## NPM : Documentação

Material de referência e consulta de comandos `npm`

Fontes:

 - [YouTube] NPM Inc : https://www.youtube.com/channel/UCK71Wk0I45SLTSXQA23GdIw


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
