# Padrão de Commits Semânticos 💣

Repositório para concentrar as informações de padrões de mensagens em commits, branchs, issues.

Essas informações são recomendações mínimas a serem usadas nos commits.

---
  
#### Utilize o seguinte formato para padronizar as mensagens de commit 📝:

~~~ 
<tipo>[escopo opcional]: <descrição curta>
[corpo opcional]
[rodapé(s) opcional(is)]
~~~

### Tipos Comuns 📌
- `feat`: Nova funcionalidade.
- `fix`: Correção de bug. 
- `docs`: Alterações na documentação.
- `style`: Alterações que não afetam a lógica (formatação, espaços, etc). 
- `refactor`: Alterações no código que não adicionam funcionalidades nem corrigem bugs. 
- `perf`: Melhorias de performance. 
- `test`: Adição ou correção de testes. 
- `chore`: Atualizações em tarefas de manutenção (build, configurações, etc).
- `build`: Alteração em arquivos de build e dependências.
- `env`: Modificações em arquivos de configurações, containers e CI.

### Exemplos:
- `feat(auth): adicionar endpoint de login`
- `fix(api): corrigir erro no endpoint de consulta`
- `docs: atualizar README com instruções de deploy`
- `refactor(payment): refatorar lógica de cálculo de juros`

### Dicas Adicionais 🎉
- **Mensagem Concisa e Descritiva**: A linha de título deve ter até 72 caracteres e ser escrita no imperativo.
- **Corpo da Mensagem (opcional)**: Use uma linha em branco após o título e inclua mais detalhes se necessário.
- **Referência de Issues**: Se o commit resolver ou estiver relacionado a uma issue, adicione Closes #número ou Refs #número.

## Criação e Nomeação de Branches 🔀

Padronize o nome das branches para facilitar a organização e a comunicação.

### Formato:

~~~
<tipo>/<ID da issue opcional>-<nome-descritivo>
~~~

### Tipos de Branches 📌
- `feature`: Para novas funcionalidades.
- `bugfix`: Para correção de bugs.
- `hotfix`: Para correções urgentes em produção.
- `release`: Para preparações de release (versões de pré-produção).

### Exemplos:
- `feature/123-login-usuario` (Branch para desenvolver a funcionalidade de login vinculada à issue #123.)
- `bugfix/456-corrigir-endpoint-consulta`
- `hotfix/789-corrigir-falha-producao`

### Dicas Adicionais 🎉
- **ID da Issue**: Incluir o número da issue para facilitar o rastreamento.
- **Nome Descritivo**: Usar nomes que resumam a finalidade da branch, evitando abreviações excessivas.

---

## Documentação de Issues e Ações 📋


**Template para Issues:**

Utilize templates padronizados para manter consistência na abertura e resolução de issues.

~~~markdown
### Título da Issue
Breve descrição do problema ou funcionalidade.

---

**Descrição:**
Descreva o problema ou a nova funcionalidade de forma detalhada.

**Passos para Reproduzir (se aplicável):**
1. Passo 1
2. Passo 2
3. Passo 3

**Comportamento Esperado:**
Descreva o que deveria ocorrer.

**Comportamento Atual:**
Descreva o que está ocorrendo atualmente.

**Ambiente:**
- Sistema operacional:
- Versão da aplicação:

**Anexos:**
(Imagens, logs ou outros arquivos que ajudem na compreensão do problema)

**Referências:**
- Issue relacionada: #[número]
~~~

**Template para Ações/Tarefas:**

Ao documentar ações em issues ou pull requests, considere incluir checklists para rastreamento do progresso:
~~~markdown
### Tarefa: [Descrição da Tarefa]

**Objetivo:**  
Descrever brevemente o objetivo da tarefa.

**Checklist:**
- [X] Analisar requisitos
- [ ] Desenvolver a funcionalidade
- [ ] Realizar testes unitários e integrados
- [ ] Atualizar documentação (se necessário)
- [ ] Revisão de código

**Notas Adicionais:**
Coloque aqui observações relevantes, dependências ou links úteis.
~~~

