# Projeto 4 - Mobile Flet

Este projeto é um aplicativo frontend desenvolvido com [Flet](https://flet.dev/) para integrar-se a uma API feita com Django Ninja. Ele permite criar, listar e atualizar alunos, registrar aulas realizadas e consultar o progresso dos alunos.

## Tecnologias Utilizadas
- Flet
- Requests

### Interface
![Image](https://github.com/user-attachments/assets/28550f4f-7e0b-4f06-a4a6-34f52d53fb72)

## Funcionalidades
- **Criar Aluno**: Envia os dados do formulário para a API por uma requisição POST.
- **Listar Alunos**: Retorna os dados de aluno cadastrados e os lista.
- **Aula Realizada**: Registra a quantidade de aulas realizadas por um aluno.
- **Progresso do Aluno**: Consulta a quantidade de aulas realizadas e as necessárias para avançar de nível de faixa.
- **Atualizar Aluno**: Permite alterar as informações de um aluno.

### Passos para rodar o projeto
1. Clone o repositório:
   ```sh
   git clone --branch projeto_4 --single-branch https://github.com/lucaslpdacosta/4d4p.git
   ```
2. Instale as dependências:
   ```sh
   pip install flet requests
   ```
3. Execute o aplicativo:
   ```sh
   python app.py
   ```
