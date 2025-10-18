# resolvedor-sudoku-csp
# 🧩 Resolvedor de Sudoku: Abordagem de Programação por Restrições (CSP)

## 💻 Visão Geral do Projeto

Este projeto implementa um resolvedor de Sudoku eficiente, utilizando conceitos de Inteligência Artificial, especificamente a **Programação por Restrições (Constraint Satisfaction Problem - CSP)**. O objetivo é demonstrar a capacidade de modelar um problema combinatorial clássico e resolvê-lo utilizando técnicas avançadas de busca e inferência.

## ✨ Tecnologias e Algoritmos

* **Linguagem:** Python
* **Modelo de IA:** Programação por Restrições (CSP)
* **Algoritmos de Resolução:**
    * **Backtracking Search:** O algoritmo de busca fundamental para explorar o espaço de estados.
    * **Inclusão de Heurísticas:** Utilização de heurísticas para aumentar a eficiência da busca (ex: **MRV - Minimum Remaining Values** para seleção de variáveis).
    * **Técnicas de Poda (Pruning):** Implementação de técnicas de inferência, como [ARCO-CONSISTÊNCIA / FORWARD CHECKING], para reduzir o domínio das variáveis e evitar buscas desnecessárias.

## 🚀 Como Testar (Executando no Colab)

O projeto foi desenvolvido para ser executado diretamente no Google Colab, garantindo a reprodutibilidade.

1.  **Acesse o Notebook:** Clique no arquivo `Sudoku.ipynb` neste repositório.
2.  **Abra no Colab:** Clique no ícone do Google Colab no topo do notebook.
3.  **Execute as Células:** Execute todas as células do notebook em sequência (Runtime -> Run all / Tempo de Execução -> Executar tudo).
4.  **Entrada:** O notebook contém uma grade de Sudoku inicial (pode ser modificada na célula de entrada).
5.  **Saída:** A solução será impressa, mostrando o tempo de processamento e a grade final resolvida.

## 🧠 Exemplo de Resultado

| Posição (Variável) | Restrições (Constraints) |
| :--- | :--- |
| Célula `(r, c)` | O valor deve ser único na Linha, Coluna e Bloco 3x3. |

