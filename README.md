# Start
A melhor maneira de memorizar um atalho/comando é relacionando ele com a ação que você quer executar.  
Por exemplo, é fácil lembrar que `d` é apagar pois a letra d vem de **D**elete.  

Usarei português e inglês quando julgar apropriado.  

## Instructions
* Eu vou referênciar a teclas utilizando o formato de "uma linha de código" do markdow.  
  * tecla `y`, tecla `p`, tecla `d`...  
* Neovim é sensível a caracter, ou seja, apertar `d` é diferente de apertar `D` (shift + d)  
  * tecla `Y`, tecla `P`, tecla `D`...  
* Se a tecla não for uma letra apenas, vou escrever o nome da tecla entre "<" e ">".  
  * tecla `<up>`, tecla `<down>`, tecla `<escape>`...  
* Apertar uma combinação de teclas vai ser representado com um sinal de + fora da formatação de tecla.  
  * teclas `<ctrl>` + `w`...  


# Modes
Vim é dividido em 3 modos, cada um com funcionalidades diferente. As funcionalidades das suas teclas variam em cada modo.  

> É por isso que pessoas novas ficam perdidas no vim. Elas começam a tentar escrever texto sem antes entrarem no modo que permite escrever.  

| Modo | Utilidade |     | Atalho |
| ---- | --------- | --- | ------ |
| Normal Mode | Executar comandos | **default** | |
| **I**nsert Mode | Inserir texto | | `i` |
| **V**isual Mode | Selecionar texto | | `v` |

![Normal mode, Insert mode and Visual mode](modes.jpg)  

A tecla `<escape>` é utilizada para sair do insert mode e visual mode.  

