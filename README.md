```
╔══════════════════════════════════════════════════════╗
║  Abel Pozza · Backend Engineer                       ║
║  Kotlin · Spring Boot · REST APIs · PostgreSQL       ║
╚══════════════════════════════════════════════════════╝
```

## Sobre

Desenvolvedor backend focado em **Kotlin e Spring Boot**, atuando na construção de APIs REST com arquitetura em camadas (Controller → Service → Repository), integração com banco de dados relacional e processamento de eventos em tempo real.

Meu background como suporte N2 me deu uma visão direta de sistemas em produção: sei diagnosticar problemas reais, entender regras de negócio complexas e construir soluções que de fato funcionam sob pressão.

Também desenvolvo apps **Android com Jetpack Compose**, integrados às minhas próprias APIs.

---

## Stack

```kotlin
val stack = mapOf(
    "backend"   to listOf("Kotlin", "Spring Boot", "REST API", "JPA/Hibernate"),
    "database"  to listOf("PostgreSQL", "SQL", "Firebird"),
    "mobile"    to listOf("Android", "Jetpack Compose", "Navigation Compose", "Firebase"),
    "infra"     to listOf("Docker", "Git", "Postman", "Webhook")
)
```

---

## Projetos

### `parking-api` — Gerenciamento de Estacionamento (Backend)
> API REST para controle operacional de estacionamento em tempo real

Controle de vagas, entrada/saída de veículos e cálculo de faturamento com processamento via Webhook. Regras de negócio aplicadas na camada de serviço com consistência garantida pelo PostgreSQL.

**Stack:** Kotlin · Spring Boot · PostgreSQL · JPA/Hibernate · Docker · Postman  
🔗 [github.com/Abelpozza/parking-api](https://github.com/Abelpozza/parking-api)

---

### `flowfood-api` — Sistema de Delivery (Backend)
> API RESTful de delivery com state machine e regras de negócio reais

Gerenciamento completo de restaurantes, produtos e pedidos. Destaque para a state machine de status de pedido — transições inválidas são bloqueadas automaticamente (`CREATED → CONFIRMED → DELIVERED`, com cancelamento restrito a estados permitidos). Cálculo automático do valor total e validação de existência de entidades antes de persistir pedidos.

**Stack:** Kotlin · Spring Boot · PostgreSQL · Spring Data JPA · Hibernate · Jakarta Validation  
🔗 [github.com/Abelpozza/flowfood-api](https://github.com/Abelpozza/flowfood-api)

---

### `interfaceEstacionamento` — Dashboard Integrado
> Frontend conectado ao backend de estacionamento

Interface em tempo real para visualização de ocupação, histórico de veículos e faturamento, integrada diretamente via API e sincronizada com o PostgreSQL.

🔗 [github.com/Abelpozza/interfaceEstacionamento](https://github.com/Abelpozza/interfaceEstacionamento)

---

### `AuthFlow Android` — Autenticação com Firebase + Compose
> App Android com fluxo completo de autenticação

Login, cadastro, navegação entre telas e validação de formulários usando Jetpack Compose e Firebase Authentication + Firestore.

**Stack:** Kotlin · Jetpack Compose · Navigation Compose · Firebase  
🔗 [github.com/Abelpozza/AnotherTest](https://github.com/Abelpozza/AnotherTest)

---

### `ComposeNavigator` — UI e Navegação no Android
> Estudo aplicado de arquitetura de UI declarativa

Componentes reutilizáveis, navegação entre telas e boas práticas de UI com Jetpack Compose.

🔗 [github.com/Abelpozza/JETPACK-Project](https://github.com/Abelpozza/JETPACK-Project)

---

## O que me diferencia

- **Background em suporte N2** → entendo sistemas em produção, não só ambientes de desenvolvimento
- **Foco em backend com propósito** → código orientado a regras de negócio reais, não só CRUD
- **IA como ferramenta, não muleta** → uso ChatGPT, Claude e GitHub Copilot para acelerar, mas valido criticamente cada solução
- **Backend + Mobile** → consigo construir a API e o app que a consome

---

## Contato

📧 abelfloripa2000@gmail.com  
💼 [linkedin.com/in/devabelpozza](https://www.linkedin.com/in/devabelpozza/)  
📍 Florianópolis, SC

---

*Focado em evoluir como engenheiro backend e construir soluções que funcionam em produção.*
