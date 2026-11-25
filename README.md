# cchooks ê¢â¬â Hooks do Claude Code

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso web **self-contained** (HTML + fontes CDN + JS inline, sem build/backend, funciona em `file://`) inteiramente sobre **hooks do Claude Code**: dos fundamentos êÂ s travas de seguranêÂ§a, êÂ  automaêÂ§êÂ£o e ao uso em equipe/CI. Formato-curso ARCKHê **v4** ê¢â¬â dark editorial com movimento, leitura viva (uma ideia por seêÂ§êÂ£o + figura na margem) e uma camada de aprendizagem com retenêÂ§êÂ£o (progresso, marcar lido, teste-se, grifo ê¢â â flashcard, revisêÂ£o espaêÂ§ada, "pratique agora", "minha jornada").

## Estrutura

- `index.html` ê¢â¬â redireciona para a landing.
- `landing.html` ê¢â¬â porta do curso: hero + as 4 trilhas + mêÂ©todo.
- `curso.html` ê¢â¬â **Trilha 01 êÂ· Fundamentos** (5 aulas). PêÂ¡gina êÂºnica (roteamento por hash `#trilha`, `#aula-1`ê¢â¬Â¦), estado prêÂ³prio em `localStorage`.
- `curso-guardrails.html` ê¢â¬â **Trilha 02 êÂ· Guardrails** (4 aulas): travas de seguranêÂ§a.
- `curso-automacao.html` ê¢â¬â **Trilha 03 êÂ· AutomaêÂ§êÂ£o** (4 aulas): formatar, avisar, logar, injetar contexto.
- `curso-time.html` ê¢â¬â **Trilha 04 êÂ· Equipe & CI** (4 aulas): versionar, determinismo, headless, higiene.
- `assets/aula.css` ê¢â¬â design language v4 (tokens, temas dark/papel/sêÂ©pia, leitura + trilho + painêÂ©is).
- `assets/curso.js` ê¢â¬â motor da pêÂ¡gina êÂºnica (roteador, progresso, teste-se, grifo/flashcard, revisêÂ£o espaêÂ§ada, jornada, export/import).

Cada trilha êÂ© uma pêÂ¡gina v4 independente (estado isolado por `<meta name="curso">`); a subnav no topo cruza entre as trilhas.

## As trilhas

1. **Fundamentos** ê¢â¬â o que êÂ© um hook êÂ· os eventos do ciclo êÂ· `settings.json` êÂ· o que o hook recebe (JSON no stdin) êÂ· como responde (exit code + JSON).
2. **Guardrails** ê¢â¬â a ideia de trava (`exit 2`) êÂ· ler o comando êÂ· casos reais êÂ· allow/ask/deny + higiene.
3. **AutomaêÂ§êÂ£o** ê¢â¬â formatar ao salvar êÂ· avisar ao terminar êÂ· registrar comandos êÂ· injetar contexto.
4. **Equipe & CI** ê¢â¬â versionar pro time êÂ· determinismo êÂ· rodar headless/pipeline êÂ· hook êÂ© poder (seguranêÂ§a).

## Publicado em

GitHub Pages: https://linnoff88-dev.github.io/

> ConteêÂºdo educativo sobre hooks do Claude Code ê¢â¬â no formato-curso ARCKHê v4.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>