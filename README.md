# RottenPotatoes

Aplicacao desenvolvida em Rails 8 para gerenciamento do catalogo RottenPotatoes.

---

## Pré-requisitos

* **Ruby:** 3.3.6
* **Rails:** 8.1.3.1
* **SQLite:** 3

---

## Como Executar o Projeto Localmente

Siga os passos abaixo no terminal a partir da raiz do projeto:

### 1. Instalar as dependências
Instale as gems do projeto através do Bundler:
```bash
bundle install
```

### 2. Preparar o banco de dados
Execute as migrações para criar as tabelas e popule o banco com os dados iniciais de filmes:
```bash
bin/rails db:prepare
bin/rails db:seed
```

### 3. Executar os testes
Verifique a integridade da aplicação executando a suíte de testes e o linter de código:
```bash
bin/rails test
bin/rubocop
```

### 4. Iniciar o servidor
Inicie o servidor de desenvolvimento Puma:
```bash
bin/rails server
```
Acesse a aplicação no seu navegador em: `http://localhost:3000/movies`
