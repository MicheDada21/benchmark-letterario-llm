# benchmark-letterario-llm

Misura le risposte di un LLM con e senza web su cultura letteraria, bibliografie, giudizio critico e riconoscimento degli errori.

Fa parte della [Prompt Library di CH Labs](https://www.cryptohelvetia.com/ch-labs/prompt-library), dove la pagina di riferimento è [Benchmark letterario LLM](https://www.cryptohelvetia.com/ch-labs/prompt-library/skills/benchmark-letterario-llm). Il repo contiene una copia della skill, rigenerata a ogni aggiornamento della libreria.

## Installare

In Claude Code aggiungi una volta il marketplace e installa il plugin.

```
/plugin marketplace add MicheDada21/ch-labs-skills
/plugin install benchmark-letterario-llm@ch-labs-skills
```

Da shell i comandi sono `claude plugin marketplace add MicheDada21/ch-labs-skills` e `claude plugin install benchmark-letterario-llm@ch-labs-skills`. Nell'app desktop premi + accanto al campo del prompt, apri Plugins, aggiungi il marketplace `MicheDada21/ch-labs-skills` con Add marketplace e poi il plugin con Add plugin.

Con altri agenti copia la cartella `skills/benchmark-letterario-llm` tra le skill dell'agente, per esempio in `~/.codex/skills/benchmark-letterario-llm`.

## Licenza

MIT, testo completo in [LICENSE](LICENSE).
