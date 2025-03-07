# 💰 Sistema Bancário em Python

Este é um sistema bancário funcional desenvolvido em **Python**, permitindo cadastro de clientes, criação de contas e operações como **depósitos, saques e consulta de extrato** através de um **menu interativo**.

## 🚀 Funcionalidades

✅ **Cadastro de clientes** (CPF, nome, data de nascimento e endereço)  
✅ **Criação de contas bancárias** associadas a clientes  
✅ **Operações bancárias**:
   - **Depósito**: Adiciona saldo à conta.
   - **Saque**: Respeita limites de valor e quantidade diária.
   - **Extrato**: Exibe o histórico de transações.
✅ **Listagem de contas cadastradas**  
✅ **Restrições para segurança**:
   - Limite de **R$500,00** por saque.
   - No máximo **3 saques diários**.
   - **Uma conta por cliente**.

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Programação Orientada a Objetos (POO)**
- **Decoradores** (@property, @registrar_transacao)
- **Classes Abstratas** (ABC)

## 📌 Como Executar o Projeto

1️⃣ **Instale o Python 3** caso ainda não tenha.  
2️⃣ **Clone este repositório** ou faça o download dos arquivos.  
3️⃣ **Abra o terminal** e navegue até a pasta do projeto.  
4️⃣ **Execute o script** com o comando:

```bash
python nome_do_arquivo.py
```

## 📂 Estrutura do Código

📌 **Cliente** → Classe que armazena informações do cliente e suas contas.  
📌 **PessoaFisica** → Subclasse de Cliente, representando clientes com CPF.  
📌 **Conta** → Classe base para contas bancárias.  
📌 **ContaCorrente** → Subclasse de Conta, com regras específicas de saque.  
📌 **Transacao** → Classe abstrata para representar transações.  
📌 **Saque e Deposito** → Subclasses de Transacao para operações financeiras.  
📌 **Historico** → Registra todas as transações de uma conta.  
📌 **Menu** → Interface de texto para interação com o usuário.  

## 🔧 Melhorias Futuras

🔹 **Persistência de dados** com JSON ou banco de dados.  
🔹 Criar uma **interface gráfica** para melhor experiência do usuário.  
🔹 Melhorar o **tratamento de erros e validação de entradas**.  

## 📞 Contato

Tem sugestões ou quer contribuir? Abra uma *issue* ou envie um *pull request*!  
📧 E-mail: [ccunhalira8760@gmail.com](mailto:ccunhalira8760@gmail.com)

---
Projeto desenvolvido por **Cauã Cunha Lira**. 🚀

