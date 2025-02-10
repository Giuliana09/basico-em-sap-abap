# 🚀 Projeto ABAP - Gestão de Clientes

Este projeto é um sistema simples de **gestão de clientes** utilizando a linguagem **ABAP**, desenvolvido como parte do **Projeto Final ** no curso: ** ABAP for Girls**. O objetivo do sistema é permitir ao usuário **cadastrar, editar e exibir relatórios** de clientes a partir de uma tabela no banco de dados.

---

## 🛠 Funcionalidades

O sistema oferece as seguintes funcionalidades para o gerenciamento de clientes:

### 1. 📋 **Cadastrar Cliente**
- O usuário pode cadastrar novos clientes, informando os dados como nome, RG, CPF, data de nascimento e endereço.
- O sistema verifica se os campos obrigatórios (como RG, CPF e nome) foram preenchidos e exibe mensagens de erro caso algum campo essencial esteja vazio.
- Após o cadastro, a informação é gravada no banco de dados e uma mensagem de **sucesso** ou **erro** é exibida.

### 2. ✏️ **Editar Cliente**
- O usuário pode editar os dados de um cliente já cadastrado, fornecendo o RG e o CPF do cliente a ser editado.
- O sistema busca os dados do cliente no banco de dados e permite a modificação dos dados como nome, RG, CPF, data de nascimento e endereço.
- Se o cliente não for encontrado, uma mensagem de **erro** é exibida.

### 3. 📊 **Exibir Relatório de Clientes**
- O usuário pode gerar um relatório de clientes filtrado por nome, RG e CPF.
- Os dados dos clientes são extraídos do banco de dados e exibidos de forma organizada, com campos como nome, RG, CPF, data de nascimento e endereço.

---

## 🎨 Tela de Seleção

O programa apresenta uma tela de seleção para o usuário escolher a operação desejada:

- **Opções**: 
  - **Cadastrar Cliente**
  - **Editar Cliente**
  - **Exibir Relatório**
  
- **Campos de Entrada**:
  - Para **Exibir Relatório**, são fornecidos filtros como nome, RG e CPF.
  - Para **Cadastrar Cliente** e **Editar Cliente**, são necessários campos para nome, RG, CPF, data de nascimento e endereço.

---

## 🗂 Estrutura de Dados

- **Tabela ZTCLIENTE0440**: Contém os dados dos clientes, com campos como `cliente`, `rg`, `cpf`, `data` (data de nascimento) e `endereco`.

---

## 💬 Mensagens de Erro e Sucesso

- **Erros**: Quando os campos obrigatórios não são preenchidos, o sistema exibe mensagens de erro para guiar o usuário.
- **Sucesso**: Mensagens de confirmação são exibidas após o sucesso das operações de cadastro e edição.

---

## 💻 Código ABAP

O código é estruturado da seguinte forma:

- **Declaração de Telas**: Utilização de parâmetros e radio buttons para selecionar a operação desejada.
- **Lógica de Seleção e Execução**: Processamento das operações conforme a opção escolhida (cadastrar, editar ou exibir relatório).
- **Tabelas Internas**: Armazenamento temporário dos dados de clientes durante a execução das operações.

---

## 🧑‍💻 Como Usar

1. Execute o programa no ambiente SAP.
2. Escolha a operação desejada na tela de seleção.
3. Preencha os campos conforme necessário e clique em "Executar".
4. Para **cadastrar** ou **editar**, verifique se todos os campos obrigatórios estão preenchidos.
5. Para **exibir o relatório**, forneça os filtros de nome, RG ou CPF.

---

## ⚙️ Tecnologias Utilizadas

- **ABAP** (Advanced Business Application Programming)
- **SAP** (Sistema de Gestão Empresarial)

---
<p align="center">
  <img src="https://github.com/user-attachments/assets/4b8ea0b9-0dfa-410d-9e2d-22ce16a79ca8" width="700" />
</p>  

