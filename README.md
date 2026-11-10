# TaskFlow — Gerenciador de Tarefas em Python

Aplicação de terminal para organização de tarefas, desenvolvida como projeto de portfólio para praticar fundamentos de programação e conceitos de Engenharia de Software.

## Funcionalidades

- Criar tarefas com título e descrição
- Listar tarefas cadastradas
- Marcar tarefas como concluídas
- Excluir tarefas
- Persistir dados localmente em arquivo JSON
- Validar entradas e tratar erros comuns

## Tecnologias e conceitos

- **Python 3.10+**
- Programação Orientada a Objetos (POO)
- Operações CRUD
- JSON e manipulação de arquivos
- Tratamento de exceções
- Testes automatizados com `unittest`

## Estrutura do projeto

```text
taskflow-python/
├── src/
│   ├── main.py
│   └── gerenciador.py
├── data/
├── tests/
│   └── test_gerenciador.py
├── .gitignore
├── requirements.txt
└── README.md
```

## Como executar

1. Instale o [Python 3.10 ou superior](https://www.python.org/downloads/).
2. Clone o repositório:

   ```bash
   git clone https://github.com/SEU-USUARIO/taskflow-python.git
   cd taskflow-python
   ```

3. Execute a aplicação:

   ```bash
   python src/main.py
   ```

O arquivo `data/tarefas.json` será criado automaticamente após o primeiro cadastro. Os dados ficam armazenados localmente.

## Como executar os testes

Na raiz do projeto, execute:

```bash
python -m unittest discover -s tests -v
```

Os testes cobrem criação, validação, persistência, conclusão e exclusão de tarefas.

## Próximas melhorias

- [ ] Editar tarefas já cadastradas
- [ ] Adicionar prioridade e prazo
- [ ] Filtrar tarefas pendentes e concluídas
- [ ] Criar interface web com Flask ou FastAPI
- [ ] Migrar a persistência de JSON para SQLite
- [ ] Adicionar integração contínua (GitHub Actions)

## Objetivo educacional

Este projeto foi criado para consolidar conhecimentos de Python e demonstrar evolução prática em desenvolvimento de software. As funcionalidades e melhorias serão implementadas de forma incremental.

## Licença

Distribuído sob a licença MIT. Consulte o arquivo `LICENSE`.
