# Projeto FastHTML com Python

Este projeto demonstra como utilizar o **FastHTML**, um framework minimalista de templating para Python, para criar um site simples e uma lista de tarefas. O projeto também faz uso de um ambiente virtual `venv` para gerenciamento das dependências de desenvolvimento.

## Tecnologias Utilizadas

- **Python 3.10+**
- **FastHTML** (um framework minimalista de templating)
- **Venv** (para gerenciamento de dependências)

## Estrutura do Projeto

```
.
├── README.md
├── __pycache__
│   ├── aplicativo.cpython-310.pyc
│   ├── componentes.cpython-310.pyc
│   └── main.cpython-310.pyc
├── aplicativo.py
├── componentes.py
├── main.py
├── requirements_dev_fastHtml.txt
├── requirements_init.txt
└── tree.txt

1 directory, 10 files
```

### Arquivos principais:

- **main.py**: Define uma rota simples para a página inicial usando o FastHTML.
- **aplicativo.py**: Implementa a lógica de uma lista de tarefas e um blog fictício, com rotas para adicionar e deletar tarefas.
- **componentes.py**: Contém funções utilitárias para gerar componentes HTML como formulários e listas de tarefas dinâmicas.
- **requirements_dev_fastHtml.txt**: Lista de dependências para o ambiente de desenvolvimento.

## Instalação

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/usuario/repositorio.git
   cd repositorio
   ```

2. Crie o ambiente virtual:

```
python -m venv venv
```

3. Ative o ambiente virtual:

```
venv\Scripts\activate
```

4. Instale as dependências:

```
pip install -r requirements_dev_fastHtml.txt
```

## Passos para Linux e macOS

1. Clone o repositório:

```
git clone https://github.com/usuario/repositorio.git
cd repositorio
```

2. Crie o ambiente virtual:

```
python3 -m venv venv
```

3. Ative o ambiente virtual:

- No Linux:

```
source venv/bin/activate
```

- No MacOs:

```
source venv/bin/activate
```

4. Instale as dependências:

```
pip install -r requirements_dev_fastHtml.txt
```

## Uso

### Executando o main.py

### Este arquivo define uma rota básica para a página inicial.

```
python main.py
```

Acesse no navegador: http://localhost:8000

### Executando o aplicativo.py

### Este arquivo contém a lógica da lista de tarefas, com suporte para adicionar e excluir tarefas dinamicamente.

```
python aplicativo.py
```

Acesse no navegador: http://localhost:8000

### Adicionando uma Tarefa

1. Preencha o formulário na página inicial com uma tarefa.
2. A tarefa será adicionada à lista de tarefas exibida na página.

### Excluindo uma Tarefa

1. Clique no link "Excluir" ao lado da tarefa que deseja remover.
2. A lista será atualizada automaticamente para refletir a remoção da tarefa.

### Visualizando da Página

Acesse http://localhost:8000/blog para ver a página do blog.

# Dependências

### As dependências são listadas no arquivo requirements_dev_fastHtml.txt. Aqui estão algumas das principais bibliotecas:

- python-fasthtml: Utilizado para criação de páginas HTML dinâmicas.
- uvicorn: Servidor ASGI para rodar a aplicação web.
- httpx: Cliente HTTP para interações baseadas em HTTP.
- starlette: Framework de web para manipulação de rotas e requisições.

# Contribuindo

1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature (git checkout -b minha-feature).
3. Faça um commit das suas mudanças (git commit -m 'Adiciona minha feature').
4. Faça um push para a branch (git push origin minha-feature).
5. Crie um Pull Request.

Licença
Este projeto está sob a licença MIT.
