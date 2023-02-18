# Coffee And Code
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

Este projeto é uma exploração do dataset [Coffee And Code](https://www.kaggle.com/datasets/shrutikunapuli/coffee-and-code-dataset) fornecido pelo [Kaggle](https://www.kaggle.com/). O foco é explorar os dados e descobrir quaisquer insights interessantes ou padrões que possam estar presentes.

## Conteúdo
- Descrição dos Dados
- Objetivos
- Ferramentas Usadas
- Integrantes
- Recomendações
- Instalação
- Organização do projeto
- Contribuições

## Descrição dos Dados
O conjunto de dados consiste em uma variedade de recursos, como '...'. Também inclui informações sobre o '...' no conjunto de dados.

## Objetivos
 Os objetivos deste projeto são: 

- Entender melhor os dados disponíveis;
- Descobrir padrões e relações entre as variáveis;
- Ajudar na tomada de decisão baseada em dados.

## Ferramentas Usadas 
Este projeto foi concluído usando Python e suas bibliotecas associadas, como NumPy, Pandas, Tqdm, Matplotlib, Seaborn e Ipykernel.

## Integrantes
Projeto desenvolvido pelos Dev:

- [Matheus Miranda Brandão](https://github.com/MatBrands/)

## Recomendações
- Ao desenvolver uma nova funcionalidade o dev deverá informar de maneira breve e sucinta sobre o que foi feito.
- Em relação aos commits será utilizado um padrão:
    - Commits de novas features. Ex: git commit -m "New: Readme"
    - Commits de updates. Ex: git commit -m "Updated: Readme"
    - Commits de remoção. Ex: git commit -m "Removed: Readme"

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.11.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
conda env create -f environment.yml
```

- Ativar
```sh
conda activate coffe_and_code_venv
```

- Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

- Criar ambiente virtual
```sh
python -m venv coffe_and_code_venv
```

- Ativar
```sh
source ./coffe_and_code_venv/bin/activate
```

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
pip install -r requirements.txt
```

- Desativar
```sh
deactivate
```

## Organização do projeto
```sh
...
```

## Contribuições
As contribuições são sempre bem-vindas em projetos de análise exploratória de dados. Se você é um desenvolvedor, cientista de dados ou analista, pode contribuir para o projeto de várias maneiras, tais como:

- Criar novos notebooks;
- Desenvolver novas análises;
- Encontrar e corrigir erros;
- Ajudar a documentar o código;
- Refatorar o código existente.