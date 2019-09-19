# Start
A melhor maneira de memorizar um atalho/comando é relacionando ele com a ação que você quer executar.  
Por exemplo, é fácil lembrar que `d` é apagar pois a letra d vem de **D**elete.  

Usarei português e inglês quando julgar apropriado (quando eu quiser).  

É bom ter um conhecimento de programação para usar Vim. Por exemplo, sabe que "salvar" o arquivo é nada mais que "escrever em cima do anterior".  

## Instructions
* Eu vou referênciar a teclas utilizando o formato de "uma linha de código" do Markdown.  
  * tecla `y`, tecla `p`, tecla `d`, tecla `;`...  
* Vim é sensível a caracter, ou seja, apertar `d` é diferente de apertar `D` (shift + d)  
  * tecla `Y`, tecla `P`, tecla `D`, tecla `:`...  
* Se a tecla não for uma letra apenas, vou escrever o nome da tecla entre "<" e ">".  
  * tecla `<up>`, tecla `<down>`, tecla `<esc>`...  
* Apertar uma combinação de teclas ao mesmo tempo vai ser representado com um sinal de + fora da formatação de tecla.  
  * teclas `<ctrl>` + `w`...  
* Apertar uma sequência de teclas vai ser representado em apenas uma formatação.  
  * apertar teclas `ydp` (`y`,`d`,`p`), apertar teclas `:q!` (`:`,`q`,`!`)...  
* Qualquer outro caso eu tentarei deixar claro o que você deve apertar.  

# Modes
No Vim existe muitos modos, as funcionalidades das suas teclas variam em cada modo.  

É por isso que pessoas novas ficam perdidas no Vim. Elas começam a tentar escrever texto sem antes entrarem no modo que permite escrever.  

| Modo              | Utilidade         |                  | Atalho | Sair do modo |
| ----------------- | ----------------- | ---------------- | ------ | ------------ |
| Normal Mode       | Executar comandos | **default mode** |        |              |
| **I**nsert Mode   | Inserir texto     |                  | `i`    | `<esc>`      |
| **V**isual Mode   | Selecionar texto  |                  | `v`    | `<esc>`      |
| Command-line Mode | Linha de comandos |                  | `:`    | `<esc>`      |

# Chapter
Eu ataco em ordem de importância para conseguir utilizar Vim como editor de texto.  

* [Capítulo 1](chapter01.md)
