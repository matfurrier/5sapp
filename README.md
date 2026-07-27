# 5S Quality Audits & Action Plans

🔗 **Languages:**  
- [Português 🇧🇷](#português)  
- [English 🇺🇸](#english)

- 📐 Diagramas: [Arquitetura e Fluxos](docs/diagrams/ARCHITECTURE_5S_Quality.md)

---

<img width="949" height="846" alt="%s" src="https://github.com/user-attachments/assets/93aa7205-7c0c-403a-ac41-f139abb056ac" />
<img width="951" height="775" alt="5s" src="https://github.com/user-attachments/assets/238f0ece-e175-4a2c-9457-f36a4329481c" />
<img width="975" height="806" alt="5s" src="https://github.com/user-attachments/assets/477dac0b-9f24-4ca8-9bd4-522bc6ce3628" />
<img width="1343" height="837" alt="5s" src="https://github.com/user-attachments/assets/7d4f7e14-3705-4756-9bc3-25c230ae199a" />

## Português

### Visão Geral

Aplicação web corporativa para **gestão de auditorias 5S**, **não conformidades** e **planos de ação**, utilizada pela área de Qualidade de uma multinacional francesa do agronegócio (subsidiária brasileira).

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
- Gestão de não conformidades com evidência fotográfica  
- Planos de ação com responsáveis, prazos e fotos de resolução  
- Fluxo mobile dedicado  
- Dashboards gerenciais com indicadores por período, setor e área  
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
[ app data ] [ auth/security ]  

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

Corporate web application for **5S audits**, **non-conformities**, and **action plan management**, used by the Quality department of a French agribusiness multinational (Brazilian subsidiary).

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
- Non-conformity tracking with photo evidence  
- Action plan management with owners, deadlines and resolution photos  
- Dedicated mobile audit flow  
- Management dashboards with indicators by period, sector and area  
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
