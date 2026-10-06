<!-- ELUCENIA technical documentation · escala-de-resultados-de-glasgow · pt-BR · no clinical/professional/rights approval -->

# Escala de Resultados de Glasgow (GOS)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-de-resultados-de-glasgow)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Situação do paciente

`gos`

- `1` — 1 – Óbito
- `2` — 2 – Estado vegetativo persistente: sem resposta com significado, ciclos de sono e vigília
- `3` — 3 – Incapacidade grave: consciente, mas depende de outra pessoa no dia a dia
- `4` — 4 – Incapacidade moderada: independente, mas com sequelas (pode usar transporte, trabalhar em ambiente protegido)
- `5` — 5 – Boa recuperação: retoma a vida normal, mesmo com déficits menores

## Edição do método

GOS/Jennett Bond 1975:5 categorias; favorável 4–5; sem GOSE 8 categorias

## Fórmula documentada

Escolha a categoria que melhor descreve o paciente. Nos estudos, o desfecho é geralmente dicotomizado em favorável (4 e 5) e desfavorável (1 a 3).

## Limites e população

Avalia desfecho funcional após lesão cerebral considerando incapacidade física e mental. Registre o tempo de seguimento e a edição de cinco categorias. A GOS não deve ser tratada como equivalente à GOSE de oito categorias ou como uma previsão a partir de dados de admissão.

## Referências

- [Jennett B, Bond M. Assessment of outcome after severe brain damage: a practical scale. Lancet, 1975.](https://doi.org/10.1016/S0140-6736(75)92830-5)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Incapacidade grave (desfecho desfavorável)


### 2

Incapacidade moderada (desfecho favorável)


### 3

Boa recuperação (desfecho favorável)

