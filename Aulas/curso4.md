
## Limite do y_Hook 

o y_hook possui uma deficiencia como o hook e um gancho, no momento em que o mesmo e chamado ele chamar varios outros macros e alguns defines para torna possivel a modulacao, entao ele acab evadindo uma limitacao do Pawncc que no caso e o limite de caracteres em uma public 


Para resolver isso devemos prestar atencao nos Macros que diminiu o tanto de caracteres  aqui esta abaixo a documentacao
```c
			{"CP",  "Checkpoint",
			{"Cnt", "Container",
			{"Inv", "Inventory",
			{"Dyn", "Dynamic",
			{"TD",  "TextDraw",
			{"Upd", "Update",
			{"Obj", "Object",,
			{"Cmd", "Command",

``` 

Por tanto uma callback que poderia ser escrita assim:

```c
 hook OnPlayerEnterRaceCheckpoint() // off parametros 
 {
    return 1;
 }
 ```
          
                      E escrita assim! 


 ```c
 hook OnPlayerEnterRaceCP() // off parametros 
 {
    return 1;
 }
 ```

 Assim evitamos o erro de maximo de carecteres! 



## Nao Obrigatorio!!

[Estilo de Chamada a_entry!](../Aulas/curso5.md)