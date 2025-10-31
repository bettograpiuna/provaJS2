# 🔁 Mestre dos Loops: while(true), for & for...of em Ação

**Que tal ver este projeto funcionando antes de ler a documentação?**

[![Testar Agora!](https://img.shields.io/badge/Testar%20Agora!-Clique%20Aqui-3498DB?style=for-the-badge)](https://bettograpiuna.github.io/provaJS2/)

---

## 🚀 Sobre o Projeto
Este pequeno script JavaScript é uma demonstração direta e didática de três estruturas de repetição (loops) fundamentais: `while(true)`, `for` e `for...of`.

O objetivo é ilustrar como cada loop se encaixa em uma fase diferente de um processo de dados: **Coleta, Indexação e Exibição**.

## ✨ Funcionalidades

| Loop | Propósito | Palavra-chave |
| :--- | :--- | :--- |
| **`while(true)`** | Coleta de dados com repetição infinita. | `break` para sair. |
| **`for`** | Processamento e exibição de dados com índices. | `i` (índiodo). |
| **`for...of`** | Iteração simples sobre os valores (sem índice) para exibição personalizada. | `item` (valor). |

## 🛠 Como Executar

Este projeto utiliza a função nativa `prompt()`, portanto, deve ser executado em um ambiente de navegador.

1.  **Salve:** Salve o código como um arquivo `.html` (ex: `index.html`).
2.  **Abra:** Abra o arquivo `index.html` em qualquer navegador (Chrome, Firefox, etc.).
3.  **Interaja:** A caixa de diálogo `prompt()` aparecerá. Siga as instruções no console (`F12`) e no prompt.

### 🛑 Palavra de Parada

Para encerrar a coleta de dados (o loop `while(true)`), digite: **`parar`** (ou clique em **Cancelar**).

## 📊 Saída Esperada (Console)

Após digitar os nomes e a palavra de parada, o console exibirá os resultados em duas etapas:

1.  **Listagem Indexada (Loop `for`):**
    ```
    1: NomeDigitado1
    2: NomeDigitado2
    ...
    ```
2.  **Mensagem Personalizada (Loop `for...of`):**
    ```
    Bem-vindo(a), NomeDigitado1!
    Bem-vindo(a), NomeDigitado2!
    ...
    ```
