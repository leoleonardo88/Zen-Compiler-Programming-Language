# 🌌 Zen Programming Language (v1.0)
**Desenvolvida por LZ GAMES OFC**

A **Zen** é uma linguagem de programação focada em simplicidade, performance e integração nativa com o Windows. Criada do zero por **leoleonardo8362**, ela traduz lógica de alto nível para C++, gerando executáveis (.exe) rápidos e leves.

---

## 🚀 Diferenciais da Zen
- **Compilação Global:** Funciona direto no CMD, PowerShell, MSYS2 e VS Code.
- **Sintaxe Zenith IA:** Comandos nativos para criar interações inteligentes e árvores de decisão (`if`).
- **Visual Terminal:** Controle total de cores e interface via comandos simples como `cor()` e `limpar()`.
- **Arquitetura Multi-Estágio:** Processamento dividido em Syntax, Conflict, Linker e Accept.

---

## 🛠️ Comandos Oficiais (v1.0)

| Comando | Descrição |
| :--- | :--- |
| `void main() ( ... )` | Estrutura principal do código. |
| `texto("mensagem");` | Exibe um texto no console. |
| `cor(azul/verde);` | Altera a cor do terminal. |
| `limpar();` | Limpa todo o rastro do console. |
| `resposta.ia("pergunta");` | Captura entrada do usuário com prefixo de IA. |
| `if resposta == "valor" ( )` | Lógica de decisão baseada na última resposta. |
| `esperar();` | Pausa a execução até uma tecla ser pressionada. |
| `fim void();` | Finaliza o bloco principal com segurança. |

---

## 📦 Como Instalar (Jeito Raiz)

1. Baixe o arquivo **`Zen_Lang_v1.0.zip`** nos [Releases](link-da-aba-releases).
2. Extraia o conteúdo em uma pasta (ex: `C:\ZenLang`).
3. Adicione o caminho da pasta `bin` às **Variáveis de Ambiente (PATH)** do seu Windows.
4. Abra qualquer terminal e digite `zen` para começar a criar!

---

## 📝 Exemplo de Código (`terra.zen`)

```zen
void main() (
    cor(azul);
    limpar();
    texto("SISTEMA ZENITH IA ATIVO");
    resposta.ia("Qual o tamanho da Terra?");
    
    if resposta == "Não sei" (
        cor(verde);
        print("Estude!!");
    )
    
    esperar();
    fim void();
)
