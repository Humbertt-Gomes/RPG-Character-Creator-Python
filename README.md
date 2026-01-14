# Gerador de Ficha de Personagem RPG

Este é um projeto interativo desenvolvido em **Python** focado em lógica de programação, validação de dados e interface via linha de comando (CLI). O objetivo é criar fichas de personagens de RPG com uma visualização estética e organizada.

##  Funcionalidades

* **Validação de Entrada:** O sistema impede nomes vazios, caracteres numéricos no nome e limita o tamanho do texto para manter a interface limpa.
* **Tratamento de Exceções:** Implementação de `try/except` para lidar com entradas de dados inválidas nos atributos, evitando o fechamento inesperado do programa.
* **Interface Visual:** Exibição dos atributos (Força, Magia, Inteligência e Carisma) através de barras de progresso estilizadas (`●●●○○○○○○○`).
* **Fluxo de Controle:** Uso de funções modulares e loops aninhados para permitir múltiplas criações sem reiniciar o script.

##  Tecnologias

* **Linguagem:** Python 3.x
* **Conceitos aplicados:** Funções, Loops (`while`), Condicionais (`if/else`), Manipulação de Strings e Tratamento de Erros.

##  Exemplo de Saída

```text
SEU PERSONAGEM:
Arthur Silva
FORÇA         ●●●●●●●○○○
MAGIA         ●●●●●○○○○○
INTELIGENCIA  ●●●●●●●●○○
CARISMA       ●●●●●●○○○○
```

##  Como usar

1.  Certifique-se de ter o Python instalado em sua máquina.
2.  Clone este repositório.
3.  Execute o arquivo principal:
    ```bash
    python personagem_RPG.py
    ```

## Testar Online

Se você não tem o Python instalado, pode executar o código diretamente no seu navegador através do Google Colab:

[Clique aqui para rodar o projeto online] ( https://colab.research.google.com/drive/1NEaBobj-DJYV4jPF2zSD9AFwHTmwJ-Js?usp=sharing )
