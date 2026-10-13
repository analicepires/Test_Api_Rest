# 🔌 Testes de API REST com Postman e Pytest (TripleTen)

Testes manuais e automatizados dos endpoints de uma API, validando códigos de status, corpo das respostas e regras de negócio dos campos.

## 🎯 Objetivo
Verificar se a API aceita apenas dados válidos e retorna respostas e mensagens de erro corretas.

## 🚀 Tecnologias
Postman · Requests · JSON

## 🧪 Técnicas de teste
- **Classes de equivalência** e **valores-limite** (ex.: tamanho mínimo e máximo de um campo de texto)
- Testes **positivos** e **negativos** (campo vazio, tipo inválido, caracteres especiais, campo ausente)

## ✅ Exemplos de casos de teste
| # | Cenário | Esperado |
|---|---|---|
| 1 | Campo `name` com 1 caractere | 201 Created |
| 2 | Campo `name` com 15 caracteres (limite) | 201 Created |
| 3 | Campo `name` com 16 caracteres | 400 Bad Request |
| 4 | Campo `name` vazio | 400 Bad Request |
| 5 | Campo `name` com número em vez de texto | 400 Bad Request |

> Ajuste a tabela para os casos reais do seu projeto. Link para checklist/planilha completa: [link]

## 👩‍💻 Autora
**Analice Pires**, Analista de QA · [LinkedIn](https://www.linkedin.com/in/analice-pires)
