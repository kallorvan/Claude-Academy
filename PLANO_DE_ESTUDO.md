# Plano de estudo: Claude Code

Roteiro do básico ao avançado, em quatro etapas. Cada etapa tem objetivos, cursos da Claude Academy (em inglês) e um exercício prático para fixar o conteúdo.

## Etapa 1: Fundamentos (dias 1 a 3)

**Objetivos**
- Entender o que é um agente de código e como o Claude Code difere de um chat.
- Instalar e rodar o Claude Code no terminal.
- Conhecer o loop agêntico, a janela de contexto e o sistema de permissões.

**Leitura e vídeos**
- [Claude Code 101](https://academy.claude.com/courses/claude-code-101): começar pelas lições “What is Claude Code?” e “Installing Claude Code”.

**Exercício**
1. Instalar o Claude Code e rodar `claude` dentro deste repositório.
2. Pedir para ele explicar a estrutura do projeto.
3. Rodar `/init` e comparar o resultado com este `CLAUDE.md`.

**Pronto quando:** você consegue explicar a diferença entre modo manual, auto-accept e Plan Mode.

## Etapa 2: Uso diário (dias 4 a 8)

**Objetivos**
- Usar o fluxo Explorar → Planejar → Codar → Commitar.
- Controlar o contexto com `/compact`, `/clear` e `/context`.
- Escrever um CLAUDE.md útil e curto.

**Leitura e vídeos**
- [Claude Code 101](https://academy.claude.com/courses/claude-code-101): lições sobre prompts, Plan Mode, contexto e CLAUDE.md.
- [Claude Code plan mode como ponto de partida](https://academy.claude.com/courses/ai-native-sdlc-playbook/plan-mode).

**Exercício**
1. Criar uma pequena funcionalidade ou script (ex.: uma função utilitária) usando Plan Mode antes de editar.
2. Anotar, no CLAUDE.md, um comando ou convenção que o Claude errou e corrigir a instrução.

**Pronto quando:** você sabe quando usar `/clear` em vez de `/compact` e consegue justificar a escolha.

## Etapa 3: Extensibilidade (dias 9 a 15)

**Objetivos**
- Criar subagentes para delegar tarefas sem sujar o contexto principal.
- Conectar fontes externas com MCP.
- Automatizar comportamentos com hooks.
- Entender quando usar skills, subagentes, hooks ou CLAUDE.md.

**Leitura e vídeos**
- [Claude Code 101](https://academy.claude.com/courses/claude-code-101): subagentes, MCP e hooks.
- [Skills vs. other Claude Code features](https://academy.claude.com/tutorials/how-skills-compare-to-other-claude-code-features).
- [Skills vs. other Claude Code features (lição)](https://academy.claude.com/courses/introduction-to-agent-skills/skills-vs-other-claude-code-features).

**Exercício**
1. Criar um hook que impeça comandos destrutivos (ex.: `rm -rf`) ou que formate arquivos após editar.
2. Criar um subagente de revisão com instruções próprias e usá-lo em uma mudança real.

**Pronto quando:** você consegue decidir, para um problema novo, qual dos quatro mecanismos usar e explicar o motivo.

## Etapa 4: Avançado (dias 16 a 30)

**Objetivos**
- Rodar sessões longas e sem supervisão com segurança.
- Usar o modo headless em scripts e pipelines de CI.
- Agendar tarefas recorrentes e integrar com pull requests.
- Empacotar uma configuração como plugin para o time.

**Leitura e vídeos**
- [Claude Code in action](https://academy.claude.com/courses/claude-code-in-action): planejamento, configuração, automação e verificação.
- [Using Claude Code Remote Control](https://academy.claude.com/tutorials/using-claude-code-remote-control).
- [How to use the Nextflow Deployment agent skill with Claude Code](https://academy.claude.com/tutorials/how-to-use-the-nextflow-deployment-agent-skill-with-claude-code) e [FHIR Developer agent skill](https://academy.claude.com/tutorials/how-to-use-the-fhir-developer-agent-skill-with-claude-code): exemplos de skills em domínios específicos.

**Exercício**
1. Rodar o Claude Code em modo headless em um script simples e capturar a saída.
2. Configurar uma rotina que roda em horário fixo e resume o estado do projeto.
3. Empacotar hooks, skills e CLAUDE.md em um plugin local e instalá-lo em outro projeto.

**Pronto quando:** você consegue automatizar um fluxo real de ponta a ponta e explicar quais verificações faz antes de confiar no resultado sem supervisão.

## Recursos complementares

- Cursos listados acima, na Claude Academy: https://academy.claude.com
- Documentação oficial do Claude Code: https://code.claude.com/docs

## Como acompanhar

Marque cada exercício concluído nesta lista e registre, em uma linha, o que aprendeu ou o que travou:

- [ ] Etapa 1: Fundamentos
- [ ] Etapa 2: Uso diário
- [ ] Etapa 3: Extensibilidade
- [ ] Etapa 4: Avançado
