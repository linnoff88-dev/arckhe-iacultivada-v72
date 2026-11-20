# IA Cultivada â€” curso (INEMA Learning v7.2)

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


ðŸ‡§ðŸ‡· [PortuguÃªs](https://inematds.github.io/iacultivada-v72/) Â· ðŸ‡ºðŸ‡¸ [English](https://inematds.github.io/iacultivada-v72/en/) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](https://inematds.github.io/iacultivada-v72/es/)

[![IA Cultivada](assets/img/capa.jpg)](https://inematds.github.io/iacultivada-v72/)

VersÃ£o em curso do projeto [IA Cultivada](https://inematds.github.io/iacultivada/) ("nÃ£o se programa, se cultiva"). O projeto original continua no ar com os capÃ­tulos, kits, gerador, diagnÃ³stico, skills e o vÃ­deo; este curso organiza o mesmo conteÃºdo em 8 aulas com diagrama clicÃ¡vel, prÃ¡tica com "pronto quando", teste comentado e um plano datado no fim.

## As aulas

| # | Aula | PrÃ¡tica |
|---|---|---|
| 1 | A semente e o jardim: por que IA se cultiva | diagnÃ³stico de maturidade |
| 2 | Os oito elementos e os cinco arquivos que cultivam | ficha do agente e a pasta com os 5 arquivos |
| 3 | A escada de maturidade: o que Ã© e o que nÃ£o Ã© IA cultivada | classificar 3 IAs que vocÃª usa |
| 4 | Primeiro jardim: a vida pessoal | Sobre mim, 3 regras e a 1Âª revisÃ£o semanal |
| 5 | Segundo jardim: o seu Jarvis | arquivo-mestre, diÃ¡rio de falhas e runbook |
| 6 | Fechar o ciclo: diÃ¡rio de falhas e observabilidade | uma semana de registro e a 1Âª regra nascida de erro |
| 7 | Autonomia por evidÃªncia, nÃ£o por confianÃ§a | critÃ©rio de promoÃ§Ã£o + conversa simulada |
| 8 | Terceiro jardim: a empresa, e o seu plano | plano datado (.md + .ics) |

## O que mudou em relaÃ§Ã£o ao projeto

- NÃ­veis de autonomia unificados em quatro (os capÃ­tulos de vida pessoal e Jarvis usavam trÃªs passos).
- Os 14 capÃ­tulos viraram 8 aulas com prÃ¡tica verificÃ¡vel e teste comentado.
- ComparaÃ§Ãµes (88% â†’ 95%, Empresa A Ã— B, 5 â†’ 14 regras) viraram diagramas clicÃ¡veis.
- Conversa simulada para treinar a decisÃ£o de autonomia com um diretor apressado.

## Como editar

ConteÃºdo em `conteudo/<lang>/` (JSON). Nunca editar o HTML gerado:

```bash
python3 gerar.py && python3 gerar.py --lang en && python3 gerar.py --lang es
python3 validar.py --links
```

## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/328-ia-cultivada-curso-em-8-aulas-faca-o-seu-agente-melhorar-a-cada-semana/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)

ConteÃºdo educacional aberto e gratuito do [INEMA.CLUB](https://inema.club).

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>