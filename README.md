## **Projeto de integração entre agenda do ERP Sankhya e CRM**!

📊 Sistema para importar dados entre um sistema e outro desenvolvido em **Python** e utilizando **JSON**. Durante quase dois anos percorridos na fase de implementação, algo que travava a implementação do sistema era o fato de não ter uma integração para que fossem importados esses dados, porém com esse script, solucionei esse impeditivo e conseguimos realizar a implementação do sistema após 3 meses da minha chegada na empresa. <br>  
🌐 Tecnologias usadas: Python, JSON, Selenium.  

---

## 💻 Tecnologias Utilizadas
<div style="display: inline-block"><br>

### Linguagem e Libs
> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="5%"/>
> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/selenium/selenium-original.svg" width="5%"/>
> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/json/json-original.svg" width="5%"/>
          
---

## 📋 Funcionalidades

- **Leitura de dados em excel**: Utilizando o pandas realizei a leitura da planilha em excel linha por linha, para realizar a inserção desses dados no novo sistema.
- **Automação de mouse e teclado com python**: Automatizei o uso do teclado para realizar o login no sistema e digitar algumas outras informações.
- **Automação web utilizando Selenium**: Utilizando selenium webdriver realizei diversas funções de clique e preenchimento de informações automaticamente.
- **Json para controle de erros e tarefas duplicadas**: Utilizei um arquivo JSON para salvar os códigos que já haviam sido processados evitando processá-los novamente e gerar duplicidades.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter instalado:

- [Python](https://www.python.org/downloads/).
- IDE de sua preferência.
- Baixar as bibliotecas utilizadas via terminal. As principais bibliotecas foram:
  - pandas
  - selenium webdriver
  - datetime
  - pyperclip
  - pyautogui
  - json
- Ter um arquivo em excel com as colunas com os nomes exatamente condizentes com as colunas importadas via pandas
- Criar uma conta no Ploomes
  
### Passos

1. **Clone o Repositório**
    ```bash
    git clone https://github.com/rom-lucca/projetoImportacao.git
    ```
    Navegue até o diretório do projeto:
    ```bash
    cd projetoImportacao
    ```

2. **Configure a Planilha corretamente**
    - Utilizando a planilha que deixei como base no repositório configure a sua planilha com os dados organizados corretamente
    - Troque o caminho do arquivo excel pelo caminho do seu arquivo local

3. **Login Ploomes**
    - Crie uma conta ou caso já tenha apenas adicione o seu login e senha onde está "email@email" e "senha123"

4. **Altere o contador**
    Pode apagar as partes em que contém um contador dos funcionários que tiveram tarefas importadas ou alterar para adicionar os seus funcionários.

---

## 🗂 Estrutura do Projeto

- `criarTarefas.ipynb`: Código-fonte do projeto.
- `ids_processados.json`: JSON que contém os códigos já processados.

---
