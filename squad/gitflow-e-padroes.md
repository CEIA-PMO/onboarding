## 📁 GitFlow — Organização do Código

Os repositórios dos projetos do CEIA devem seguir o modelo **GitFlow**, com as seguintes convenções para facilitar a colaboração e manter a consistência.

---

### Principais branches

| Branch        | Descrição                                             |
|---------------|--------------------------------------------------------|
| `main`        | Código estável e em produção                             |
| `develop`     | Integração de funcionalidades em desenvolvimento         |
| `feature-*`   | Desenvolvimento de novas funcionalidades                |
| `hotfix-*`    | Correções de bugs                                       |

---

### Padrão de nomes de branches

Utilize o prefixo da categoria seguido do número da issue relacionada e um nome descritivo em `kebab-case`:

```
feature-42-login-tela
hotfix-50-erro-validacao-formulario
```
---

### Padrão de mensagens de commits

A mensagem de commit deve seguir a seguinte regra: \
`#[número da issue] - [mensagem de commit]`

Exemplos de mensagem de commits numa branch para realizar a issue 42:

```
#42 - Criação da tela de login
#42 - Inclusão do botão de recuperação de senha
#42 - Alteração da lógica de checagem de email válido
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

## Boas Práticas
- Vincule seu Pull Request à issue correspondente.
- Descreva bem o que foi feito no título e descrição do PR.
- Use comentários na issue para manter o progresso do trabalho desenvolvido e a comunicação clara com o time.
