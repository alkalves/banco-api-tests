# 🧪 Banco API Tests

## 📘 Descrição do Projeto
O **Banco API Tests** é um projeto de **automação de testes de API REST**, desenvolvido em **JavaScript**, com o objetivo de validar as funcionalidades da API do projeto [Banco API](https://github.com/juliodelimas/banco-api).  
O foco é garantir a integridade dos endpoints disponibilizados, por meio de testes automatizados.

---

## 🧰 Stack Utilizada
O projeto utiliza as seguintes tecnologias e bibliotecas:

- **Node.js** — ambiente de execução JavaScript.  
- **Mocha** — framework de testes.  
- **Chai** — biblioteca de asserções.  
- **Supertest** — biblioteca para requisições HTTP em testes.  
- **Mochawesome** — gerador de relatórios HTML e JSON para testes Mocha.  
- **Dotenv** — para gerenciamento de variáveis de ambiente.

---

## 📂 Estrutura de Diretórios
A estrutura do projeto segue o formato abaixo:

```
banco-api-tests/
├── test/
│   ├── login.test.js     
│   ├── transferencias.test.js    
├── mochawesome-report/       # Diretório onde os relatórios HTML são gerados
├── .env                      # Arquivo de configuração de variáveis de ambiente (não versionado)
├── .gitignore
├── package.json              # Dependências e scripts do projeto
├── package-lock.json
└── README.md
```

---

## ⚙️ Configuração do Ambiente

### 1️⃣ Pré-requisitos
- [Node.js](https://nodejs.org/en/) (versão 16 ou superior)
- [npm](https://www.npmjs.com/) instalado

### 2️⃣ Instalação das Dependências
```bash
npm install
```

### 3️⃣ Configuração do arquivo `.env`
Crie um arquivo `.env` na raiz do projeto com o seguinte formato:

```env
BASE_URL=http://localhost:3000
```

> A variável `BASE_URL` deve apontar para o endereço onde a **Banco API** está sendo executada.

---

## 🚀 Execução dos Testes

### Rodar todos os testes
```bash
npm test
```

### Gerar relatório Mochawesome
Durante a execução, o **Mochawesome** automaticamente cria um relatório no diretório:
```
mochawesome-report/mochawesome.html
```

Para abrir o relatório:
- Localize o arquivo `mochawesome.html`
- Abra-o em seu navegador preferido.

---

## 📄 Links Úteis (Documentações)

| Biblioteca / Tecnologia | Link |
|--------------------------|------|
| **Mocha** | [https://mochajs.org/](https://mochajs.org/) |
| **Chai** | [https://www.chaijs.com/](https://www.chaijs.com/) |
| **Supertest** | [https://github.com/visionmedia/supertest](https://github.com/visionmedia/supertest) |
| **Mochawesome** | [https://github.com/adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) |
| **Dotenv** | [https://github.com/motdotla/dotenv](https://github.com/motdotla/dotenv) |
| **Node.js** | [https://nodejs.org/](https://nodejs.org/) |

---

## 👩‍💻 Autora
Desenvolvido por **Ana Luiza**  
📎 Projeto de testes para [Banco API](https://github.com/juliodelimas/banco-api)
