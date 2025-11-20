<!--START_SECTION:header-->
<div align="center">
  <p align="center">
    <img 
      alt="DIO Education" 
      src="https://raw.githubusercontent.com/digitalinnovationone/template-github-trilha/main/.github/assets/logo.webp" 
      width="100px" 
    />
    <h1>Curso Básico de Python Django para Iniciantes</h1>
  </p>
</div>
<!--END_SECTION:header-->

<p align="center">
  <img src="https://img.shields.io/static/v1?label=DIO&message=Education&color=E94D5F&labelColor=202024" alt="DIO Project" />
  <img src="https://img.shields.io/static/v1?label=Nivel&message=B%C3%A1sico&color=E94D5F&labelColor=202024" alt="Nivel" />
</p>

---

### Sobre o Projeto

Curso prático e orientado a projeto para iniciantes que desejam transição para desenvolvimento web full‑stack com foco em Python e Django. Do setup do ambiente ao deploy, com ênfase em GitHub, APIs com Django REST Framework e construção de um portfólio publicável.

---

### Público‑alvo e pré‑requisitos

- Público‑alvo: iniciantes com desejo de transição para desenvolvimento web full‑stack com foco em código.  
- Pré‑requisitos mínimos:
  - Lógica de programação básica
  - Noções de terminal/linha de comando
  - Capacidade de instalar programas no sistema operacional

---

### Objetivos do curso

Ao final do curso o estudante será capaz de:
- Desenvolver aplicações web completas com Django (CRUD, autenticação, templates).  
- Criar e documentar APIs REST usando Django REST Framework.  
- Versionar projetos e colaborar no GitHub (branches, PRs, issues, README).  
- Fazer deploy de aplicações em um serviço cloud gratuito.  
- Montar e publicar um projeto de portfólio com documentação profissional.

---

## Estrutura do curso

### Módulo 0 Ambiente e GitHub (6 horas)
- 0.1 Instalação Python e Pip  
- 0.2 Configurar ambiente virtual (venv/virtualenv)  
- 0.3 Instalar e configurar Git local  
- 0.4 Criar conta GitHub e repositório inicial  
- 0.5 Boas práticas de commits, .gitignore e README inicial  
- 0.6 GitHub Pages (opcional) para documentação estática

Objetivo: Ambiente pronto, repositório no GitHub com README e workflow básico.

---

### Módulo 1 Fundamentos de Python (18 horas)
- 1.1 Tipos primitivos, variáveis e operadores  
- 1.2 Estruturas de controle (if, for, while)  
- 1.3 Coleções: listas, tuplas, dicionários, sets  
- 1.4 Funções, argumentos, retorno e escopo  
- 1.5 Módulos, pacotes e pip  
- 1.6 Conceitos básicos de OOP: classes, métodos, herança  
- 1.7 Exercícios práticos e pequenos scripts utilitários

Objetivo: Domínio da sintaxe Python usada no desenvolvimento web.

---

### Módulo 2 HTML, CSS e JavaScript Básico (12 horas)
- 2.1 Estrutura HTML semântica  
- 2.2 CSS: layout com Flexbox e Grid, responsividade básica  
- 2.3 Formulários HTML e validação no front-end  
- 2.4 JavaScript: DOM, eventos e fetch/axios básico  
- 2.5 Integração simples com API (fetch) e manipulação de respostas

Objetivo: Construir interfaces simples e conectar com back‑end via HTTP.

---

### Módulo 3 Introdução ao Django (24 horas)
- 3.1 Conceitos: projetos, apps, MTV (model-template-view)  
- 3.2 Criar projeto e app Django; settings essenciais  
- 3.3 URLs, views (FBV e CBV) e templates  
- 3.4 Modelos e migrations (Django ORM)  
- 3.5 Formulários Django: validation e ModelForm  
- 3.6 Admin site customizado  
- 3.7 Uploads de arquivo e gerenciamento de mídia estática

Objetivo: Construir aplicações Django completas com persistência e interface administrativa.

---

