# 🔄 Fluxo de Trabalho com GitHub Projects e GitFlow

Este documento descreve o fluxo de trabalho que deve ser seguido pelos membros do squad durante a execução das atividades no contexto dos projetos do CEIA.

---

## Visão Geral

O gerenciamento de tarefas será feito pela **Coordenação Técnica** através do **GitHub Projects**, e o versionamento dos artefatos seguirá o modelo **GitFlow**.

---

## 📋 1. GitHub Projects — Movimentação de Issues

Abaixo está o processo padrão de como uma issue deve ser tratada:

### To Do
- A issue será atribuída a um membro do squad pela **Coordenação Técnica**.
- A issue aparecerá na coluna **To Do**.

### In Progress
- Assim que iniciar o trabalho, o membro do squad deve mover a issue para a coluna **In Progress**.
- A movimentação é manual, feita diretamente na interface do GitHub Projects.


### In Review

Ao finalizar a atividade:

- **Se a entrega for versionada no repositório** (ex: código, documentação, arquivos de configuração, CSVs, etc):
  - Crie um **Pull Request (PR)** associando-o à issue correspondente.
  - Descreva claramente no PR o que foi feito e inclua links ou contexto, se necessário.

- **Se a entrega não for versionada diretamente no repositório** (ex: protótipo, apresentação, documento externo):
  - Escreva um **comentário na issue** descrevendo a entrega e incluindo o link de acesso ao material.
    
    Exemplo: "Protótipo disponível em: [link do Figma]".
    
- Em seguida, mova a issue para a coluna **In Review**.

## Atualizações de Progresso

- **Dois ou três dias úteis antes da reunião de acompanhamento**, é recomendado que o membro do squad:
  - Escreva um comentário na issue informando:
    - O progresso da atividade
    - Dificuldades encontradas ou impedimentos

> ⚠️ Essa rotina pode ser adaptada pelo Coordenador Técnico conforme a necessidade da equipe.

---

## 📁 2. GitFlow — Organização do Código

- Os repositórios dos projetos do CEIA devem seguir o modelo **GitFlow**, com as seguintes convenções para facilitar a colaboração e manter a consistência.

---

### 🔧 Principais branches

| Branch        | Descrição                                             |
|---------------|--------------------------------------------------------|
| `main`        | Código estável e em produção                             |
| `develop`     | Integração de funcionalidades em desenvolvimento         |
| `feature/*`   | Desenvolvimento de novas funcionalidades                |
| `hotfix/*`    | Correções de bugs                                       |

---

### Padrão de nomes de branches

Utilize o prefixo da categoria seguido do número da issue relacionada e um nome descritivo em `kebab-case`:

```
feature/42-login-tela
hotfix/50-erro-validacao-formulario
```
---

### Pull Requests

#### Título do PR

Use o padrão:

```
[feature] Cria tela de login
[hotfix] Corrige validação do formulário
```

> O prefixo entre colchetes indica o tipo da entrega.

#### Descrição do PR

- Faça um resumo do que foi entregue.
- Vincule a issue correspondente:
  ```
  Closes #42
  ```

---

### Processo de revisão

- _Em construção_

---


### Exemplo de Fluxo

_1. Em construção_

## Boas Práticas
- Vincule seu Pull Request à issue correspondente.
- Descreva bem o que foi feito no título e descrição do PR.
- Use comentários na issue para manter o progresso do trabalho desenvolvido e a comunicação clara com o time.

   
