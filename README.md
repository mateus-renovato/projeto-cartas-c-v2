# projeto-cartas-c-v2
Implementação em linguagem C de um jogo inspirado no Super Trunfo, com criação dinâmica de cartas baseadas em cidades brasileiras e sistema avançado de comparação de atributos em múltiplos níveis (Novato, Aventureiro e Mestre). O projeto aplica conceitos de programação estruturada, validação de entrada e cálculo de métricas derivadas.


Super Trunfo em C – Versão 2

Este projeto consiste na implementação de um jogo inspirado no clássico **Super Trunfo**, desenvolvido em linguagem C.  
A aplicação permite a criação de cartas baseadas em cidades, cálculo automático de métricas estatísticas e comparação de atributos em diferentes níveis de complexidade.

🎯 Objetivo

Desenvolver um sistema estruturado que permita:

- Criar cartas com informações de cidades
- Calcular métricas derivadas automaticamente
- Comparar cartas com base em diferentes atributos
- Implementar múltiplos níveis de comparação
- Aplicar validação de entrada de dados

🧠 Estrutura da Carta

Cada carta contém os seguintes atributos:

- Estado
- Código
- Cidade
- População
- Área
- PIB
- Pontos turísticos
- Densidade populacional
- PIB per capita
- Inverso da densidade
- Super Poder (atributo calculado)

⚙️ Funcionalidades Implementadas

🔹 Cálculo Automático de Métricas
O sistema calcula automaticamente:
- Densidade populacional
- PIB per capita
- Inverso da densidade
- Super Poder (soma estratégica dos atributos)

🔹 Níveis de Comparação

**Nível Novato**
- Comparação fixa baseada na densidade populacional
- Regra especial: menor densidade vence

**Nível Aventureiro**
- Usuário escolhe um atributo para comparação
- Sistema aplica automaticamente a regra (maior ou menor vence)

**Nível Mestre**
- Comparação de dois atributos diferentes
- Exibição do vencedor por atributo
- Soma dos atributos escolhidos
- Resultado final com base na soma total

### 🔹 Validação de Entrada
- Impede valores negativos
- Garante entradas numéricas válidas
- Controle de opções inválidas no menu

## 🛠 Tecnologias Utilizadas

- Linguagem C
- Biblioteca `stdio.h`
- Biblioteca `string.h`
- Biblioteca `stdbool.h`