# Censo Escolar 2022

## Análise Exploratória de Dados para prospecção de escolas privadas no Brasil.

#### Desenvolvido por Victor Vilela.

# 1. Problema de Negócio

Uma escola de inglês desenvolvou um novo serviço de realizar consultorias sobre o ensino do idioma para as escolas particulares no Brasil.
Por se tratar de uma nova unidade de negócio, precisam identificar quais escolas podem oferecer este serviço.

## 1.1 Objetivo

Uma lista de escolas privadas com maiores chances de venda para um serviço de consultoria.

# 2. Premissas.



# 3. Estratégia de Solução

    Estratégia baseada na metodologia CRIPS-DS

## 3.1. Produto Final
- Arquivo formato .csv com as principais escolas contendo dados necessários para abordagem ao cliente. 

## 3.2. Ferramentas
- Python
- Pandas
- Seaborn
- Matplotlib

## 3.3. Processo

**Step 01. Data Description and ETL:** Análise Descritiva da base, considerando o problema de negócio demandado. Além disso, fora realizado o tratamento e extração dos dados para iniciar a exploração de dados.

**Step 02. Análise Exploratória de Dados (EDA):** Exploração dos dados para extrair as escolas com maiores potenciais de venda, análises uni, bi e multivariadas.

**Step 03. Preparação da lista de escolas para prospecção:** Após filtrar as principais escolas para iniciar as vendas do serviço de consultoria, a preparação consiste em trazer apenas os dados relevantes para o time comercial.

**Step 04. Transformação para CSV:** Conversão para o formato **.csv** para disponibilizar ao time comercial.

# 4. Top 3 Data Insights

1. **Matrículas por idade em cada região do Brasil**
![Alt text](/docs/image.png)

2. **As 10 cidades com maiores quantidades de matrículas para os ensinos infantil, fundamental e médio**

| index | sg_uf | no_municipio | qt_mat_bas | qt_mat_fund | qt_mat_med |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 0 | 3298 | SP | São Paulo | 959522.0 | 353961.0 | 80885.0 |
| 1 | 2335 | RJ | Rio de Janeiro | 458396.0 | 233191.0 | 61683.0 |
| 2 | 565 | DF | Brasília | 195686.0 | 94264.0 | 26453.0 |
| 3 | 464 | CE | Fortaleza | 191670.0 | 110233.0 | 21226.0 |
| 4 | 918 | MG | Belo Horizonte | 178466.0 | 75760.0 | 21967.0 |
| 5 | 336 | BA | Salvador | 177838.0 | 89168.0 | 19687.0 |
| 6 | 2016 | PR | Curitiba | 133790.0 | 56741.0 | 18756.0 |
| 7 | 2633 | RS | Porto Alegre | 133290.0 | 45163.0 | 12602.0 |
| 8 | 1794 | PE | Recife | 126402.0 | 71008.0 | 13417.0 |
| 9 | 671 | GO | Goiânia | 103042.0 | 60589.0 | 15155.0 |

3. **Dessas 10 cidades, quais são os bairros com as maiores quantidades de matrículas?**

![Alt text](/docs/image_2.png)

# 6. Resultados para o Negócio
- A empresa agora possui uma lista de 545 escolas nos 10 principais bairros do país para iniciar a prospecção e venda dos novos serviços.

# 7. Conclusões
- Para o time comercial iniciar as vendas o mais rápido possível, era importante levantar os principais indícios para que uma escola privada se interesse nesse novo serviço. 
Por conta disso, foram consideradas as regiões brasileiras com as maiores quantidades de matrículas por ensinos básico, fundamental e médio que, a princípio, as vendas seriam consideradas em escolas que possuem maior quantidade de alunos.

# 8. Lições Aprendidas
1. Conhecimento de negócio sobre consultoria de inglês para escolas privadas
2. Aprimoramento em manipulação e tratamento de dados
3. Visualização de dados com estilização avançada no Seaborn e Matplotlib

# 9. Próximos passos
- Levantar uma lista de escolas com estruturas médias que tenham interesse em aprimorar suas aulas de inglês.
- Realizar testes de hipótese a um novo ciclo de EDA.
