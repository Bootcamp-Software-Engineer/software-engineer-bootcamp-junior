# 🚀 Bootcamp Software Engineer Júnior: Da Ideia ao Deploy

Repositório oficial do **Bootcamp Software Engineer Júnior**, promovido pela **Vanguard Tech** em parceria com a **Selde Company**.

---

## 📌 Sobre o Bootcamp

Este evento foi desenhado para eliminar a distância entre a teoria académica e as exigências reais do mercado de trabalho de TI. Durante 1 semana (10 horas de prática), construímos do zero uma API REST moderna em TypeScript, aplicando boas práticas de arquitetura, persistência de dados, segurança e deploy na nuvem.

* **📅 Data:** 23 a 27 de Novembro de 2026
* **⏰ Horário:** 18h30 – 20h30 (WAT)
* **👨‍💻 Formador:** Benilson Salvador (*Solution Architect & Business Developer - Vanguard Tech*)
* **🌐 Website:** [vanguardit.ao](https://vanguardit.ao)

---

## 🛠️ Tech Stack & Ferramentas

* **Linguagem & Runtime:** Node.js, TypeScript
* **Framework Web:** Express
* **Base de Dados & ORM:** PostgreSQL / SQLite, Prisma ORM
* **Segurança:** JSON Web Tokens (JWT), Bcrypt
* **DevOps & Infrastructure:** Docker, Docker Compose
* **Deploy:** Cloud Platform (Render / Railway)

---

## 📅 Estrutura do Conteúdo

| Dia | Tópico Principal | Ramo (Branch) |
| :--- | :--- | :--- |
| **Dia 1** | A Mente do Software Engineer & Setup Profissional (Git, Clean Architecture) | `dia-01` |
| **Dia 2** | Modelação e Construção da API REST (Rotas, Controllers, Validações) | `dia-02` |
| **Dia 3** | Persistência de Dados & Modelação Relacional (ORM, Migrações, CRUD) | `dia-03` |
| **Dia 4** | Segurança, Autenticação e DevSecOps (JWT, OWASP, Env Vars) | `dia-04` |
| **Dia 5** | Containerização com Docker, Deploy na Nuvem & Gestão de Carreira | `dia-05` |

---

## ⚙️ Pré-requisitos para Executar o Projeto

Antes de começar, garante que tens instalado na tua máquina:
* [Node.js](https://nodejs.org/) (v18+)
* [Git](https://git-scm.com/)
* [Docker Desktop](https://www.docker.com/) (Opcional para os dias 1-3, necessário para os dias 4-5)
* Um editor de código (recomendado: [VS Code](https://code.visualstudio.com/))

---

## 🚀 Como Executar Localmente

```bash
# 1. Clonar o repositório
git clone [https://github.com/vanguardit/vanguard-bootcamp-backend.git](https://github.com/vanguardit/vanguard-bootcamp-backend.git)

# 2. Entrar na pasta do projeto
cd vanguard-bootcamp-backend

# 3. Instalar as dependências
npm install

# 4. Configurar as variáveis de ambiente (criar o ficheiro .env com base no .env.example)
cp .env.example .env

# 5. Executar as migrações da base de dados
npx prisma migrate dev

# 6. Iniciar o servidor de desenvolvimento
npm run dev
