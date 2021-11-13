# Data Science: Primeiros passos

Repositório do curso de [Data Science: primeiros passos](https://cursos.alura.com.br/course/data-science-primeiros-passos)

Neste curso veremos: 

- Entre na área de ciência de dados (data science)
- Explore dados com exploratory data analysis
- Conheça os tipos de variáveis
- Entenda o papel de visualizações como histogramas e boxplots
- Entenda a importância e dê os primeiros passos em visualizações
- Utilize medidas de resumo
- Explore seus dados em Python com Pandas, Matplotlib e Seaborn

## Ambiente de desenvolvimento

Ao executar o projeto a primeira vez:

1. Clonar projeto no github

2. Instalar Python 3.9.2

3. Instalar Anaconda

- Após instalar o Anaconda, executar , no terminal, o comando

```sh
conda init
```

4. Criar e ativar ambiente virtual

- É muito importante que o ambiente virtual seja salvo em uma pasta com um nome DIFERENTE de .env. Uma sugestão é .venv.

```sh
conda create  -p .venv python=3.9.2
conda activate ./.venv
```

5. Para instalar as bibliotecas do projeto, basta executar o comando:

    $ pip install -r requirements.txt