---
title: Análise das Tarefas
parent: Análise de Requisitos
has_children: false
nav_order: 3
---

# Análise das Tarefas

## Metodologia: Card, Moran and Newell GOMS (CMN-GOMS)

O método utilizado para analisarmos as tarefas será o CMN-GOMS, que define uma sintaxe padronizada onde há uma única hierarquia estrita de objetivos, as operações são executadas forma sequencial e os métodos são representados em uma notação semelhante a pseudocódigo.

## Tarefa 1: Acessar as informações sobre os casos de COVID-19 na cidade

``` 
GOAL 0: Acessar informações sobre caso de COVID-19
    GOAL 1: Acessar Portal da Transparência
        METHOD 1.A: Clicar no botão "Portal da transparência"
        (SEL. RULE: o botão está visivel e de fácil acesso) 
        METHOD 1.B: Clicar no link "Cidadão" em baixo da aba serviços
        (SEL. RULE: o botão "Portal da transparência" não está visível ou o botão "Cidadão" está mais fácil de visualizar)
            OP 1.A.1: girar a roda do mouse até encontrar o link "Portal da Transparência"
            OP 1.A.2: clicar no botão "Portal da Transparência"
    GOAL 2: Acessar o Painel COVID
        OP 2.1: Clicar no botão Painel COVID
``` 

## Tarefa 2 - Acessar as principais notícias

```
GOAL 0: Acessar as notícias do site
    OP 0.1: girar a roda do mouse até encontrar o link "Todas as notícias"
    OP 0.2: clicar no link "Todas as notícias"
```

## Tarefa 3 - Obter informações sobre Programas Sociais

```
GOAL 0: Obter informações sobre programas sociais
    GOAL 1: Acessar a aba "Cidadão"
        OP 1.1: clicar no link "Cidadão" na aba "Serviços"
    GOAL 2: Acessar a parte de Programas Sociais
        OP 2.1: girar a roda do mouse até encontrar o link "Cadastro Único para Programas Sociais"
        OP 2.2: clicar no link "Cadastro Único para Programas Sociais"
```

