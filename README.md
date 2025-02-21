# Projeto 2 - Web Full-Stack

## Sobre
Este projeto é uma plataforma desenvolvida com **Django** para o gerenciamento de pacientes e consultas de terapia. O sistema permite o cadastro de pacientes, registro de consultas, acompanhamento de tarefas terapêuticas e gerenciamento de estado de consultas.

## Diagrama de Fluxo de dados

![Image](https://github.com/user-attachments/assets/55b6dd2f-5f1a-4bf5-9d09-6bbbda58f978)

## Diagrama Entidade-Relacionamento

![Image](https://github.com/user-attachments/assets/7c10a368-58c6-4a37-b445-5788fe73c5b5)

## Tecnologias Utilizadas
- **Back-end**: Django, SQLite3
- **Front-end**: HTML, Tailwind CSS, Pillow

## Funcionalidades
- **Gerenciar pacientes:** Permite visualizar, adicionar e editar pacientes.
  ![Image](https://github.com/user-attachments/assets/ac14b054-c334-4250-a716-dd1437fcecd3)
  
- **Registrar consultas:** Permite registrar consultas com humor, detalhes de um paciente, além da renderização de um gráfico comparando níveis de humor.
  ![Image](https://github.com/user-attachments/assets/9c9b9612-18a2-4f90-83c1-66adf62b12d0)
  
  ![Image](https://github.com/user-attachments/assets/1e63a091-bcac-44aa-a3df-f428426da962)
  
- **Visualizar consultas:** Se o paciente tem seu indicador pagamento como "Ativo", pode acessar suas consultas e detalhes de exercícios adicionados.

  ![Image](https://github.com/user-attachments/assets/42b6a2ec-a7b9-4f56-a986-04f5fac1e0e6)

## Como Rodar o Projeto

1. **Clone o repositório**:
   ```sh
   git clone --branch projeto_2 --single-branch https://github.com/lucaslpdacosta/4d4p.git
   ```

2. **Crie um ambiente virtual**:
   ```sh
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # Linux/macOS
   ```

3. **Execute as migrations**:
   ```sh
   python manage.py migrate
   ```

4. **Inicie o servidor**:
   ```sh
   python manage.py runserver
   ```

5. **Acesse a URL no navegador**: **http://localhost:8000/pacientes**
