# Start
A melhor maneira de memorizar um atalho/comando é relacionando ele com a ação que você quer executar.  
Por exemplo, é fácil lembrar que `d` é apagar pois a letra d vem de **D**elete.  

Usarei português e inglês quando julgar apropriado.  

## Instructions
* Eu vou referênciar a teclas utilizando o formato de "uma linha de código" do Markdow.  
  * tecla `y`, tecla `p`, tecla `d`...  
* Neovim é sensível a caracter, ou seja, apertar `d` é diferente de apertar `D` (shift + d)  
  * tecla `Y`, tecla `P`, tecla `D`...  
* Se a tecla não for uma letra apenas, vou escrever o nome da tecla entre "<" e ">".  
  * tecla `<up>`, tecla `<down>`, tecla `<escape>`...  
* Apertar uma combinação de teclas ao mesmo tempo vai ser representado com um sinal de + fora da formatação de tecla.  
  * teclas `<ctrl>` + `w`...  
* Apertar uma sequência de teclas vai ser representado em apenas uma formatação.  
  * apertar teclas `ydp`...  

# Modes
Vim é dividido em 3 modos, cada um com funcionalidades diferente. As funcionalidades das suas teclas variam em cada modo.  

> É por isso que pessoas novas ficam perdidas no vim. Elas começam a tentar escrever texto sem antes entrarem no modo que permite escrever.  

| Modo | Utilidade |     | Atalho |
| ---- | --------- | --- | ------ |
| Normal Mode | Executar comandos | **default mode** | |
| **I**nsert Mode | Inserir texto | | `i` |
| **V**isual Mode | Selecionar texto | | `v` |

![Normal mode, Insert mode and Visual mode](modes.jpg)  

Se você está no Normal Mode, você pode ir para o **I**nsert Mode apertando a tecla `i`.  
Se você está no Normal Mode, você pode ir para o **V**isual Mode apertando a tecla `v`.  
Se você está no Insert Mode ou Visual Mode, você pode voltar para o Normal Mode apertando a tecla `<escape>`.  

## Insert Mode
No início esse vai ser o seu modo mais utilizado pois ele te lembra de como qualquer editor normal funciona, ou seja, você aperta uma tecla e ela é escrita na tela.  

### Shift
Se você está acostumado a selecionar parte do texto utilizando a tecla `<shift>`, você deve notar rápido que não é possvel selecionar parte do texto nesse modo.  

Shift funciona de maneira engraçada pois

## Visual Mode