# 🧮 Calculadora Interativa em Python

Este projeto faz parte do repositório de desenvolvimento em Python e consiste no desenvolvimento de uma calculadora interativa executada diretamente no terminal. O principal objetivo é permitir que o utilizador insira números, realize operações matemáticas e visualize os resultados de forma dinâmica, estilizada e intuitiva.

---

## 📁 Estrutura de Ficheiros e Evolução do Projeto

O projeto está dividido em quatro módulos principais, mostrando a evolução lógica e visual da aplicação:

### 1. `calculadora01.py` — Versão Básica (Menu e Operações Diretas)
* **Objetivo:** Estabelecer a estrutura inicial da calculadora com um menu de opções tradicionais.
* **Funcionalidades:** 
  * Menu interativo com as 4 operações básicas (Soma, Subtração, Multiplicação e Divisão).
  * Funções separadas para cada operação matemática.
  * Tratamento de erro básico para evitar divisão por zero.
  * Estrutura de repetição `while` para manter o programa ativo até que o utilizador escolha sair.

### 2. `calculadora02.py` — Versão Intermédia (Modo Contínuo / Infinito)
* **Objetivo:** Simular o comportamento de uma calculadora de bolso real com visor dinâmico.
* **Funcionalidades:**
  * Introdução de um visor gráfico desenhado no terminal (`exibir_teclado`).
  * Implementação de um fluxo de cálculo em cadeia (acumulador), permitindo realizar várias operações consecutivas sem reiniciar o programa.
  * Utilização do operador `=` para fechar a conta e exibir o resultado final acumulado.

### 3. `calculadora03.py` — Versão Avançada (Análise de Números: Par/Ímpar e Inteiro/Decimal)
* **Objetivo:** Expandir a calculadora para fornecer propriedades matemáticas adicionais sobre o resultado obtido.
* **Funcionalidades:**
  * Incorporação de funções lógicas auxiliares (`ehinteiro` e `ehpar`).
  * Análise em tempo real do resultado atual exibido no visor, informando automaticamente se o número é **Par ou Ímpar** e se é **Inteiro ou Decimal**.
  * Manutenção do design estruturado e alinhado por largura fixa de caracteres (`LARGURA = 28`).

### 4. `cores.py` — Módulo de Estilização ANSI
* **Objetivo:** Centralizar a paleta de cores e estilos visuais do terminal.
* **Funcionalidades:**
  * Códigos ANSI para cores de texto (foreground) normais e brilhantes.
  * Códigos para cores de fundo (background).
  * Estilos de texto como negrito, itálico e sublinhado.
  * Bloco de demonstração interativa para pré-visualização das cores no terminal.

---

## 🚀 Como Executar o Projeto

1. Certifica-te de que tens o **Python** instalado no teu computador.
2. Abre a pasta do projeto no **VS Code**.
3. No terminal integrado, navega até à pasta da calculadora e executa o ficheiro pretendido:
   ```bash
   python calculadora03.py
