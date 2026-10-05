<!-- ELUCENIA technical documentation · controle-da-asma-gina · pt-BR · no clinical/professional/rights approval -->

# Controle dos sintomas da asma (GINA)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/controle-da-asma-gina)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Sintomas diurnos mais de 2 vezes por semana

`diurno`

### Algum despertar noturno por asma

`noturno`

### Uso de medicação de alívio (SABA) mais de 2 vezes por semana

`alivio`

### Alguma limitação de atividades pela asma

`limit`

## Edição do método

GINA estratégia 2021:controle sintomas 4 semanas,4 perguntas; alívio SABA; 0/1–2/3–4

## Fórmula documentada

Nas últimas 4 semanas, conte quantos itens estão presentes: sintomas diurnos \> 2×/semana; despertar noturno por asma; SABA de alívio \> 2×/semana (não conta o uso antes de exercício); limitação de atividades.

0 = bem controlada · 1 a 2 = parcialmente controlada · 3 a 4 = não controlada.

## Limites e população

A avaliação GINA 2021 aqui calculada cobre controle de sintomas nas últimas quatro semanas em adultos e crianças maiores de 5 anos, com a pergunta de alívio referente a SABA. Essa contagem não avalia todo o risco futuro de exacerbação, função pulmonar, comorbidades, técnica inalatória ou adesão. Controle sintomático e gravidade da asma não são equivalentes. A adaptação do material permanece sujeita às condições de direitos do titular.

## Referências

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
