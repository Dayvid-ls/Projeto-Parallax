# Projeto Parallax 🌊

Página web com efeito parallax que aborda os Direitos Humanos à Água e ao Saneamento (DHAS), destacando a importância do acesso à água potável e ao saneamento além do ambiente domiciliar.

## Tecnologias usadas
- HTML5
- CSS3 (efeito parallax, gradients, responsividade, flexbox)
- Imagens de fundo via Unsplash

## Funcionalidades
- Efeito parallax suave com `background-attachment: fixed`
- Três seções parallax com mensagens temáticas:
  - "Água e o Saneamento"
  - "Todos tem direito a água"
  - "Acessibilidade"
- Conteúdo textual informativo sobre direitos humanos, acesso à água, saneamento e higiene
- Layout responsivo com largura máxima de 760px para o texto
- Gradiente escuro no final de cada seção parallax para melhor legibilidade do texto
- Rolagem natural entre seções

## Como executar
1. Baixe todos os arquivos na mesma pasta:
2. Abra o arquivo `index.html` em qualquer navegador moderno.

## Funcionalidades em detalhe

| Elemento | Descrição |
|----------|-----------|
| `.parallax` | Define altura de 100vh, fundo fixo (`background-attachment: fixed`), imagem centralizada e cobertura total (`background-size: cover`) |
| `.parallax:after` | Pseudo-elemento que adiciona um gradiente linear (transparente → preto) para escurecer a parte inferior do texto, melhorando contraste |
| `.parallax-1`, `.parallax-2`, `.parallax-3` | Cada um com uma imagem de fundo diferente (Unsplash) |
| `.content` | Seções com fundo bege (`#ece7d5`), padding interno e texto alinhado |
| `.container` | Limita a largura do texto a 760px em telas grandes, com margem automática e padding lateral |
| `h1` no parallax | Texto centralizado, branco, tamanho 78px, uppercase, com `z-index` para ficar acima do gradiente |

## Efeito Parallax
O efeito é conseguido com a propriedade CSS:
```css
background-attachment: fixed;
