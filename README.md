# CRUD Front-end com Angular e LocalStorage

Este projeto consiste em um **CRUD desenvolvido no front-end utilizando o framework Angular**, com persistência de dados feita através do **LocalStorage do navegador**. O sistema também consome uma **API pública gratuita** para carregamento dinâmico de **estados e cidades** na tela de cadastro.

O objetivo do projeto é **praticar Angular**, organização de componentes, serviços, rotas e integração com APIs externas, sem dependência de back-end próprio.

---

## 🚀 Tecnologias Utilizadas

* **Angular**
* **TypeScript**
* **HTML5**
* **SCSS**
* **LocalStorage (Web Storage API)**
* **API pública de Estados e Cidades (BrasilAPI)**

---

## 📂 Estrutura do Projeto

```bash
src/
 ├── app/
 │   ├── cadastro/
 │   │   ├── cadastro.html
 │   │   ├── cadastro.scss
 │   │   └── cadastro.ts
 │   │
 │   ├── consulta/
 │   │   ├── consulta.html
 │   │   ├── consulta.scss
 │   │   └── consulta.ts
 │   │
 │   ├── services/
 │   │   └── cliente.service.ts
 │   │
 │   ├── models/
 │   │   └── brasilapi.models.ts
 │   │
 │   ├── app.routes.ts
 │   ├── app.config.ts
 │   └── app.ts
 │
 ├── index.html
 ├── main.ts
 └── styles.scss
```

---

## 📌 Funcionalidades

* Cadastro de clientes
* Listagem (consulta) de registros cadastrados
* Edição de registros
* Exclusão de registros
* Persistência de dados usando **LocalStorage**
* Consumo de **API pública** para:

  * Listagem de estados
  * Listagem de cidades conforme o estado selecionado

---

## 🌐 API Externa Utilizada

Foi utilizada a **BrasilAPI**, uma API pública e gratuita, para obtenção de estados e cidades.

Funcionalidades consumidas:

* Listar estados brasileiros
* Listar cidades a partir do estado selecionado

---

## 💾 LocalStorage

Os dados cadastrados são armazenados diretamente no navegador do usuário, utilizando o **LocalStorage**. Dessa forma:

* Não é necessário back-end
* Os dados permanecem salvos mesmo após recarregar a página
* Os dados são específicos do navegador utilizado

---

## ⚙️ Instalação e Execução

### 1️⃣ Clonar o repositório

```bash
git clone <url-do-repositorio>
cd crud-angular
```

### 2️⃣ Instalar as dependências

```bash
npm install
```

### 3️⃣ Executar o projeto

```bash
ng serve
```

A aplicação estará disponível em:

```
http://localhost:4200
```

---

## 🧪 Testes

```bash
ng test
```

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

* Aprendizado do **Angular**
* Criação de CRUD no front-end
* Uso do **LocalStorage** para persistência de dados
* Consumo de APIs REST públicas
* Organização de código e boas práticas

---

## ✍️ Autor

**Jonas Kelvin**

Projeto desenvolvido para fins de estudo e prática em desenvolvimento front-end 🚀
****
