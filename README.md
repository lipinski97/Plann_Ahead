# Buy&Plan - Cronograma Físico e de Compras

## Sobre o Projeto
Um painel de visualização estática focado na integração entre o **Planejamento Físico de Obras** e a **Previsão de Compras (Suprimentos)**. 

O objetivo da interface é evidenciar o conceito de *Lookahead* e *Kitting*, cruzando as datas de início das atividades do cronograma com a lista de materiais (BOM - Bill of Materials) e o tempo de entrega dos fornecedores (Lead Time). Isso permite calcular a data limite exata para o disparo de pedidos, evitando atrasos na linha de produção por falta de insumos críticos.

## O Problema que Resolve
Na gestão de obras, a desconexão entre o setor de engenharia (cronograma) e o setor de suprimentos (compras) gera gargalos. Este painel propõe uma visão unificada onde:
- O engenheiro sabe o que precisa ser executado e quando.
- O comprador sabe exatamente o que pedir, a quantidade e a data limite (*Drop Dead Date*) para emitir a ordem de compra.

## Funcionalidades da Interface
- **Tabela de Correlação:** Relaciona a Atividade (Local/Pavimento) com o Kit de Materiais necessários para execução (ainda tá limitado a um único material)
- **Lead Time:** Alertas visuais (em vermelho) para datas limites de pedidos.

## Tecnologias Utilizadas
- HTML5
- CSS3

## Como Executar
Como é um projeto puramente front-end estático, não há necessidade de build ou servidores complexos.
1. Clone o repositório: `git clone https://github.com/seu-usuario/lookahead-cronograma.git`
2. Abra o arquivo `cronograma.html` diretamente em qualquer navegador web moderno.

## Próximos Passos (Roadmap Técnico)
- Fazer o upload do cronograma base para as datas das atividades;
- Fazer o upload de um orçamento, para ter uma previsão de gasto das compras;
- Filtro e agrupamento de data e locais (exemplo: térreo, pavimentos);
- Entre outras coisas.
