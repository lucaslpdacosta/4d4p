# Projeto 1 - Python Puro

Este projeto é um simulador de contas bancárias, permitindo a criação e movimentação de contas entre diferentes bancos. Ele permite realizar transações como transferências, entradas e saídas de dinheiro, além de visualizar um histórico e gerar gráficos das movimentações.

## Tecnologias Utilizadas
- **Python**
- **SQLModel** (para gerenciamento do banco de dados de forma local)
- **Matplotlib** (para geração de gráficos)

## Tabelas do Banco de Dados:

![Image](https://github.com/user-attachments/assets/88f199d7-2fc4-4879-a654-39b4a5172f24)

## Funcionalidades

- Interface:

  ![Image](https://github.com/user-attachments/assets/26544d19-6e91-4b68-bcac-73c11d6a3d43)

- Criar contas bancárias associadas a um banco específico.
  
  ![Image](https://github.com/user-attachments/assets/b5cdd5ee-c06a-43f8-881b-839a2dfa5f19)

- Movimentar dinheiro (entrada e saída de valores).
  
  ![Image](https://github.com/user-attachments/assets/bc0f068a-01c1-4575-855a-9ed8886a7f63)

- Transferir saldo entre contas (só ocorrem se houver saldo suficiente).
  
  ![Image](https://github.com/user-attachments/assets/6f63f08e-8246-4963-99a9-7ac2b4bbed1c)

- Desativar contas (contas com saldo não podem ser desativadas).
  
  ![Image](https://github.com/user-attachments/assets/1d5eff7d-8888-402e-9ae2-018946718230)

- Consultar saldo somado de todas as contas.
  
  ![Image](https://github.com/user-attachments/assets/70cce339-2030-4903-9ec4-5901646f5ded)

- Filtrar movimentações por período.
  
  ![Image](https://github.com/user-attachments/assets/f28bf971-f7b5-4a57-9072-f8d57e2e0670)

- Gerar gráfico com os saldos das contas ativas.
  
  ![Image](https://github.com/user-attachments/assets/e414ca67-19e6-4025-a96c-dab6c84bcf1b)

## Como Rodar o Projeto

1. **Clone o repositório**:
   ```sh
   git clone --branch projeto_1 --single-branch https://github.com/lucaslpdacosta/4d4p.git
   ```

2. **Crie um ambiente virtual**:
   ```sh
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # Linux/macOS
   ```

3. **Instale as dependências**:
   ```sh
   pip install sqlmodel matplotlib
   ```

4. **Execute o arquivo templates.py**:
   ```sh
   python templates.py
   ```
