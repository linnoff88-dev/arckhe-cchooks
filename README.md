# cchooks â€” Hooks do Claude Code

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso web **self-contained** (HTML + fontes CDN + JS inline, sem build/backend, funciona em `file://`) inteiramente sobre **hooks do Claude Code**: dos fundamentos Ã s travas de seguranÃ§a, Ã  automaÃ§Ã£o e ao uso em equipe/CI. Formato-curso INEMA **v4** â€” dark editorial com movimento, leitura viva (uma ideia por seÃ§Ã£o + figura na margem) e uma camada de aprendizagem com retenÃ§Ã£o (progresso, marcar lido, teste-se, grifo â†’ flashcard, revisÃ£o espaÃ§ada, "pratique agora", "minha jornada").

## Estrutura

- `index.html` â€” redireciona para a landing.
- `landing.html` â€” porta do curso: hero + as 4 trilhas + mÃ©todo.
- `curso.html` â€” **Trilha 01 Â· Fundamentos** (5 aulas). PÃ¡gina Ãºnica (roteamento por hash `#trilha`, `#aula-1`â€¦), estado prÃ³prio em `localStorage`.
- `curso-guardrails.html` â€” **Trilha 02 Â· Guardrails** (4 aulas): travas de seguranÃ§a.
- `curso-automacao.html` â€” **Trilha 03 Â· AutomaÃ§Ã£o** (4 aulas): formatar, avisar, logar, injetar contexto.
- `curso-time.html` â€” **Trilha 04 Â· Equipe & CI** (4 aulas): versionar, determinismo, headless, higiene.
- `assets/aula.css` â€” design language v4 (tokens, temas dark/papel/sÃ©pia, leitura + trilho + painÃ©is).
- `assets/curso.js` â€” motor da pÃ¡gina Ãºnica (roteador, progresso, teste-se, grifo/flashcard, revisÃ£o espaÃ§ada, jornada, export/import).

Cada trilha Ã© uma pÃ¡gina v4 independente (estado isolado por `<meta name="curso">`); a subnav no topo cruza entre as trilhas.

## As trilhas

1. **Fundamentos** â€” o que Ã© um hook Â· os eventos do ciclo Â· `settings.json` Â· o que o hook recebe (JSON no stdin) Â· como responde (exit code + JSON).
2. **Guardrails** â€” a ideia de trava (`exit 2`) Â· ler o comando Â· casos reais Â· allow/ask/deny + higiene.
3. **AutomaÃ§Ã£o** â€” formatar ao salvar Â· avisar ao terminar Â· registrar comandos Â· injetar contexto.
4. **Equipe & CI** â€” versionar pro time Â· determinismo Â· rodar headless/pipeline Â· hook Ã© poder (seguranÃ§a).

## Publicado em

GitHub Pages: https://inematds.github.io/cchooks/

> ConteÃºdo educativo sobre hooks do Claude Code â€” no formato-curso INEMA v4.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>