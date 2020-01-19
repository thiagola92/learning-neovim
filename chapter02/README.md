# Normal Mode
As teclas normais são guardadas para comandos muito utilizados durante o Vim (sair do Vim não é um deles :poop:)  

> Não se esqueça que Vim é sensível a caracter, `K` é diferente de `k`

## Move up, down, left and right
Mover se pelo editor de texto é essencial para o dia-a-dia e muitas vezes utilizamos o mouse para selecionar onde queremos ir do texto. Vim não conta com suporte para mouse para suas tarefas.  

> Nem sempre você vai ter suporte a mouse (boot de inicialização)

> Pessoas argumentam que é melhor desta maneira pois você não perde tempo tirando a mão do teclado

Muitos dos atalhos do Vim partiam do princípio que não se possuia mouse ou as teclas setas separadas ([Teclado original do Vim](vim_keyboard.jpg)). Por isto as teclas `h`, `j`, `k` e `l` eram utilizadas para se mover no texto. Hoje em dia essas teclas continuaram padrão mas as setas também fazem a mesma tarefa.   

| Atalho | Ação                      | Dica                                                   | Atalho 2  |
| ------ | ------------------------- | ------------------------------------------------------ | --------- |
| `h`    | Mover para esquerda       | A tecla mais na **esquerda**, move para a **esquerda** | `<left>`  |
| `j`    | Mover para baixo          |                                                        | `<down>`  |
| `k`    | Mover para cima           |                                                        | `<up>`    |
| `l`    | Mover para direita        | A tecla mais na **direita**, move para a **direita**   | `<right>` |

> Normalmente `<shift>` seria usado para ajudar a selecionar enquanto move, porém selecionar é algo exclusivo do **Visual Mode** pois `H`, `J`, `K` e `L` são atalhos para outros comandos. Com o surgimento de teclas extras como `<right>`, `<up>`, `<home>`, `<pg down>`... Foram incluidos comandos a elas com e sem o shift também.  

## Move word

| Atalho  | Ação                                      | Dica     | Atalho 2              |
| ------- | ----------------------------------------- | -------- | --------------------- |
| `w`     | Mover para o início da "palavra" seguinte | **w**ord | `<shift>` + `<right>` | 
| `b`     | Mover para o início da "palavra" anterior | **b**ack | `<shift>` + `<left>`  |
| `W`     | Mover para o início da palavra seguinte   | **W**ORD | `<ctrl>` + `<right>`  |
| `B`     | Mover para o início da palavra anterior   | **B**ACK | `<ctrl>` + `<left>`   |

**"palavra"**: Qualquer sequência de letras ou qualquer sequência de não-letras (menos espaço).  
**palavra**: Qualquer sequência de caracteres (menos espaço).  

## Move page up or down

| Atalho         | Ação                         | Dica        | Atalho 2    |
| -------------- | ---------------------------- | ----------- | ----------- |
| `<ctrl>` + `f` | Mover uma página para baixo  | **f**orward | `<pg down>` |
| `<ctrl>` + `b` | Mover uma página para cima   | **b**ack    | `<pg up>`   |
| `<ctrl>` + `d` | Mover meia página para baixo | **d**own    |             |
| `<ctrl>` + `u` | Mover meia página para cima  | **u**p      |             |

## Move start/end of line

| Atalho | Ação                         | Atalho 2    |
| ------ | ---------------------------- | ----------- |
| `$`    | Mover para o início da linha | `<home>`    |
| `0`    | Mover para o final da linha  | `<end>`     |

# Visual Mode
Muitas vezes os comandos neste modo se aproveitam dos comandos do **Normal Mode**.  
Por exemplo, ao entrar neste modo você continua a poder usar dos atalhos normais de movimentação para ajuda-lo a selecionar o texto.  

# Undo

| Atalho | Ação                      | Dica     |
| ------ | ------------------------- | -------- |
| `u`    | Desfazer a última mudança | **U**ndo |