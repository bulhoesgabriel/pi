# Projectify
## Gerenciador de Projetos - Aplicativo para gestão de projetos desenvolvido com React.js & Node.js

> Atividade avaliativa (Projeto Integrador) do curso de Análise e Desenvolvimento de Sistemas (SENAC)
## Revisitando o projeto apresentado - Definição da prova de conceito que precisa ser desenvolvida: 

- O projeto FileTransfer passou por uma reformulação estratégica. Inicialmente concebido como uma plataforma para transferência gratuita de arquivos, o projeto mostrou-se inviável no curto prazo devido à sua complexidade técnica e à ausência do investimento necessário para garantir a infraestrutura de armazenamento segura e escalável para todos os usuários. 
- Diante disso, a equipe optou por redirecionar seus esforços para um novo produto mais viável e igualmente relevante: ProjectFy, um gerenciador de projetos. 
- O ProjectiFy nasce com o objetivo de facilitar a organização, o acompanhamento de tarefas e a produtividade de equipes, oferecendo uma solução prática e eficiente para quem precisa gerenciar projetos com agilidade e controle. 

## Público-alvo do ProjectiFy

O ProjectiFy é voltado para profissionais e equipes que precisam organizar e acompanhar o progresso de múltiplos projetos. Nosso foco principal está em: 

- Freelancers e profissionais autônomos que lidam com diversos clientes simultaneamente. 

- Pequenas empresas e startups que necessitam de ferramentas acessíveis e intuitivas para gestão de projetos. 

- Gestores de equipes que desejam ter uma visão clara de tarefas, prazos e responsabilidades. 

- Estudantes e grupos acadêmicos que precisam coordenar trabalhos em grupo e dividir responsabilidades. 

##  Jornada do Usuário no ProjectiFy 

Criação de um novo projeto 
 
Ao acessar o painel principal, o usuário pode: 

- Adicionar um novo projeto com título, descrição e prazos. 

- Escolher uma categoria (Ex: Pessoal, Cliente X, Estudo, etc.). 

- Atribuir status (em andamento, concluído, arquivado, etc.). 

Gerenciamento de projetos 

- Visualizar todos os projetos com filtros por categoria ou status. 

- Editar informações do projeto. 

- Remover projetos obsoletos. 

- Adicionar tarefas ou subtarefas com prazos, responsáveis e notas. 

Organização por categorias 

- Os projetos podem ser organizados por categorias customizáveis pelo usuário (como “Clientes”, “Pessoal”, “Estudos”, etc.). 

- Possibilidade de visualizar estatísticas por categoria, como número de projetos ativos ou tarefas pendentes. 

Finalização e acompanhamento 

- Marcar projetos como concluídos. 

- Ver histórico de progresso. 

- Receber lembretes e alertas de prazos (futuro). 

## Persona 1: Mariana, a Freelancer de Design 

Idade: 29 anos 

Profissão: Designer Gráfica Freelancer 

Objetivo: Organizar os prazos e entregas dos projetos dos seus clientes em um só lugar. 

- Desafios: 

Muitos projetos simultâneos com prazos diferentes. 

Dificuldade em visualizar o que está em andamento e o que está atrasado. 

- Como o ProjectiFy ajuda: 

Mariana cria categorias como "Clientes", "Pessoal" e "Estudos". 

Ela cadastra cada projeto e consegue ver rapidamente o status de cada um. 

Usa o ProjectiFy diariamente para revisar o que precisa ser entregue. 

 

## Persona 2: Rodrigo, o Coordenador de Equipe 

Idade: 35 anos 

Profissão: Coordenador de Projetos em uma startup de tecnologia 

Objetivo: Acompanhar o progresso dos projetos de sua equipe e manter tudo centralizado. 

- Desafios: 

Comunicação fragmentada entre membros. 

Falta de clareza sobre quem está responsável por cada tarefa. 

- Como o ProjectiFy ajuda: 

Rodrigo cria projetos e atribui tarefas com prazos e responsáveis. 

Consegue visualizar rapidamente o andamento das atividades. 

Organiza os projetos por categoria (Ex: Frontend, Backend, UX). 

 

## Preparação do Ambiente de Desenvolvimento – ProjectiFy

O ProjectiFy é um sistema CRUD (Create, Read, Update, Delete) que permite gerenciar projetos de forma simples e organizada.  

A arquitetura do ProjectiFy segue o modelo cliente-servidor. O frontend em React se comunica com uma API backend feita em Node.js, que manipula dados armazenados em um arquivo .json. O backend está hospedado no Render, e o arquvo completo no Vercel, garantindo uma separação clara entre interface e lógica de dados, com integração simples e eficiente para a prova de conceito. 

Frontend: React.js 

Backend: Node.js 

Banco de Dados:.JSON 

##  Desenvolvimento FrontEnd do projeto

A escolha de cores do Projectify seguiu os critérios de contraste recomendados pela WCAG 2.1 (nível AA), para garantir legibilidade e inclusão, especialmente para pessoas com deficiência visual ou daltonismo, e possuí um design adaptavel a telas de diferentes tamanhos.

Foi criada uma interface funcional para: 

- Listar projetos. 

- Cadastrar novo projeto. 

- Editar/remover projetos. 

- Filtrar por categorias. 

## Desenvolvimento do Backend do projeto (com repositório de dados associado). 

O backend do Projectify foi desenvolvido em Node.js e um arquivo .json como banco de dados simulado. Esse arquivo está hospedado na plataforma Render, permitindo que o frontend faça requisições via API. Toda a aplicação, incluindo o frontend em React, está hospedada no Vercel, garantindo integração e funcionamento completo do sistema. 

## Link e Video do projeto funcionando

- 🔗 Link do projeto: https://projectify-green.vercel.app
- 🔗 Link do vídeo: https://drive.google.com/file/d/1MMXk1FTxG4hjbT93albwvI5hOH5ymYhd/view?usp=sharing

## Instruções ao baixar o repositório
No diretório do projeto, execute este comando no terminal para rodar o aplicativo em modo de desenvolvimento:
```sh 
npm run start-all
```

Abra o local host para visualiza-lo no seu navegador:
```sh
http://localhost:3000
```

## Integrantes

- Ariel Medeiros
- Felipe Lemos
- Gabriel Bulhões
- Andrius Gottems
- Carlos Augusto Praeiro
- Diogo Araujo Freitas

**Atividade avaliativa (Projeto Integrador) do curso de Análise e Desenvolvimento de Sistemas (SENAC-SP)!**


