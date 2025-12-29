# 5S De Sangosse – Quality Audits & Action Plans

🔗 **Languages:**  
- [Português 🇧🇷](#português)  
- [English 🇺🇸](#english)

---

## Português

### Visão Geral

Aplicação web corporativa para **gestão de auditorias 5S**, **não conformidades** e **planos de ação**, utilizada pela área de Qualidade da **De Sangosse**.

📌 **Status:** validação final / rollout  
📌 **Tipo:** sistema corporativo interno  
📌 **Código-fonte:** privado (repositório público apenas para documentação)

---

### Problema

- Auditorias 5S realizadas em papel ou planilhas  
- Dificuldade de consolidação de indicadores  
- Não conformidades sem rastreabilidade  
- Planos de ação sem acompanhamento estruturado  
- Baixa visibilidade gerencial  
- Uso mobile inexistente ou improvisado  

---

### Solução

- Planejamento e execução de auditorias 5S  
- Registro de respostas por pergunta e senso  
- Cálculo automático de scores  
- Gestão de não conformidades  
- Planos de ação com responsáveis e prazos  
- Fluxo mobile dedicado  
- Dashboards gerenciais  
- Controle de acesso por perfil  
- Integração com banco corporativo de usuários  

---

### Arquitetura (alto nível)

[ Next.js Web / Mobile ]  
    |  
    v  
[ FastAPI REST API ]  
    |  
 -------------------  
 |        |  
[ PostgreSQL ] [ PostgreSQL ]  
[ quality5s ] [ security ]  

---

### Stack Tecnológico

**Backend**
- Python 3.11
- FastAPI
- SQLAlchemy (async)
- Pydantic
- PostgreSQL
- JWT
- Docker

**Frontend / Mobile**
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- Radix UI / shadcn-like
- Recharts

**Infraestrutura**
- Docker
- Docker Compose
- Deploy containerizado

---

### Papel de Liderança Técnica

- Arquitetura da solução  
- Modelagem de dados  
- Definição de fluxos de negócio  
- Segurança e autenticação  
- Governança e controle de acesso  
- Deploy e containerização  
- Entrega end-to-end  

---

## English

### Overview

Corporate web application for **5S audits**, **non-conformities**, and **action plan management**, used by the Quality department at **De Sangosse**.

📌 **Status:** final validation / rollout  
📌 **Type:** internal corporate system  
📌 **Source code:** private (public repository for documentation only)

---

### Problem

- 5S audits executed on paper or spreadsheets  
- Difficult KPI consolidation  
- Non-conformities without traceability  
- Action plans without structured follow-up  
- Low management visibility  
- No proper mobile workflow  

---

### Solution

- Planning and execution of 5S audits  
- Answer recording per question and sense  
- Automatic score calculation  
- Non-conformity tracking  
- Action plan management with owners and deadlines  
- Dedicated mobile audit flow  
- Management dashboards  
- Role-based access control  
- Integration with corporate user database  

---

### Technology Stack

**Backend**
- Python 3.11
- FastAPI
- SQLAlchemy (async)
- Pydantic
- PostgreSQL
- JWT
- Docker

**Frontend / Mobile**
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- Radix UI / shadcn-like
- Recharts

**Infrastructure**
- Docker
- Docker Compose
- Containerized deployment

---

### Notes

- Source code is private due to corporate ownership  
- This repository exists for technical documentation and professional presentation only  
