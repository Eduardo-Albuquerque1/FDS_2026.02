# Fórum FDS 2026.2

Aplicação web de fórum de programação, desenvolvida em Django para a disciplina de Fundamentos de Desenvolvimento de Software (FDS).

## Funcionalidades

- Criação de perguntas
- Criação de respostas às perguntas

## Tecnologias

- Python
- Django
- PostgreSQL (produção) / SQLite (desenvolvimento)
- Gunicorn + Whitenoise (deploy)

## Rodando localmente

1. Clone o repositório
2. Crie e ative um ambiente virtual:

python -m venv .venv
.venv\Scripts\Activate.ps1

3. Instale as dependências:

pip install -r requirements.txt

4. Crie um arquivo `.env` na raiz do projeto com:

ENVIRONMENT=development
SECRET_KEY=sua-chave-aqui

5. Rode as migrações e o servidor:

python manage.py migrate
python manage.py runserver


## Deploy

Aplicação hospedada no [Render](https://render.com).

🔗 Acesse: https://fds-2026-02.onrender.com/forum/

## Autor

Eduardo Albuquerque
