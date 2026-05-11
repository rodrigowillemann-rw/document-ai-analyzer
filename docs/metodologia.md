# Metodologia

A priorizacao sintetica combina complexidade documental e urgencia de prazo.

## Criterios

- Complexidade baixa: peso 1
- Complexidade media: peso 2
- Complexidade alta: peso 3
- Prazo ate 20 dias: bonus 30
- Prazo acima de 20 dias: bonus 10
- Sem prazo: bonus 0

## Formula

```text
prioridade = peso_complexidade * 10 + bonus_prazo
```

## Interpretacao

O resultado ajuda a ordenar uma fila de documentos para leitura automatizada, extracao de metadados e analise assistida por IA.
