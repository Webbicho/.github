# Webbicho Organization

Bem-vindo à organização do **Webbicho**! 🐾  
Esta organização centraliza todos os repositórios e microsserviços que compõem a plataforma Webbicho, uma solução
digital pensada para facilitar o dia a dia das ONGs de proteção animal.

---

## 🌱 Propósito

O **Webbicho** é uma plataforma modular, multi-ONG e escalável, voltada para:

- Gerenciar perfis de ONGs e seus animais
- Facilitar adoções e doações
- Conectar protetores, voluntários e adotantes
- Promover a visibilidade de animais abandonados

---

## 🧱 Estrutura da Organização

A arquitetura do projeto segue o modelo de microsserviços desacoplados, organizados por domínio funcional. Cada
repositório possui seu próprio ciclo de vida e documentação específica.

### Microsserviços principais

| Nome         | Descrição                                | Stack           |
|--------------|:-----------------------------------------|-----------------|
| `wb-server`  | Core da aplicação (ONGs, pets, usuários) | Spring + Kotlin |
| `wba-server` | Administração (ONGs, pets, usuários)     | Spring + Kotlin |

---

## 🧩 Tecnologias

- **Back-end:** Spring Boot (Kotlin)
- **Front-end:** Nuxt 3 (Vue 3 + Tailwind)
- **Banco de dados:** PostgreSQL
- **Infraestrutura:** Docker, GitHub Actions, NGINX

---

## 🔐 Conformidade e Segurança

- Todas as entidades utilizam **UUID** como chave primária
- Gerenciamento de migrations com **Liquibase**
- Múltiplos schemas no PostgreSQL (multi-ONG, não tenants clássicos)

---

## 📦 Padrões

- **Branch naming:** `feature/*`, `fix/*`, `hotfix/*`
- **Commits:** [Conventional Commits](https://www.conventionalcommits.org/)

---

## 🧠 Contribuindo

1. Leia o `README.md` do repositório em que vai atuar
2. Crie uma issue no Jira com **Title**, **Description** e **Goal** (em inglês)
3. Crie uma branch a partir da `main`
4. Abra um Pull Request e descreva claramente sua implementação
5. Marque a tarefa como **Review** no Jira

---

## 🛣️ Roadmap

- [ ] Lançamento beta para ONGs parceiras
- [ ] Implementação de analytics no painel das ONGs
- [ ] Integração com gateways de pagamento nacionais

---

## 🧑‍💻 Contato

Quer colaborar ou tem sugestões?  
Abra uma issue ou mande um e-mail: **admin@webbicho.org.br**

---

> Feito com carinho para ajudar quem ajuda. 🐶🐱💚
