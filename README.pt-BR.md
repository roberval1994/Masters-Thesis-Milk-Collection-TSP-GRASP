# Otimização na Cadeia Produtiva da Agricultura Familiar (Pesquisa de Mestrado)

**Uma variante do PCV com Coleta de Prêmios para logística de coleta de leite, resolvida com GRASP + 2-opt**

🌐 **Idioma / Language:** **Português** | [English](README.md)

---

[![Java](https://img.shields.io/badge/Java-007396.svg?logo=openjdk&logoColor=white)](https://www.java.com/)
[![Metaheuristic](https://img.shields.io/badge/Metaheuristica-GRASP%20%2B%202--opt-orange.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Visão geral

Este repositório contém a implementação desenvolvida durante minha **pesquisa de Mestrado
em Ciência da Computação** (UERN/UFERSA, 2018–2020). Modela uma variante do
**Problema do Caixeiro Viajante com Coleta de Prêmios (PCVCP)** aplicada à **logística de
coleta de leite** de pequenos produtores da agricultura familiar, resolvida com a
metaheurística **GRASP** refinada por busca local **2-opt**.

> Projeto de pesquisa acadêmica. Preservado e documentado como parte do meu portfólio de
> Pesquisa Operacional.

## Problema

O leite precisa ser coletado de pequenos produtores dispersos, sob considerações de custo
e capacidade, onde visitar cada produtor gera um "prêmio" mas implica custo de
deslocamento. O objetivo equilibra o prêmio coletado contra o custo de roteirização — um
PCV com Coleta de Prêmios.

## Metodologia

- **Fase construtiva:** construção gulosa randomizada (GRASP).
- **Busca local:** melhoria das rotas por 2-opt.
- **Experimentos:** instâncias reais e sintéticas.

## Estrutura do projeto

```
.
├── src/br/com/uern/projeto/   # Código-fonte Java
├── bin/                       # Classes compiladas
└── doc/                       # Documentação
```

## Compilar & executar

```bash
git clone https://github.com/roberval1994/Masters-Thesis-Milk-Collection-TSP-GRASP.git
cd Masters-Thesis-Milk-Collection-TSP-GRASP

# Compilar
javac -d bin src/br/com/uern/projeto/*.java
# Executar (ajuste o nome da classe principal conforme necessário)
java -cp bin br.com.uern.projeto.Main
```

## Tecnologias

`Java` · `GRASP` · `2-opt` · `PCV com Coleta de Prêmios`

## Autor

**Roberval Gonçalves Moreira Filho** — Cientista de Dados | Analista de Pesquisa Operacional
Mestre em Ciência da Computação, UERN/UFERSA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-robervalOr-blue)](https://www.linkedin.com/in/robervalOr)
[![GitHub](https://img.shields.io/badge/GitHub-roberval1994-black)](https://github.com/roberval1994)

## Licença

Distribuído sob a Licença MIT. Veja [LICENSE](LICENSE).
