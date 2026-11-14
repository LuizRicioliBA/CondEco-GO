[CondEco-GO.md](https://github.com/user-attachments/files/34842254/CondEco-GO.md)
![Logo pequeno do CondEco-GO](condeco-go-small.png)

# 🌿 CondEco-GO

### Sistema de apoio à gestão ambiental de condomínios

Uma plataforma web para organizar informações ambientais e facilitar o acompanhamento da rotina do condomínio.

![Projeto APS UNIP](https://img.shields.io/badge/PROJETO-APS%20%7C%20UNIP-2E7D32?style=for-the-badge) ![Frontend HTML CSS JavaScript](https://img.shields.io/badge/FRONTEND-HTML%20%7C%20CSS%20%7C%20JAVASCRIPT-F7DF1E?style=for-the-badge) ![Backend Node.js e Express](https://img.shields.io/badge/BACKEND-NODE.JS%20%2B%20EXPRESS-339933?logo=node.js&logoColor=white&style=for-the-badge) ![Dados Supabase e PostgreSQL](https://img.shields.io/badge/DADOS-SUPABASE%20%2B%20POSTGRESQL-3ECF8E?logo=supabase&logoColor=white&style=for-the-badge)

---

## 🎯 Sobre o projeto

O **CondEco-GO** foi desenvolvido para apoiar a organização das informações ambientais de condomínios em Goiás. Em vez de manter dados espalhados por planilhas e documentos, a equipe pode registrar informações em um só lugar, acompanhar sua evolução e consultar relatórios.

O sistema é voltado ao **responsável administrativo** e ao **síndico**, com contas e permissões próprias. Seu objetivo é facilitar o acompanhamento e apoiar decisões administrativas, sem substituir a conferência dos dados ou uma avaliação técnica ambiental.

## 🚀 Funcionalidades principais

- **Consumo de água e energia:** registro mensal dos valores, unidades e custos informados.
- **Gestão de resíduos:** acompanhamento do tipo, quantidade, data e destinação dos resíduos.
- **Ocorrências ambientais:** registro de situações de descarte irregular e acompanhamento até sua resolução.
- **Metas ambientais:** organização de objetivos por indicador e período.
- **Ações ambientais:** acompanhamento de responsáveis, prazos, situação e observações.
- **Painel de acompanhamento:** visualização de indicadores e informações recentes do condomínio.
- **Relatórios:** consultas mensais e anuais, com opção de exportação anual em PDF.
- **Dados do condomínio:** atualização de informações e organização de blocos e quantidades de apartamentos.
- **Acesso por perfil:** autenticação e permissões associadas ao usuário e ao condomínio.

## 🗂️ Como funciona

1. **Registre as informações:** usuários autorizados cadastram os consumos de água e energia, os resíduos e as ocorrências. Também podem organizar metas e ações ambientais.
2. **Acompanhe o condomínio:** consulte no painel os indicadores, os registros recentes, as ocorrências pendentes e o andamento das ações.
3. **Gere relatórios e planeje providências:** consulte os dados por mês ou ano e use as informações para acompanhar metas e organizar as próximas ações ambientais.

Por trás da interface, o fluxo é: **Navegador → API Node.js/Express → Supabase/PostgreSQL**. Os dados são enviados à API, que valida a solicitação e verifica o acesso antes de consultar ou atualizar os registros do condomínio.

## 🧰 Tecnologias

- **Interface:** HTML, CSS e JavaScript.
- **Servidor e API:** Node.js e Express.
- **Autenticação e persistência:** Supabase Auth e PostgreSQL.
- **Relatórios em PDF:** jsPDF e jspdf-autotable no navegador.

## 🌱 Escopo e limites

O CondEco-GO organiza informações inseridas pelos usuários. O sistema não lê hidrômetros ou medidores automaticamente, não se integra às concessionárias, não calcula emissões de carbono e não certifica conformidade com normas ambientais. A confiabilidade dos indicadores depende da qualidade e da conferência dos dados cadastrados. As informações usadas em demonstrações são fictícias e não representam medições reais.

## 🎓 Contexto acadêmico

Projeto desenvolvido como **Atividade Prática Supervisionada (APS)** do curso de Ciência da Computação da **Universidade Paulista (UNIP)**, em 2026.
