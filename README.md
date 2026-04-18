# 💠 Zen Programming Language

![Zen Status](https://img.shields.io/badge/Language-Pre--Alpha-blueviolet?style=for-the-badge)
![Environment](https://img.shields.io/badge/Environment-MSYS2%20%2F%20UCRT64-006ced?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Zen** é uma linguagem de programação (Transpiler) de baixo nível, projetada para ser rápida, minimalista e eficiente. Criada originalmente para orquestrar sistemas de terminais customizados e lógica de motores voxel, o Zen traduz uma sintaxe simplificada diretamente para **C++ Moderno**.

---

## ⚡ Filosofia Zen

A linguagem foi construída sobre três pilares:
1. **Simplicidade Visual**: Menos ruído sintático, mais lógica.
2. **Performance Nativa**: Compilação direta para código máquina via `g++`.
3. **Portabilidade**: Gerenciamento de binários estáticos (`-onefile`).

---

## 🛠️ Estrutura da Linguagem

O ecossistema Zen é dividido em três partes fundamentais:

* **Zen Core (DLL)**: O motor de análise léxica e tradução.
* **Zen Compiler (CLI)**: A interface de linha de comando para o desenvolvedor.
* **Standard Lib**: Conjunto de funções pré-injetadas para manipulação de sistema e terminal.

---

## 💻 Exemplo de Sintaxe

O Zen utiliza um sistema de blocos por parênteses `( )`, unindo a estética de C com a limpeza de scripts modernos.

```python
// Exemplo de código v1.12
void main() (
    titulo("Meu Programa Zen")
    cor(verde)
    
    texto("Iniciando motor Zen...")
    
    definir player = "Leonardo"
    texto("Usuario logado: ")
    texto(player)
    
    esperar(1000)
    limpar()
)
