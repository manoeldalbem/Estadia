# Estadia

O seguinte trabalho visa estimar o preço da estadia para a cidade do Rio de Janeiro usando dados do airbnb.

Assim, foi separado em duas partes.
- a primeira faz uma análise descritiva e exploratória dos dados, além de transformação em alguuns dados.
- a segunda foca na estimação e análise dos resultados.

A parte da análise exploratória chamou atenção por um motivo em especial:
- o preço apresenta muitos outliers e tem distribuição assimétrica.

Na parte da modelagem, foram realizadas os seguintes métodos:
- Ridge
- Lasso
- Elastic Net
- Decision Tree
- Random Forest
- Gradient Boosting

O modelo selecionado foi o Gradient Boosting por dois motivos:
- apresentou maior R2 e teve menor porcentagem do erro absoluto.

Para trabalhos futuros, a ideia é acrescentar novas variáveis e melhorar o tratamento das já inclusas (inclusive o tratamento com os outliers) com o objetivo de melhorar a performance e resultado dos modelos.
