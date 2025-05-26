# Magui Web & API – Sistema de Gestão para Confecções

**Magui** é uma solução voltada para gestão de confecções, composta por uma API REST robusta e uma aplicação web moderna. O sistema oferece funcionalidades para gerenciamento de pedidos, produtos, clientes e ordens de produção, com foco em eficiência, usabilidade e adaptação ao setor têxtil.

---

## Sumário
- [Magui Web \& API – Sistema de Gestão para Confecções](#magui-web--api--sistema-de-gestão-para-confecções)
  - [Sumário](#sumário)
  - [Sobre o Projeto](#sobre-o-projeto)
  - [Arquitetura e Tecnologias](#arquitetura-e-tecnologias)
    - [Frontend](#frontend)
    - [Backend](#backend)
    - [Infraestrutura](#infraestrutura)
  - [Funcionalidades Principais](#funcionalidades-principais)
  - [Recursos Técnicos](#recursos-técnicos)


---

## Sobre o Projeto

O Magui foi desenvolvido para atender as necessidades de confecções de uma empresa familiar, facilitando o controle de pedidos, estoque, clientes e produção. O sistema é intuitivo e pensado para o dia a dia do setor.

---

## Arquitetura e Tecnologias

### Frontend
- **React** + **TypeScript** (Vite)
- **Tailwind CSS** e **Shadcn/ui**
- **React Router**, **React Hook Form**, **Zod**, **date-fns**, **jsPDF**

### Backend
- **FastAPI** (Python 3.8+)
- **PostgreSQL** (banco relacional)
- **SQLAlchemy**, **Pydantic**

### Infraestrutura
- **Docker** 
- **Git** (controle de versão)
- **Firewall** (segurança de rede)

---

## Funcionalidades Principais

- **Gestão de Pedidos:** Cadastro, filtros, atualização de status, histórico
- **Gestão de Produtos:** Cadastro, estoque, categorização, preços
- **Gestão de Clientes:** Cadastro, histórico, contatos, documentação
- **Ordem de Produção:** Geração, exportação em PDF, controle e status
- **Dashboard:** Visão geral, métricas, gráficos e indicadores

---


## Recursos Técnicos

- **Performance:** Lazy loading, compressão Gzip, cache, otimização de imagens, code splitting
- **Segurança:** Autenticação, autorização, validação e sanitização de dados, headers de segurança, CORS
- **Infraestrutura:** Deploy com Docker, firewall, Git

---
