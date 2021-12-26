# Configuration
> Por padrão não existe arquivo de configuração, então crie o arquivo em `~/.config/nvim/init.vim`  

Utilizar esse arquivo de configuração é **bem** simples, basicamente você bota nele qualquer comando que você fosse executar com `:` no normal mode. Por exemplo, fazer as linhas aparecerem seria `:set number`, então no arquivo de configuração você bota:  
```vim
set number
```

Isto significa que é possível até trollar um amigo botando o comando de sair do Vim:
```vim
q!
```

Para adicionar um comentário a um comando use `"`
```vim
set number " Adiciona o número das linhas
```

Não precisa ser no final do comando, tudo após `"` será interpretado como comentário. Comente da maneira que preferir:  
```vim
" Adiciona o número das linhas
" Pois eu não consigo contar linhas tão rapido assim
set number
```