### Módulo 4 APIs com Django REST Framework (DRF) (16 horas)
- 4.1 Conceitos REST e arquitetura de endpoints  
- 4.2 Serializers e validação de dados  
- 4.3 ViewSets, Routers e rotas versionadas  
- 4.4 Autenticação token / JWT básica  
- 4.5 Testes de API com Postman / HTTPie  
- 4.6 Documentação básica da API (Swagger / drf-yasg)

Objetivo: Expor dados e funcionalidades do app via API segura e documentada.

---

### Módulo 5 Banco de Dados e Produção (10 horas)
- 5.1 Configurar PostgreSQL local / via Docker  
- 5.2 Migrations avançadas e índices básicos  
- 5.3 Conexão segura (variáveis de ambiente)  
- 5.4 Performance básica: select_related / prefetch_related  
- 5.5 Backups e estratégias simples de restauração

Objetivo: Preparar app para uso real com banco robusto e configurações de produção.

---

### Módulo 6 Testes, CI e Deploy (12 horas)
- 6.1 Testes unitários com Django TestCase e pytest  
- 6.2 GitHub Actions: pipeline básico para tests e deploy automático  
- 6.3 Deploy em Railway/Render/Heroku: env vars, static files, collectstatic  
- 6.4 Monitoramento básico e logs

Objetivo: Entregar código confiável e automatizar fluxo de integração e publicação.

---

### Módulo 7 Projeto de Portfólio (22 horas)
- 7.1 Planejamento do projeto (issues e milestones no GitHub)  
- 7.2 Implementação incremental em branches com PRs  
- 7.3 Testes, documentação e deploy final  
- 7.4 Preparar README profissional, screenshots, GIFs e link do deploy  
- 7.5 Publicação no GitHub e divulgação (LinkedIn/portfolio)

Projeto sugerido: Plataforma de Blog com autenticação, editor de posts, comentários, pesquisa e API pública.

Critérios de aceitação:
- Registro/login funcional; CRUD de posts; comentários; API documentada; deploy público; README com instruções.

---

## Metodologia e avaliações

- Método: 40% teoria curta + 60% prática hands‑on; entregas semanais no GitHub.  
- Avaliações: quizzes ao final de cada módulo; revisão de código (peer review simulado); avaliação final baseada no projeto de portfólio.  
- Entregáveis semanais: issue concluída, PR com descrição e screenshots, atualização do README.

---

## Cronograma sugerido (120 dias / 4 meses)

- Meses 1–2: Módulos 0, 1, 2, 3 (fundamentos e primeiro app Django)  
- Mês 3: Módulos 4 e 5 (API e banco)  
- Mês 4: Módulo 6 e 7 (CI/CD, deploy e projeto final)

Sugestão de carga: 10 horas/semana divididas em 5 blocos de 2 horas: 1 bloco teoria, 3 blocos hands‑on, 1 bloco revisão/GitHub.

---

## Recursos recomendados

- Documentação oficial: Python, Django, Django REST Framework, PostgreSQL  
- Ferramentas: VS Code, Git, GitHub, Postman, Docker (opcional)  
- Cursos base sugeridos: Formação Python (DIO), módulos oficiais de Django e Git/GitHub

---

## Guia rápido de GitHub para o curso

- Criar repositório público para o projeto final  
- Usar branches por feature: feature/nome, hotfix/nome  
- Abrir PRs com descrição, checklist e referência a issues  
- Manter README com: visão geral, requisitos, instruções de instalação, exemplos de uso, link do deploy e badges  
- Usar GitHub Projects (Kanban) para organizar sprints semanais

---

## Templates fornecidos (sugestões para incluir no repositório)

- Template de README com seções obrigatórias  
- Template de ISSUE/PR para descrever tarefa e checklist  
- Workflow GitHub Actions exemplo para rodar testes e deploy

---

## Próximos passos

1. Criar repositório inicial no GitHub e subir README com sumário do curso.  
2. Seguir Módulo 0 e Módulo 1 nas primeiras 3 semanas.  
3. Abrir issues semanais e registrar progresso com commits pequenos.

---

<!--START_SECTION:footer-->

<br />
<br />

<p align="center">
  <a href="https://www.dio.me/" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/digitalinnovationone/template-github-trilha/main/.github/assets/footer.png" alt="banner"/>
  </a>
</p>

<!--END_SECTION:footer-->
