# Miniguia: Git e GitHub para Iniciantes

## ▷ Contexto e Objetivos
Escolhi Git e GitHub pois são ferramentas essenciais para qualquer desenvolvedor. Quero aprender a versionar meus projetos e publicar meu portfólio. O principal objetivo é dominar os comandos básicos e entender o fluxo de trabalho com repositórios. <br>
Este material foi construído com o auxílio do NotebookLM, utilizando fontes abertas e gratuitas, e serve como guia de referência para revisões futuras.

## ▷ Fontes
As fontes abaixo foram selecionadas e adicionadas ao NotebookLM para enriquecer este caderno temático:

1. **Como escrever no GitHub – Documentos do Git**
   Guia oficial sobre escrita e formatação no GitHub, incluindo o uso de Markdown em repositórios.

2. **Git – Documentação Oficial (git-scm.com)**
   Documentação completa e oficial do Git, abordando desde conceitos básicos até funcionalidades avançadas.

3. **Git – Pro Git Book (git-scm.com)**
   Segunda seção da documentação oficial, com aprofundamento em fluxos de trabalho e boas práticas.

4. **Git Tutorial – W3Schools**
   Tutorial interativo e visual voltado para iniciantes, com exemplos práticos de cada comando.

5. **GitHub Docs**
   Guia oficial do GitHub com tutoriais sobre criação de repositórios, pull requests e colaboração.

6. **O que é o Git? – Tutorial da Atlassian**
   Explicação conceitual do Git com foco em boas práticas e contexto profissional.

7. **git - guia prático - sem complicação! (Roger Dudler)**
   Guia rápido, visual e direto ao ponto, ideal para quem está começando agora.

## ▷ Engenharia de Prompts e Troubleshooting
Abaixo estão os prompts que utilizei no NotebookLM, os resultados obtidos e os ajustes realizados.

### Prompt 1
**Pergunta:** "O que é Git e qual a diferença entre Git e GitHub? Explique como se eu tivesse 15 anos."<br>
**Resultado:** Resposta clara e acessível, com analogia de "salvar versões de um documento".<br>
**Observação:** A adição de "como se eu tivesse 15 anos" foi essencial para tornar a resposta mais didática.

### Prompt 2
**Pergunta:** "Quais são os 5 comandos Git mais usados por iniciantes e para que serve cada um?"<br>
**Resultado:** O NotebookLM listou os seguintes comandos essenciais:
1. `git init`
2. `git clone`
3. `git add` 
4. `git commit -m "mensagem"`
5. `git push` <br>

Além desses, o `git pull` também foi destacado como essencial para atualizar o repositório local com as mudanças feitas por outras pessoas. <br>
**Observação:** Resposta clara e completa já na primeira tentativa. 

### Prompt 3
**Pergunta:** "Crie um resumo estruturado com os conceitos fundamentais de Git abordados nas fontes."<br>
**Resultado:** Resumo completo, mas longo demais na primeira versão. Utilizou muitos itens e dificultou a compreensão rápida.<br>
**Ajuste:** Adicionei "estruture em um parágrafo em no máximo 200 palavras" e o resultado ficou mais adequado.<br>

### Prompt 4
**Pergunta:** "Com base nas fontes, crie um glossário com os 15 termos mais importantes do Git e GitHub."<br>
**Resultado:** Glossário bem estruturado com definições claras, porém muito longas.<br>
**Observação:** Adicionei "com descrições de até 15 palavras" e resultou em um glossário mais limpo."<br>

### Prompt 5
**Pergunta:** "Crie 10 perguntas de fixação sobre Git e GitHub para eu me auto-avaliar."<br>
**Resultado:** Perguntas variadas, cobrindo teoria e prática.<br>
**Observação:** Boa resposta já na primeira tentativa.<br>

## ▷ Resumos Estruturados

### O que é Git?
Git é um sistema de controle de versão distribuído que permite rastrear alterações no código ao longo do tempo. Com ele, é possível voltar a versões anteriores, trabalhar em equipe sem conflitos e manter um histórico completo do projeto.

### O que é GitHub?
GitHub é uma plataforma online que hospeda repositórios Git na nuvem. Ele facilita a colaboração entre desenvolvedores, permite o compartilhamento de código e é amplamente utilizado como portfólio profissional na área de tecnologia.

### Fluxo Básico do Git
1. `git init` — Inicia um repositório local
2. `git add .` — Adiciona os arquivos à área de preparação
3. `git commit -m "mensagem"` — Registra as alterações com uma descrição
4. `git remote add origin <url>` — Conecta o repositório local ao GitHub
5. `git push origin main` — Envia as alterações para o repositório remoto

### Conceitos Importantes
- **Branch:** Ramificação do projeto que permite desenvolver funcionalidades de forma isolada
- **Merge:** União de duas branches em uma só
- **Pull Request:** Solicitação para integrar alterações de uma branch à principal
- **Clone:** Cópia de um repositório remoto para a máquina local
- **Fork:** Cópia de um repositório de outro usuário para o seu perfil

## ▷ Glossário
| Termo | Definição |
|-------|-----------|
| **Git** | Sistema de controle de versão distribuído |
| **GitHub** | Plataforma online para hospedagem de repositórios Git |
| **Repositório** | Pasta do projeto que contém todo o histórico de versões |
| **Commit** | Registro de uma alteração no código com mensagem descritiva |
| **Branch** | Ramificação do projeto para desenvolvimento paralelo |
| **Merge** | União de duas branches |
| **Push** | Envio de alterações locais para o repositório remoto |
| **Pull** | Atualização do repositório local com as alterações remotas |
| **Clone** | Cópia de um repositório remoto para a máquina local |
| **Fork** | Cópia de um repositório de outro usuário para o seu perfil |
| **Pull Request** | Solicitação para integrar alterações à branch principal |
| **README** | Arquivo de documentação principal de um repositório |
| **Stage** | Área de preparação antes de confirmar um commit |
| **Conflict** | Divergência entre versões que precisa ser resolvida manualmente |
| **Init** | Comando que inicializa um novo repositório Git |

## ▷ Prompts Reutilizáveis

Use estes prompts para revisões futuras sobre o tema:

- "Explique o fluxo básico do Git do init ao push para um iniciante."
- "Quais são os erros mais comuns de iniciantes no Git e como corrigi-los?"
- "Crie 10 perguntas de fixação sobre Git e GitHub."
- "Monte um plano de estudos de 1 semana para aprender Git do zero."
- "Explique a diferença entre merge e rebase com exemplos simples."
- "O que é um Pull Request e como funciona na prática?"
- "Crie um glossário com os termos essenciais do Git e GitHub."
- "Resuma os comandos Git mais usados no dia a dia de um desenvolvedor."

***Projeto desenvolvido como parte do desafio prático da DIO, utilizando o NotebookLM como ferramenta de aprendizagem ativa.***
