# Document AI Analyzer

## Descricao

Ferramenta conceitual para extracao, classificacao e analise automatizada de documentos usando OCR, NLP e LLMs.

## Problema que Resolve

Editais, contratos, relatorios tecnicos e artigos frequentemente contem informacoes importantes, mas a leitura manual consome tempo, aumenta risco de erro e dificulta comparacoes entre documentos.

## Para Quem Gera Valor

- Consultorias e escritorios de projetos
- Equipes de captacao de recursos
- Instituicoes de pesquisa e inovacao
- Empresas que analisam contratos, editais e relatorios
- Organizacoes publicas e sociais que lidam com documentacao recorrente

## Solucao Proposta

Criar um fluxo para receber documentos, extrair metadados, classificar o tipo de documento, identificar temas principais, mapear prazos e gerar uma sintese operacional para tomada de decisao.

## Tecnologias e Metodos

- Python
- OCR
- NLP
- LLMs
- RAG
- PDF processing
- Classificacao textual
- Extracao de entidades e metadados

## Estrutura do Projeto

```text
data/       exemplos sinteticos de documentos
notebooks/  demonstracao de classificacao e extracao
prompts/    modelos de prompts para analise assistida
src/        pipeline futuro de processamento documental
```

## Como Executar

```sh
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/document-ai-demo.ipynb
```

## Resultados e Aprendizados

- Classificacao automatizada por tipo de documento
- Extracao de prazos, entidades e temas
- Reducao de tempo em triagem documental
- Base para integracao com sistemas de gestao de projetos

## Resultado Demonstrativo

Com os dados sinteticos em `data/documentos_exemplo.csv`, o notebook prioriza documentos para triagem assistida por IA.

| Documento | Tipo | Prioridade |
| --- | --- | ---: |
| Termo de Referencia PMO | termo_referencia | 60 |
| Contrato Parceria Tecnologica | contrato | 50 |
| Edital Inovacao Industria 2026 | edital | 40 |
| Relatorio Sustentabilidade Textil | relatorio | 20 |
| Artigo DPP Cadeia Textil | artigo | 10 |

## Autor

Rodrigo Willemann  
Email: rodrigo.willemann@gmail.com

