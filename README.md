# 💻 Exercício 1 do trabalho de modelagem de dados

Trabalho da faculdade desenvolvido com o padrão arquitetural **MVC (Model-View-Controller)** utilizando **Python + Flask**.

---

## 📌 Descrição

Este projeto consiste em um sistema simples de gerenciamento bancário que permite:

* Criar contas bancárias
* Armazenar contas em memória (simulando um banco de dados)
* Exibir os dados da conta criada

A aplicação foi desenvolvida seguindo o padrão **MVC**, separando:

* **Model:** classes do sistema bancário (`Cliente`, `Conta`, etc.)
* **View:** interface em HTML
* **Controller:** aplicação Flask (`app.py`)

---

## 🛠️ Tecnologias utilizadas

* Python 3
* Flask
* HTML

---

## ⚙️ Pré-requisitos

Antes de rodar o projeto, você precisa ter instalado:

* Python 3.x
* Flask

Para instalar o Flask, execute:

```bash
pip install flask
```

---

## ▶️ Como executar o projeto

1. Clone o repositório ou baixe os arquivos

2. Acesse a pasta do projeto pelo terminal

3. Execute o comando:

```bash
python app.py
```

4. Abra o navegador e acesse:

```
http://127.0.0.1:5000
```

---

## 📁 Estrutura do projeto

```
Tarefa_modelagem_de_dados/
 ├── app.py
 ├── model.py
 └── templates/
      ├── index.html
      └── conta.html
```

---

## 📚 Observações

* O sistema utiliza uma lista em memória para simular um banco de dados
* O Flask é utilizado apenas como controlador e para renderizar as páginas HTML
* Este projeto tem fins acadêmicos

---

## 👨‍💻 Autor

Desenvolvido para atividade acadêmica.
