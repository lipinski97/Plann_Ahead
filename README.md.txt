# Lookahead - Cronograma Integrado (Buy Ahead) 🏗️⚡

## Sobre o Projeto
Um painel de visualização (mockup estático) focado na integração entre o **Planejamento Físico de Obras** e a **Previsão de Compras (Suprimentos)**. 

O objetivo da interface é evidenciar o conceito de *Lookahead* e *Kitting*, cruzando as datas de início das atividades do cronograma com a lista de materiais (BOM - Bill of Materials) e o tempo de entrega dos fornecedores (Lead Time). Isso permite calcular a data limite exata para o disparo de pedidos, evitando atrasos na linha de produção por falta de insumos críticos.

## O Problema que Resolve
Na gestão de obras, a desconexão entre o setor de engenharia (cronograma) e o setor de suprimentos (compras) gera gargalos. Este painel propõe uma visão unificada onde:
- O engenheiro sabe o que precisa ser executado e quando.
- O comprador sabe exatamente o que pedir, a quantidade e a data limite (*Drop Dead Date*) para emitir a ordem de compra.

## Funcionalidades da Interface
- **Tabela de Correlação:** Relaciona a Atividade (Local/Pavimento) com o Kit de Materiais.
- **Destaque de Insumos Críticos:** Indicadores visuais para materiais que podem travar o caminho crítico da obra.
- **Cálculo Visual de Lead Time:** Alertas visuais (em vermelho) para datas limites de pedidos.

## Tecnologias Utilizadas
- HTML5 Semântico
- CSS3 (Variáveis, Flexbox, UI/UX orientada a dados)
- Fonte Inter (Google Fonts) para legibilidade de dados numéricos.

## Como Executar
Como é um projeto puramente front-end estático, não há necessidade de build ou servidores complexos.
1. Clone o repositório: `git clone https://github.com/seu-usuario/lookahead-cronograma.git`
2. Abra o arquivo `cronograma.html` diretamente em qualquer navegador web moderno.

## Próximos Passos (Roadmap Técnico)
- [ ] Refatoração para componentização (React ou Vue.js).
- [ ] Desenvolvimento de API REST para alimentar a tabela com dados reais de ERPs.
- [ ] Algoritmo de cálculo automático da `Data Limite` (Data de Início da Atividade - Lead Time).