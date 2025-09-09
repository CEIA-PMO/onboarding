# 📋 Uso do GitHub Projects

O GitHub Projects será utilizado como **ferramenta oficial de acompanhamento técnico**.  
Toda atividade deve ser registrada como **issue** e vinculada ao quadro do projeto.

## Checklist do Coordenador Técnico

- Criar issues para cada atividade relevante.
- Garantir que as descrições contenham informações mínimas para compreensão.
- Revisar semanalmente o quadro, movendo issues conforme status real.
- Acompanhar prazos das macroentregas.

## Template Oficial do CEIA

O template oficial segue a seguinte configuração.

### Visualizações Disponíveis

O template oferece diferentes formas de visualizar as atividades no board:

| Aba               | Descrição |
|-------------------|-----------|
| **Backlog**        | Visualização em quadro (Kanban) com todas as issues, organizadas por status. |
| **Team Capacity**  | Quadro com agrupamento por colaborador e distribuição das issues por prioridade. |
| **Current Iteration** | Mostra somente as issues da iteração atual, agrupadas por prioridade. |
| **Roadmap**        | Linha do tempo baseada nas datas das iterações. Útil para planejamento macro. |
| **In Review**      | Exibe apenas as issues em revisão com os respectivos PRs. |
| **My Items**       | Cada membro visualiza suas próprias issues com todos os campos relevantes. |

### Fluxo de Issues

As colunas padrão do quadro são:

1. **To Do** → Atividades planejadas  
2. **In Progress** → Atividades em execução  
3. **In Review** → Atividades concluídas, aguardando validação  
4. **Done** → Atividades encerradas  

> 🔔 Sempre associe a issue à macroentrega correspondente.

### Campos para Organização das Issues

Para garantir rastreabilidade e organização nas entregas, recomendamos preencher os seguintes campos em cada issue do projeto:

#### Campos Personalizados (Recomendados)

- **Prioridade**: Define o nível de urgência (`Alta`, `Média`, `Baixa`)..
- **Iteração**: Ciclo semanal em que a atividade será realizada.
- **Squad**: Time responsável pela atividade (ex: `Frontend`, `Backend`, `Documentação`, `CI/CD`).
- **Data de Início**: Data que a atividade foi iniciada.
- **Data de Fim**: Data de conclusão da atividade.

> 🔔 Esses campos permitem alimentar visualizações como **Roadmap**, **Current Iteration** e **Team Capacity** com mais precisão.

#### Campos Padrão (Obrigatórios)

Estes campos são obrigatórios para organização mínima do projeto:

- **Assignee**: Pessoa responsável pela execução da issue.
- **Milestone**: Macroentrega ou marco ao qual a atividade está relacionada. 

> 🔔 Consulte [macroentregas.md](./macroentregas.md) para saber como criar e utilizar milestones.

### Automatizações

O quadro utiliza automações que facilitam o acompanhamento do fluxo de trabalho. Entre as principais:

- Ao **fechar um Pull Request vinculado a uma issue**, o card da issue é automaticamente movido para a coluna **Done**.

Essa automação depende de o PR estar corretamente vinculado à issue por meio do campo _Development_. É responsabilidade do **membro do squad** realizar o vínculo da issue ao Pull Request.

> 🔔 Recomendamos que a **Coordenação Técnica sempre reforce essa prática com o time**, especialmente durante o onboarding ou revisões semanais. O vínculo correto permite rastreabilidade entre código e planejamento, além de acionar as automações do GitHub Projects de forma adequada.

## Acesse o Template Oficial

Para visualizar a estrutura do board oficial utilizado pelo CEIA, acesse:

[Template Público - GitHub Projects (AKCIT-Geral)](https://github.com/orgs/AKCIT-Geral/projects/5)


