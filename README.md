# README do Projeto de Análise de Salários

Este repositório contém dados e scripts de análises relacionadas à relação entre os anos de experiência e salários de profissionais em uma indústria fictícia. O foco principal do projeto é utilizar técnicas de Data Science para extrair insights sobre como a experiência pode afetar o salário de uma pessoa.

## Estrutura do Projeto

O projeto consiste nos seguintes arquivos principais:

1. **.gitignore** - Contém especificações de arquivos e diretórios que devem ser ignorados pelo git. Atualmente, ignora o diretório `venv` que pode conter um ambiente virtual Python.

2. **Salary_Data.csv** - Um conjunto de dados em formato CSV que contém duas colunas: `YearsExperience` e `Salary`. Esses dados servem como a base principal para análises de correlação entre a experiência profissional em anos e os salários correspondentes.

3. **modelagem.ipynb** - Um Jupyter Notebook que inclui o código e as análises realizadas sobre os dados. Este notebook está dividido em células que:
   - Importam as bibliotecas necessárias.
   - Criam e manipulam a base de dados.
   - Realizam visualizações e modelagem estatística para entender a relação entre os anos de experiência de profissionais e seus salários.

## Pré-requisitos

Para executar o projeto, você precisará de:

- Python 3
- Pacotes Python: (pode variar conforme o desenvolvimento do notebook, mas aqui estão alguns exemplos)
    - Pandas
    - NumPy
    - Matplotlib
    - Scikit-learn
- Um ambiente virtual Python (recomendado).

## Configuração do Ambiente

Para configurar o ambiente Python para executar o notebook, siga estes passos (assumindo que você já tenha o Python e o pip instalados):

```bash
python -m venv venv
source venv/bin/activate  # Para usuários de Unix/MacOS
venv\Scripts\activate      # Para usuários de Windows
pip install pandas numpy matplotlib scikit-learn
```

## Execução

Para visualizar e executar o notebook `modelagem.ipynb`, você precisará de um servidor Jupyter, que pode ser iniciado com:

```bash
jupyter notebook
```

Navegue até o arquivo `modelagem.ipynb` através da interface do Jupyter e execute as células para visualizar as análises.

## Conclusão

Este projeto oferece uma análise inicial sobre como os anos de experiência impactam nos salários. Futuras análises poderiam incluir modelos preditivos mais complexos e inclusão de mais variáveis, caso os dados estejam disponíveis.