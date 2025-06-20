# PRD - Product Requirements Document

## Introdução & Objetivo

Este projeto consiste no desenvolvimento de uma análise estatística aplicada ao setor de **hotelaria**, utilizando dados simulados que representam informações operacionais e financeiras de um hotel. O principal objetivo é transformar dados brutos em informações estratégicas que possam auxiliar na tomada de decisões gerenciais, operacionais e comerciais.

O produto final é um sistema analítico que permite explorar dados sobre perfis de clientes, desempenho financeiro, sazonalidade, padrões de consumo e relacionamento entre variáveis-chave como tempo de estadia, faturamento e avaliações dos hóspedes.

Este projeto diferencia-se por aplicar conceitos estatísticos combinados com visualizações interativas e modelos preditivos, oferecendo uma ferramenta acessível e poderosa para análise de desempenho no setor hoteleiro.

## Integrantes do Grupo

- André Lucas Ferreira
- Leonardo Rodrigues
- Nickolas Machado
- Odirlei Lima

## Por que implementar isto?

A implementação deste projeto visa atender a uma necessidade crescente do mercado hoteleiro: **tomada de decisão orientada por dados**. Em um setor altamente competitivo, onde pequenas variações na demanda impactam diretamente a receita, compreender os padrões de consumo e o perfil dos hóspedes torna-se fundamental.

Além disso, o projeto oferece:
- **Visão estratégica:** suporte na precificação, promoções, gestão de ocupação e sazonalidade.
- **Acesso democrático à análise de dados:** uso de ferramentas open source como Python, sem custos de licenciamento.
- **Oportunidade de monetização futura:** este produto pode ser adaptado para ser uma solução analítica para pequenas e médias redes hoteleiras, oferecendo insights valiosos sem depender de consultorias externas.

---

## Público-alvo

| Perfil de usuário           | Descrição, necessidades e interesses |
|------------------------------|---------------------------------------|
| **Gestores de hotéis**        | Necessitam de relatórios para tomar decisões sobre preços, promoções, gestão de ocupação e sazonalidade. |
| **Analistas de dados**        | Precisam de dados organizados e visualizações claras para gerar insights e apoiar a estratégia. |
| **Acadêmicos e estudantes**   | Buscam compreender como análises estatísticas podem ser aplicadas na prática ao setor de serviços. |

---

## Personas

1. **Fernando, 45 anos – Gerente Geral de Hotel**  
Deseja aumentar a taxa de ocupação e entender melhor o comportamento dos hóspedes. Frustra-se com a falta de dados claros para decisões rápidas.

2. **Ana, 28 anos – Analista de Dados**  
Trabalha no setor de turismo e busca ferramentas que facilitem a visualização e a análise de dados operacionais e financeiros, sem depender de softwares caros.

3. **Lucas, 22 anos – Estudante de Hotelaria**  
Quer entender como os dados são utilizados para tomada de decisão no setor e desenvolver habilidades práticas em análise de dados para sua carreira.

---

## Requisitos Funcionais

1. **F1 – Análise descritiva dos dados operacionais** (**P1**)  
Exibir médias, medianas, moda, desvio padrão, variância e amplitude para variáveis como tempo de estadia, preço e faturamento.

2. **F2 – Visualizações gráficas** (**P1**)  
Gerar histogramas, boxplots, gráficos de dispersão e séries temporais para auxiliar na compreensão dos dados.

3. **F3 – Análise de correlação e regressão linear** (**P1**)  
Permitir verificar relações entre variáveis, como a relação entre tempo de estadia e total pago, além de fornecer modelos preditivos simples.

4. **F4 – Classificação das variáveis por escalas de medição** (**P2**)  
Apresentar aos usuários a definição das variáveis como nominais, ordinais, intervalares ou de razão.

5. **F5 – Relatórios automatizados e exportáveis** (**P3**)  
Gerar sumários estatísticos e gráficos em formato PDF ou Excel.

### Casos de uso

- **Caso de uso 1:** O gestor acessa a plataforma, analisa a série temporal de faturamento e identifica períodos de baixa demanda para planejar promoções.
- **Caso de uso 2:** O analista verifica a correlação entre tipos de quarto e valor médio da diária para sugerir ajustes na precificação.
- **Caso de uso 3:** O estudante utiliza o sistema para entender como medidas estatísticas são aplicadas ao setor de hotelaria, gerando gráficos para um trabalho acadêmico.

---

## Requisitos Não Funcionais

1. **NF1 – Facilidade de uso e navegação intuitiva** (**P1**)  
Interface simples e clara, que permita ao usuário gerar relatórios sem conhecimentos avançados em programação.

2. **NF2 – Portabilidade e replicabilidade** (**P2**)  
O projeto deve ser executável em qualquer máquina com Python instalado, sem necessidade de servidores robustos.

---

## Fora de escopo

- Integração com sistemas comerciais de gestão hoteleira (PMS).
- Desenvolvimento de dashboards online (este projeto é local/offline).
- Implementação de modelos de machine learning avançados (foco apenas em estatística descritiva e regressão linear simples).

---

## Dependências

- Instalação de bibliotecas Python: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels.
- Ambiente Python 3.9 ou superior.
- Sistema operacional compatível (Windows, Linux ou MacOS).

---

## Como utilizar

Para utilizar os scripts, basta acessar o site [Google Colab](https://colab.google), baixar o arquivo `Projeto_final_CD.ipynb` e abri-lo a partir do Google Colab. Os scripts estão separados por textos com os títulos das respectivas abordagens estatísticas que estão sendo utilizadas pelo script relacionado.
