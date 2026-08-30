# Fundamentos

App pessoal de treino cognitivo. Um arquivo HTML, sem build, sem dependência, sem servidor. Abre e usa.

Não é curso e não é anotação. O app pergunta, você responde, e ele devolve leitura do que você escreveu — tratando erro como dado, não como nota.

## Como usar

**No navegador:** abre o `index.html`. Só isso.

**No celular:** baixa o arquivo e abre pelo navegador. No iPhone dá pra adicionar à tela de início pelo Safari (Compartilhar → Adicionar à Tela de Início) e ele abre como app.

O progresso salva sozinho no navegador (`localStorage`). Não sobe nada pra lugar nenhum — os dados ficam no aparelho.

## O que tem dentro

| Módulo | O que faz |
|---|---|
| **Crença** | Quatro trilhas de perguntas (Musk, Branson, Naval, Ferriss) que quebram uma crença até o átomo |
| **Fundação** | 20 átomos de matemática e física, cada um feito dos anteriores |
| **Gente** | Persuasão aplicada — teoria em uma frase, missão de campo, feedback, ajuste |
| **Fala** | Vocabulário e moldes de frase por dedução: a palavra em uso, você deduz o sentido e constrói a sua |
| **Sozinho** | A escada de 6 degraus pra destrinchar qualquer assunto sem depender de ninguém |
| **Meu mapa** | Tudo que está aberto num lugar só: missões, âncoras, ajustes, frases, cadeias |

## A moldura

Todo módulo roda o mesmo ciclo, desenhado no topo de cada tela:

```
1 ação  →  2 dado  →  3 ajuste  →  4 de novo
```

Erro não é nota, é a peça que faltava. Depois de 10 unidades fechadas as legendas somem sozinhas — o andaime sai quando você já segura o peso.

## Âncoras físicas

Toda peça fechada pede um objeto do espaço ou um gesto do corpo pra carregar aquilo. As âncoras ficam listadas no Meu mapa. Passar por elas uma vez por dia, tocando e falando em voz alta, vale mais que uma sessão longa por semana.

## Estrutura

```
index.html    o app inteiro — HTML, CSS e JS num arquivo só
```

## Backup

Dentro do app, em Plano do dia, tem a opção de copiar tudo em Markdown. Serve como backup manual e como registro fora do navegador.

## Licença

MIT — ver [LICENSE](LICENSE).
