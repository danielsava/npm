## NPM : Documentação

Material de referência e consulta de comandos `npm`

Fontes:

 - YouTube : [NPM Inc](https://www.youtube.com/channel/UCK71Wk0I45SLTSXQA23GdIw)


<br/>

### Pacotes instalados

Para verificar os pacotes `npm instalados`:

    # Local
    $ npm ls
    
    # Global
    $ npm ls -g --depth=0
   
<br/>   

### Uninstall

O comando acima lista os pacotes instalados. Para desinstalar:

    # Local
    npm uninstall <nome_pacote>

    # Global
    $ npm uninstall -g <nome_pocote>
    
    # ex.:
    $ npm uninstall -g @nestjs/cli
  
`obs`: informar o nome do pacote sem a versão

<br/>

### Desatualizados

Como o comando `outdated` é possível verificar os pacotes que estão desatualizados:

    # Local
    npm outdated
    
    # Global
    npm outdated -g
    
`obs` : a coluna `Wanted` possui a versão compatível com a aplicação e a coluna `Latest` mostra a versão mais recente do pacote. 

<br/>

### Atualização

Com o comando acima é possível verificar os pacotes que estão desatualizado. Com o `npm update` é possível atualizar os pacotes para as versões `Wanted`

    # Local
    npm update
    
    # Global
    npm update -g



