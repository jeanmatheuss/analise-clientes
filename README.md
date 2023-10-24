# Análise de clientes de um banco

## Contexto
Este projeto consiste na análise de um dataset que contém informações de clientes de um banco. 

## Objetivo
O objetivo deste projeto é realizar uma análise exploratória dos dados e gerar gráficos para uma melhor compreensão dos clientes do banco. Ao realizar essa análise, buscamos identificar padrões, tendências e insights relevantes que possam auxiliar na tomada de decisões estratégicas.

Com base nos resultados obtidos a partir dos gráficos e da análise dos dados, é possível obter insights valiosos sobre os clientes do banco, como identificar segmentos de clientes com características específicas, entender o comportamento de compra, avaliar a relação entre a inatividade e o uso do cartão de crédito, entre outros aspectos relevantes para a estratégia do negócio.

No geral, este projeto visa explorar e visualizar os dados dos clientes do banco, proporcionando uma compreensão mais profunda e insights significativos para auxiliar nas decisões e estratégias relacionadas ao atendimento, produtos e serviços oferecidos pelo banco.


## Dados:
O dataset retirado [aqui](https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/credito.csv), inclui as seguintes variáveis:

| coluna | Dtype |
| ------: | ---- |
| idade | int |
| sexo | string |
| dependentes | int |
| escolaridade | string |
| estado_civil | string |
| salario_anual | string |
| tipo_cartao | string |
| meses_de_relacionamento | int |
| qtd_produtos | int |
| iteracoes_12m | int |
| meses_inativo_12m | int |
| limite_credito | float |
| valor_trasacoes_12m | float |
| qtd_transacoes_12m | float |

## Anáilse

Utilizando ferramentas como Python e bibliotecas de visualização de dados, como Matplotlib e Seaborn, foram criados diferentes tipos de gráficos para a análise. Alguns exemplos de gráficos gerados incluem gráficos de barras para mostrar a distribuição de variáveis categóricas.

### Principais descobertas:
- Média de idade: 46 anos;
- Média de dependentes: 2;
- 52.9% são mulheres, 47.1% são homens;
- 31.2% possuem mestrado;
- 61.3% ganham menos de $40K;
- 95.2% possuem cartão blue;
- Não há relações entre a alta escolaridade e salário.

### Próximos passos:
- Oferecer cartões com mais vantagens para quem possui alto salário e continua com cartão blue;


