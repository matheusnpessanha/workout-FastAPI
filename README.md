# 🏋️‍♂️ Workout API - FastAPI + SQLAlchemy

Este é um projeto prático desenvolvido como parte do desafio da [Digital Innovation One (DIO)](https://www.dio.me/), com foco em construção de APIs modernas utilizando **FastAPI**, **SQLAlchemy**, **Pydantic** e boas práticas de desenvolvimento backend em Python.

> 🚀 O objetivo foi aprimorar conhecimentos em criação de rotas, manipulação de exceções, paginação, respostas customizadas e uso de query parameters com FastAPI.

---

## 📌 Funcionalidades implementadas

- ✅ Endpoints com filtros via query parameters (`nome`, `cpf`, etc.)
- ✅ Respostas customizadas nos `GET`
- ✅ Manipulação de exceções com mensagens claras e códigos de status apropriados
- ✅ Paginação com `limit` e `offset` usando a lib `fastapi-pagination`
- ✅ Organização modular por domínio (Atletas, Categorias, Centros de Treinamento)
- ✅ Separação clara entre modelos, controladores e schemas

---

## 🗃️ Tecnologias e Bibliotecas

- [FastAPI](https://fastapi.tiangolo.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Uvicorn](https://www.uvicorn.org/)
- [Pydantic](https://docs.pydantic.dev/)
- [fastapi-pagination](https://github.com/uriyyo/fastapi-pagination)
- SQLite (ou outro banco de sua escolha)

---

## 📥 Instalação e Execução

### 1. Clone o repositório

git clone https://github.com/seu-usuario/workout_api.git
cd workout_api

### 2. Crie um ambiente virtual

python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate

### 3. Instale as dependências

pip install -r requirements.txt

🧠 Autor
Matheus Pessanha
Recife/PE 🇧🇷
LinkedIn • GitHub
### 4. Execute a aplicação

uvicorn workout_api.main:app --reload


