```
╔══════════════════════════════════════════════════════╗
║  Abel Pozza · Backend Developer                      ║
║  Kotlin · Spring Boot · REST APIs · PostgreSQL       ║
╚══════════════════════════════════════════════════════╝
```

## Sobre

Desenvolvedor backend focado em **Kotlin/Java**, atuando na construção de APIs REST com arquitetura em camadas (Controller → Service → Repository), integração com banco de dados relacional e processamento de eventos em tempo real.

Meu background como suporte N2 me deu uma visão direta de sistemas em produção: sei diagnosticar problemas reais, entender regras de negócio complexas e construir soluções que de fato funcionam sob pressão.

Também desenvolvo apps **Android com Jetpack Compose**, integrados às minhas próprias APIs.

---

## Stack

| Categoria | Tecnologias |
|-----------|------------|
| 💻 Backend | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![REST API](https://img.shields.io/badge/REST%20API-000000?style=flat-square) |
| 🗄️ Banco de Dados | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square) ![Firebird](https://img.shields.io/badge/Firebird-FF6C37?style=flat-square) |
| 📱 Mobile | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=android&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| ⚙️ Infra | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

---

## Projetos

### `parking-api` — Gerenciamento de Estacionamento (Backend)
> API REST para controle operacional de estacionamento em tempo real

Não é um CRUD de vagas. O sistema processa eventos de entrada e saída via Webhook, recalcula ocupação em tempo real e aplica regras de faturamento isoladas na camada de serviço — sem lógica vazando pra controller. Quem chama a API recebe o estado atual do estacionamento sempre consistente, garantido pelo PostgreSQL com JPA/Hibernate. Containerizado com Docker e validado com coleções Postman organizadas por fluxo de negócio.

**Stack:** Kotlin · Spring Boot · PostgreSQL · JPA/Hibernate · Docker · Postman  
🔗 [github.com/Abelpozza/parking-api](https://github.com/Abelpozza/parking-api)

---

### `flowfood-api` — Sistema de Delivery (Backend)
> API RESTful de delivery com state machine e regras de negócio reais

O ponto central não é o CRUD de restaurantes — é o controle de fluxo de pedidos. Implementei uma state machine que bloqueia transições inválidas direto na camada de serviço: `CREATED → CONFIRMED → DELIVERED`, com cancelamento permitido apenas nos estados corretos. Qualquer tentativa fora do fluxo retorna erro antes de tocar no banco. Contrato externo separado por DTOs, validação de dados com Jakarta Validation e tratamento global de exceções com respostas padronizadas em toda a API.

**Stack:** Kotlin · Spring Boot · PostgreSQL · Spring Data JPA · Hibernate · Jakarta Validation  
🔗 [github.com/Abelpozza/flowfood-api](https://github.com/Abelpozza/flowfood-api)

---

### `interfaceEstacionamento` — Dashboard Integrado
> Frontend conectado ao backend de estacionamento

Interface construída sobre a própria `parking-api`, consumindo os endpoints em tempo real para exibir ocupação de vagas, histórico de veículos e faturamento atualizado. Demonstra que consigo fechar o ciclo: projeto o backend e conecto o cliente que o consome.

🔗 [github.com/Abelpozza/interfaceEstacionamento](https://github.com/Abelpozza/interfaceEstacionamento)

---

### `AuthFlow Android` — Autenticação com Firebase + Compose
> App Android com fluxo completo de autenticação

Fluxo de login e cadastro com Firebase Authentication, persistência de usuário no Firestore e navegação entre telas com Navigation Compose. Formulários com validação de estado em tempo real — erro aparece no campo certo, no momento certo, sem travar a UI. Toda a interface construída de forma declarativa com Jetpack Compose.

**Stack:** Kotlin · Jetpack Compose · Navigation Compose · Firebase Auth · Firestore  
🔗 [github.com/Abelpozza/AnotherTest](https://github.com/Abelpozza/AnotherTest)

---

### `ComposeNavigator` — UI e Navegação no Android
> Estudo aplicado de arquitetura de UI declarativa

Exploração prática de composição de telas, navegação entre destinos e construção de componentes reutilizáveis com Jetpack Compose. Base técnica que sustenta os projetos Android mais complexos.

🔗 [github.com/Abelpozza/JETPACK-Project](https://github.com/Abelpozza/JETPACK-Project)

---

## O que me diferencia

- **Background em suporte N2** → já vi sistema quebrar em produção às 23h. Sei o que é urgência real e o que acontece quando uma regra de negócio está errada
- **Não escrevo só CRUD** → state machine, processamento de eventos, regras de negócio isoladas na camada certa — é o que aparece nos meus projetos
- **Backend + Mobile** → projeto a API e construo o app que a consome. Entendo os dois lados do contrato
- **IA como alavanca, não resposta** → uso ferramentas como Claude e Copilot pra acelerar, mas cada decisão técnica passa pelo meu entendimento antes de ir pro código

---

## Contato

📧 abelfloripa2000@gmail.com  
💼 [linkedin.com/in/devabelpozza](https://www.linkedin.com/in/devabelpozza/)  
📍 Florianópolis, SC

---

*Focado em evoluir como desenvolvedor backend e construir soluções que funcionam em produção.*
