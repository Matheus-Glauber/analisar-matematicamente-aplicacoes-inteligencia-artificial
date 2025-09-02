# Análise Matemática de Aplicações de Inteligência Artificial

Este projeto contém notebooks Jupyter para análise matemática e estatística de dados, com foco em aplicações de inteligência artificial. O projeto utiliza o dataset do Titanic para demonstrar técnicas de análise exploratória de dados.

## 📁 Estrutura do Projeto

```
analisar-matematicamente-aplicacoes-inteligencia-artificial/
├── README.md                 # Este arquivo
├── .gitignore               # Arquivos ignorados pelo Git
├── .venv/                   # Ambiente virtual Python (criado após setup)
├── aula_01.ipynb           # Notebook principal com análise do Titanic
└── data/
    └── titanic.csv         # Dataset do Titanic
```

## 🛠️ Pré-requisitos

- **Python 3.8+** instalado no sistema
- **Visual Studio Code**
- **Git** (opcional, para controle de versão)

## ⚙️ Configuração do Ambiente

### 1. Clone ou baixe o projeto

```bash
git clone https://github.com/Matheus-Glauber/analisar-matematicamente-aplicacoes-inteligencia-artificial.git
cd analisar-matematicamente-aplicacoes-inteligencia-artificial
```

### 2. Configuração do Ambiente Virtual Python

#### 2.1. Criar o ambiente virtual

```bash
# No macOS/Linux:
python3 -m venv .venv

# No Windows:
python -m venv .venv
```

#### 2.2. Ativar o ambiente virtual

```bash
# No macOS/Linux:
source .venv/bin/activate

# No Windows (Command Prompt):
.venv\Scripts\activate

# No Windows (PowerShell):
.venv\Scripts\Activate.ps1
```

#### 2.3. Instalar dependências

```bash
pip install --upgrade pip
pip install pandas jupyter ipykernel
```

### 3. Configuração do VS Code

#### 3.1. Instalar extensões necessárias

Abra o VS Code e instale as seguintes extensões:

1. **Python** (Microsoft) - `ms-python.python`
2. **Jupyter** (Microsoft) - `ms-toolsai.jupyter`

**Como instalar:**

- Pressione `Ctrl+Shift+X` (ou `Cmd+Shift+X` no Mac)
- Pesquise por "Python" e "Jupyter"
- Clique em "Install" para cada extensão

#### 3.2. Configurar o interpretador Python

1. Abra o VS Code na pasta do projeto:

   ```bash
   code .
   ```

2. Abra a paleta de comandos: `Ctrl+Shift+P` (ou `Cmd+Shift+P` no Mac)

3. Digite "Python: Select Interpreter" e selecione a opção

4. Escolha o interpretador do ambiente virtual:
   ```
   ./.venv/bin/python
   ```

## 🚀 Como Executar o Projeto

### 1. Abrir o notebook

1. No VS Code, navegue até o arquivo `aula_01.ipynb`
2. Clique duas vezes para abrir o notebook

### 2. Selecionar o kernel

1. No canto superior direito do notebook, clique em "Select Kernel"
2. Escolha "Python Environments"
3. Selecione o ambiente `.venv` que você criou

### 3. Executar as células

- **Executar célula individual**: `Shift+Enter`
- **Executar todas as células**: `Ctrl+A` seguido de `Shift+Enter`
- **Executar célula e inserir nova**: `Alt+Enter`

## 📊 Conteúdo do Notebook

O notebook `aula_01.ipynb` contém:

### 1. **Importação de Bibliotecas**

- Configuração do ambiente pandas

### 2. **Carregamento e Visualização de Dados**

- Leitura do dataset do Titanic
- Primeiras visualizações com `head()` e `tail()`

### 3. **Análise Estrutural**

- Informações do dataset com `info()`
- Estatísticas descritivas com `describe()`

### 4. **Manipulação de Dados**

- Renomeação de colunas
- Seleção de dados específicos

### 5. **Análise Estatística Detalhada**

- Medidas de tendência central (média, mediana, moda)
- Medidas de dispersão (desvio padrão)
- Valores extremos e agregações

## 🔧 Solução de Problemas Comuns

### Problema: Kernel não encontrado

**Solução:**

1. Certifique-se de que o ambiente virtual está ativado
2. Execute: `python -m ipykernel install --user --name=.venv`
3. Reinicie o VS Code

### Problema: Pandas não encontrado

**Solução:**

```bash
# Ative o ambiente virtual primeiro
source .venv/bin/activate  # macOS/Linux
# ou
.venv\Scripts\activate     # Windows

# Depois instale o pandas
pip install pandas
```

### Problema: Extensão Jupyter não funciona

**Solução:**

1. Desinstale e reinstale a extensão Jupyter
2. Reinicie o VS Code
3. Certifique-se de que a extensão Python também está instalada

## 📋 Comandos Úteis

```bash
# Verificar dependências instaladas
pip list

# Atualizar todas as dependências
pip install --upgrade pandas jupyter ipykernel

# Desativar ambiente virtual
deactivate

# Remover ambiente virtual (se necessário recriar)
rm -rf .venv  # macOS/Linux
rmdir /s .venv  # Windows
```

## 📚 Dependências do Projeto

- **pandas**: Manipulação e análise de dados
- **jupyter**: Interface de notebooks
- **ipykernel**: Kernel Python para Jupyter

## 🤝 Contribuindo

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📧 Contato

**Matheus Glauber**

- GitHub: [@Matheus-Glauber](https://github.com/Matheus-Glauber)

---

**Nota:** Este projeto foi desenvolvido com fins educacionais para demonstrar técnicas de análise de dados e estatística aplicada à inteligência artificial.
