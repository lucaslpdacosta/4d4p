# Projeto 3 - API REST

## Sobre
API REST para gerenciamento de alunos de Jiu-Jitsu, permitindo cadastro de alunos, consulta de progresso individual e registro de aulas concluídas.

## Diagrama de Fluxo de dados

![Image](https://github.com/user-attachments/assets/cd00999d-8c1c-4474-8801-28dee01e8bc9)

## Diagrama Entidade-Relacionamento

![Image](https://github.com/user-attachments/assets/cf7e6d54-15c7-4979-af3c-23e9e6733165)

## Tecnologias Utilizadas
- Python
- Django
- Django Ninja
- Pydantic
- SQLite3

## Funcionalidades

- **Criar um novo aluno**  
  ```
  (POST) /
  ```
  ![Image](https://github.com/user-attachments/assets/a626439e-42bf-45b0-91e2-3bf5c8e89b5e)

- **Lista todos os alunos**  
  ```
  (GET) /aluno/
  ```
  ![Image](https://github.com/user-attachments/assets/c53a1df0-c58a-4767-9825-acec539c4493)

- **Marca aula concluida para o aluno**  
  ```
  (POST) /aula_realizada/
  ```
  ![Image](https://github.com/user-attachments/assets/1b653111-d0f5-4a08-aa0c-c35057f56a32)

- **Consulta o progresso de um aluno pelo e-mail**  
  ```
  (GET) /progresso_aluno/
  ```
  ![Image](https://github.com/user-attachments/assets/e6b4e759-274e-4600-b774-1c3e26c4c3c1)

- **Atualiza dados de um aluno**  
  ```
  (PUT) /alunos/{aluno_id}
  ```
  ![Image](https://github.com/user-attachments/assets/bd029338-381c-4153-bcba-c0a434694c2a)

## Como Rodar o Projeto

1. **Clone o repositório**:
   ```sh
   git clone --branch projeto_3 --single-branch https://github.com/lucaslpdacosta/4d4p.git
   ```

2. **Crie um ambiente virtual**:
   ```sh
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # Linux/macOS
   ```

3. **Instale as dependências**:
   ```sh
   pip install django django-ninja pydantic
   ```
   
4. **Execute as migrations**:
   ```sh
   python manage.py migrate
   ```

5. **Inicie o servidor**:
   ```sh
   python manage.py runserver
   ```
