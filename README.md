# Atividade prática — Engenharia Reversa aplicada ao NOXBYTE

## Diagrama geral da engenharia reversa

Este seria o melhor diagrama para apresentar na atividade:

NOXBYTE
│
▼
SISTEMA EM FUNCIONAMENTO
│
▼
┌──────────────────┐
│ USUÁRIO │
└────────┬─────────┘
│
▼
🌐 INTERNET
│
▼
┌──────────────────┐
│ FRONTEND │
│ Interface Web │
└────────┬─────────┘
│
Requisições HTTP
│
▼
┌──────────────────┐
│ API / BACKEND │
│ Express │
└────────┬─────────┘
│
▼
┌──────────────────┐
│ PRISMA │
└────────┬─────────┘
│
▼
┌──────────────────┐
│ POSTGRESQL │
│ Banco de Dados │
└──────────────────┘

 ↑ Engenharia Reversa ↓

 
## Identificação dos componentes do NOXBYTE

| Conceito       | Como aparece no NOXBYTE |
|----------------|--------------------------|
| **Entradas**       | Pesquisas, cliques, seleção de categorias, acesso às páginas, login e dados cadastrados pelos administradores |
| **Processamento**  | Consultas de produtos, filtros, organização por categorias e subcategorias, autenticação e processamento das requisições |
| **Armazenamento**  | Banco de dados PostgreSQL, responsável por armazenar produtos, categorias, subcategorias e informações administrativas |
| **Saídas**         | Produtos, categorias, ofertas, informações dos produtos, resultados de pesquisas e mensagens do sistema |
| **Usuários**       | Visitantes/clientes e administradores |
| **Comunicação**    | Comunicação entre navegador, frontend, API/servidor e banco de dados através da Internet e de requisições HTTP |

## Conclusão

A análise do NOXBYTE demonstra como a engenharia reversa pode ser utilizada para compreender um software já existente.

A partir da observação do sistema, é possível identificar suas entradas, processamento, armazenamento, saídas, usuários e formas de comunicação. Também é possível identificar sua arquitetura, composta por frontend, backend/API e banco de dados.

Dessa maneira, a engenharia reversa permite sair da visão superficial de "um site que mostra produtos" e compreender o que existe por trás da interface: requisições, processamento, regras, armazenamento e comunicação entre diferentes componentes de software.
