# IFood Dev Week 2023

> ## **Net Promoter Score (NPS)**

O Net Promoter Score (NPS) é uma métrica amplamente utilizada para medir a lealdade e satisfação dos clientes em relação a uma determinada empresa, marca ou produto. Ele foi desenvolvido por Fred Reichheld, um consultor de negócios da Bain & Company, em 2003.

O NPS é baseado em uma pergunta simples feita aos clientes: "Em uma escala de 0 a 10, o quanto você indicaria nossa empresa/produto/serviço a um amigo ou colega?". Com base nas respostas, os clientes são divididos em três categorias:

1. Promotores (Promoters): São aqueles que dão notas entre 9 e 10. Eles são entusiastas e leais à empresa, tendem a recomendar ativamente a marca para outras pessoas e são considerados os principais impulsionadores do crescimento dos negócios.

2. Neutros (Neutrals): São aqueles que dão notas entre 7 e 8. Eles estão satisfeitos com a empresa, mas não são entusiastas a ponto de recomendá-la a outras pessoas. Eles não têm um impacto significativo no crescimento ou declínio dos negócios.

3. Detratores (Detractors): São aqueles que dão notas entre 0 e 6. Eles estão insatisfeitos e podem expressar opiniões negativas sobre a empresa. Os detratores representam um risco para a empresa, pois suas experiências negativas podem afetar a reputação da marca e desencorajar potenciais clientes.

Para calcular o Net Promoter Score, subtrai-se a porcentagem de detratores da porcentagem de promotores. O resultado varia de -100 a 100, representando a pontuação geral da empresa em termos de lealdade do cliente.

O NPS não é apenas uma métrica isolada, mas também uma abordagem para o gerenciamento da experiência do cliente. Ele fornece uma visão geral do desempenho da empresa em relação à satisfação e lealdade dos clientes, permitindo identificar áreas de melhoria e acompanhar o progresso ao longo do tempo.

Muitas empresas realizam pesquisas de NPS regularmente para obter insights valiosos sobre a percepção dos clientes e implementar ações corretivas com base nos feedbacks recebidos. O NPS pode ser usado em diversos setores e é uma ferramenta poderosa para impulsionar o crescimento dos negócios, aumentar a fidelidade dos clientes e melhorar a experiência do cliente como um todo.

> ## **Pandas**

Pandas é uma biblioteca de análise de dados em Python amplamente utilizada. Ela fornece estruturas de dados e ferramentas para manipulação e análise eficiente de dados numéricos e tabulares. Com o Pandas, é possível realizar operações como leitura e escrita de dados, limpeza, transformação, filtragem, agregação e visualização de informações.

O principal objeto de dados do Pandas é o DataFrame, que pode ser visto como uma tabela flexível onde os dados são organizados em colunas nomeadas. Cada coluna do DataFrame pode conter diferentes tipos de dados, como números, strings ou datas. Além disso, o Pandas também oferece a estrutura de dados Series, que é uma matriz unidimensional de dados com rótulos.

Aqui está um exemplo simples de como utilizar o Pandas para criar um DataFrame e realizar algumas operações básicas:

```python
import pandas as pd

# Leitura dos dados no formato CSV
dados = pd.read_csv("./data/feedbacks.csv", delimiter=";")
print(dados)
```

Saída do exemplo acima:

![](./assets/exemplo_dataframe.png)

Neste exemplo, nos lemos os dados do arquivo `feedbacks.csv` a partir do método `read_csv()` que retorna um DataFrame contendo informações fictícias de feedbacks feitos por usuários. 

Essa é apenas uma introdução às funcionalidades do Pandas. A biblioteca é extremamente poderosa e oferece diversas outras funções e recursos para manipulação e análise de dados. É amplamente utilizada em tarefas de ciência de dados, análise exploratória, limpeza de dados, preparação de dados para modelagem, entre outras aplicações.