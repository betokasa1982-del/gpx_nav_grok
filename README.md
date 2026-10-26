# GPX Navigator Grok

Revisão do GPX Navigator com os três fluxos corrigidos. O ícone (seta âmbar, anel teal, letra **G**) marca esta versão.

O repositório [gpx_nav_dev](https://github.com/betokasa1982-del/gpx_nav_dev) não foi alterado.

## O que o app faz

1. **Gravar e classificar.** Rec grava o ciclo e classifica nos cinco critérios VBC (paradas/km, velocidade média, velocidade em movimento, máxima, % parado) em Ci1–Ci3, Co1–Co2 ou LH1–LH2. Se houver um alvo escolhido antes, o cartão mostra o resultado contra esse alvo, à parte da classe em que o ciclo caiu.
2. **Repetir.** Load (ou o carregamento automático ao salvar) e START. A barra compara a volta atual com a classe da rota. Ao sair, o alerta diz se ficou dentro ou fora.
3. **Rotas sintéticas.** Aba SYNTH: ciclo de pista para comparar veículos. O GPS desse teste não entra na navegação da rota gravada.

## Como abrir

É um PWA de um arquivo. Abra `index.html` no navegador, ou:

```bash
node serve.mjs
```

Testes (Node):

```bash
node runner.js
```

## Ícone

`icon-192.png` e `icon-512.png` são o ícone desta revisão. O cache do service worker é `gpx-nav-v68-grok`, para o tablet não continuar com o ícone roxo DEV.
