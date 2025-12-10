# To-Do List com Python, Flask e Redis  

Um projeto simples e funcional de **lista de tarefas (To-Do List)** desenvolvido com **Python + Flask** e **Redis** como banco de dados em memória.  
O objetivo é demonstrar como criar um **CRUD completo** (Create, Read, Update, Delete) usando tecnologias leves e rápidas.


## Funcionalidades

- ➕ **Adicionar tarefas** com título e descrição  
- 🔍 **Buscar tarefas** (todas ou por ID específico)  
- ✏️ **Editar tarefas** e atualizar status  
- ❌ **Excluir tarefas** individualmente  
- 🕒 **Registrar data de criação automaticamente**  
- 🧠 **IDs automáticos** gerados via Redis  
- 💾 **Armazenamento rápido** com Redis  


## 🧰 Tecnologias utilizadas
<div align="left">
<img alt="python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>&nbsp;
<img alt="redis" src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>&nbsp;
<img alt="redis" src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white"/>&nbsp;
<img alt="redis" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>&nbsp;
</div>

##
![Pagina](img.png) 

| Rota | Método | Descrição |
|------|--------|-----------|
| /buscar | GET | Retorna todos |
| /enviar | POST | Cria um novo |
| /editar | GET | Busca os dados para serem editados |
| /editarDados | POST | Edita o dado selecionado |
| /excluir | GET | Exclui um |
| /buscarId | POST | Retorna um |
