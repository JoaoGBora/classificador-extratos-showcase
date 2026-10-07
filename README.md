# Classificador Automático de Extratos Bancários

> 🔒 Código privado (projeto corporativo). Esta página descreve o escopo e a lógica.

## Problema
Cada banco descreve as movimentações de um jeito diferente. Classificar centenas de linhas por semana em categorias gerenciais (custo, despesa fixa, impostos etc.) era manual e sujeito a erro.

## Solução
Motor em **Python** que lê os extratos e classifica cada movimentação em grupos gerenciais:
- Regras por banco, já que cada um tem seu padrão de descrição
- Conhecimento do negócio embutido nas regras (ex.: o que é custo da mercadoria e o que é despesa fixa)
- Validação de taxa de acerto por banco

## Resultado
Classificação validada em 100% para dois dos principais bancos, com o terceiro em fase final de ajuste.

## Tecnologias
Python · pandas · OFX/CSV
