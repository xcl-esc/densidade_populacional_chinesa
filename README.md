# 📊 Estudo de Resiliência Populacional e Econômica Chinesa (1950–1975)

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

> 📖 **Para Recrutadores e Avaliadores:** 
> O processo de fundamentação histórica, o **Diário de Bordo**, as hipóteses e a documentação completa estão centralizados no Notion.
> 
> 🔗 **[Acessar Documentação Completa e Diário de Bordo no Notion](https://app.notion.com/p/Estudo-de-Resili-ncia-Populacional-Chinesa-3acd6ce46588805bb167da79e6e34c5e?source=copy_link)**

---

## 🎯 Sobre o Projeto

Uma análise e predição sobre a densidade populacional e econômica chinesa utilizando técnicas de análise descritiva e machine learning para avaliar o choque e a recuperação no período da Grande Fome (1958–1961).

### 🛠️ Tech Stack & Ferramentas
* **Linguagem:** Python 3.10
* **Manipulação de Dados:** Pandas, NumPy
* **Análise & Modelagem:** Scikit-Learn, SQLite
* **Documentação & Processo:** Notion
* **Estrutura de Projeto:** Cookiecutter Data Science (CCDS)

---

## 🚀 Como Executar o Projeto Localmente

1. **Clonar o repositório:**
   ```bash
   git clone (https://github.com/xcl-esc/densidade_populacional_chinesa.git)
   cd densidade_populacional_chinesa

2. **Ativar o ambiente virtual e instalar dependências:**
    ```powershell
    ### Ative seu ambiente virtual
    .\venv\Scripts\Activate.ps1

    ### Instale os pacotes necessários
    pip install -r requirements.txt

3. **Abrir a exploração de dados:**
    Abra o VS Code e navegue até a pasta notebooks/ para rodar as análises interativas.
    ```text
    📁 Estrutura do Repositório (Project Organization)

    ├── LICENSE             <- Licença open-source (MIT)
    ├── Makefile            <- Comandos de atalho para automação
    ├── README.md           <- Apresentação principal do repositório
    ├── data
    │   ├── external        <- Dados auxiliares e dicionários
    │   ├── interim         <- Dados intermediários em fase de transformação
    │   ├── processed       <- Datasets finais limpos e prontos para modelagem
    │   └── raw             <- Arquivos CSV brutos originais (ONU, Maddison Project)
    │
    ├── docs                <- Documentação auxiliar do projeto (MkDocs)
    ├── models              <- Modelos de ML salvos (.pkl / .joblib)
    ├── notebooks           <- Jupyter Notebooks com as etapas de EDA e simulação
    ├── pyproject.toml      <- Configurações do pacote Python do projeto
    ├── references          <- Dicionários de dados, referências acadêmicas e artigos
    ├── reports             <- Relatórios exportados
    │   └── figures         <- Visualizações e gráficos gerados (Matplotlib / Seaborn)
    ├── requirements.txt    <- Dependências e bibliotecas do ambiente
    │
    └── densidade_e_economia   <- Código-fonte modular reutilizável do projeto
        ├── __init__.py        <- Torna o repositório um módulo Python
        ├── config.py          <- Armazenamento de variáveis globais e caminhos
        ├── dataset.py         <- Scripts de extração e carga de dados
        ├── features.py        <- Engenharia de variáveis
        ├── plots.py           <- Funções para geração de gráficos padronizados
        └── modeling           <- Scripts de treino e inferência dos modelos
            ├── predict.py
            └── train.py
    ```



Projeto desenvolvido por Cleber Santos como parte do portfólio de Ciência de Dados.