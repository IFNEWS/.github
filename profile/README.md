# 📰 IFNEWS

Bem-vindo à página oficial do nosso projeto de desenvolvimento de um **portal de notícias escolares**! Esta iniciativa surgiu para resolver um problema comum em muitas instituições de ensino: a **comunicação falha ou tardia** entre a coordenação, os professores e os alunos.## 

Atualmente, a disseminação de informações é esparsa e nem todos os comunicados chegam a todos os alunos. Nosso objetivo é criar uma plataforma acessível, clara e centralizada para garantir que **ninguém fique de fora** do que acontece na escola.

---
**IMPORTANTE:**(https://docs.google.com/spreadsheets/d/1KXuMJ9TK7GPyahR_BfLwfn4ec7vX7DgiHx42vFc4E7g/edit?gid=932601097#gid=932601097)
---

## 🎯 Objetivo do Projeto

Desenvolver um site de notícias voltado à comunidade escolar, com foco em:

- Publicação de comunicados oficiais da coordenação;
- Avisos de professores e eventos escolares;
- Canal direto e transparente de comunicação com os alunos;
- Acesso rápido e prático por qualquer dispositivo com internet.

---

## 🧩 Tecnologias Utilizadas (exemplo - personalize)

- HTML, CSS
- Framework Frontend:
- Backend:
- Banco de dados:

---

## ❗ Situação-Problema Identificada

- Muitos alunos não recebem avisos importantes da coordenação;
- Mudanças de cronograma ou eventos não chegam a todos a tempo;
- Falta de um canal oficial centralizado para consultas rápidas;
- Dependência de murais físicos ou mensagens informais.

---

## 💡 Solução Proposta

Uma plataforma web centralizada e responsiva que:

- Permite à coordenação postar avisos diretamente no site;
- Oferece histórico de notícias, editais e cronogramas;
- Garante visibilidade e alcance das informações;
- Melhora a organização da comunicação interna da escola.

---

## 🛠️ Funcionalidades Previstas

- Área pública para visualização de notícias e eventos;
- Área administrativa para publicação de conteúdo;
- Filtro por categoria (coordenação, professores, eventos, etc.);
- Sistema de busca por palavras-chave ou datas;
- Notificações (e-mail ou push, opcional).

---

## 👥 Equipe de Desenvolvimento

- [Luiz Miguel Lima de Souza](https://github.com/LMSLima)

👨‍🏫 **Professor orientador**: [Marco André Mendes](https://github.com/marrcandre)

---

## 🔗 Links Importantes (preencha com os reais)

- 📄 Documentação: [Link para a documentação](#)
- ⚙️ Backend: [Link do repositório backend](#)
- 🎨 Frontend: [Link do repositório frontend](#)
- 🌐 Site em produção: [](#)

---

## 📬 Contato

- E-mail: [lmiguells095@gmail.com]

---

## 📘 Especificação do Projeto — IFNEWS

  📌 Regras de Negócio

Somente usuários autenticados com permissão de administrador podem publicar, editar ou excluir notícias.

Usuários do tipo "Aluno" ou "Visitante" só têm permissão para visualizar conteúdos públicos.

Notícias devem ser categorizadas como: "Coordenação", "Professores", "Eventos", "Avisos Gerais".

Cada notícia deve conter: título, conteúdo, autor, data de publicação e categoria.

Notícias não podem ser publicadas com data futura.

A exclusão de uma notícia exige confirmação dupla para evitar perda acidental de informações.

Todas as publicações devem ser armazenadas com histórico de edições (log).

Professores podem publicar conteúdos apenas na categoria "Professores" ou "Eventos", salvo autorização da coordenação.

A coordenação tem acesso completo ao painel administrativo, incluindo gerenciamento de usuários.

Notificações por e-mail ou push só podem ser enviadas para usuários cadastrados e com consentimento.

  ✅ Requisitos Funcionais

Os requisitos funcionais descrevem tudo que o sistema precisa fazer do ponto de vista do usuário e do funcionamento da aplicação.

🔐 Autenticação e Acesso
RF01: O sistema deve permitir login de usuários (alunos, professores e coordenação).
RF02: O sistema deve permitir cadastro e gerenciamento de usuários pela coordenação.
RF03: O sistema deve aplicar controle de acesso baseado em perfis (Admin, Professor, Aluno, Visitante).

📰 Gerenciamento de Notícias
RF04: O sistema deve permitir criar, editar e excluir notícias.
RF05: O sistema deve exibir a lista de notícias com título, resumo, autor, data e categoria.
RF06: O sistema deve permitir filtrar notícias por categoria.
RF07: O sistema deve permitir pesquisar notícias por palavras-chave.
RF08: O sistema deve permitir visualizar a notícia completa em uma página dedicada.
RF09: O sistema deve manter histórico de edições de cada notícia.

📅 Eventos e Cronogramas
RF10: O sistema deve permitir a publicação de eventos com data, descrição e local.
RF11: O sistema deve exibir um calendário de eventos futuros.

🔔 Notificações
RF12: O sistema deve permitir o envio de notificações por e-mail para usuários cadastrados.
RF13: O sistema deve permitir ativar ou desativar notificações nas configurações do usuário.

👥 Administração
RF14: O sistema deve permitir à coordenação aprovar ou remover usuários.
RF15: O sistema deve permitir o gerenciamento de permissões (ex: tornar um professor administrador).
RF16: O sistema deve permitir visualizar logs de ações realizadas no sistema.

🚫 Requisitos Não Funcionais

🔒 Segurança
RNF01: O sistema deve criptografar senhas utilizando algoritmo seguro (ex: bcrypt).
RNF02: O sistema deve manter sessões com tokens de autenticação válidos e protegidos.
RNF03: O sistema deve validar e sanitizar todos os inputs para evitar injeções e XSS.

📱 Usabilidade
RNF04: O sistema deve ser responsivo e acessível em dispositivos móveis e desktop.
RNF05: A interface deve seguir princípios de design claro, com botões e menus bem identificados.
RNF06: O sistema deve fornecer mensagens de erro e sucesso claras para o usuário.

 ⚙️ Performance
RNF07: O sistema deve carregar a página inicial com tempo inferior a 2 segundos em rede 4G.
RNF08: O sistema deve suportar pelo menos 100 acessos simultâneos sem degradação perceptível de desempenho.

🕒 Disponibilidade e Backup
RNF09: O sistema deve estar disponível 99% do tempo (exceto janelas de manutenção).
RNF10: O banco de dados deve ser backupado automaticamente ao menos 1 vez por dia.

📂 Documentação e Manutenção
RNF11: O sistema deve ter documentação técnica acessível para novos desenvolvedores.
RNF12: O código deve seguir boas práticas de desenvolvimento (ex: PEP8, ESLint, etc.).
