# Manipulacao De CallBacks

Agora Vamos entender sobre a Manipulação de Callbacks diferente da ALS não precisamos usar um Gancho, e vários #endf como ativador de Callback, um exemplo de um código normal em uma Gamemode não Modulada
```c
public OnGameModeInit()
{
     print("olá Mundo!");
     return true; 
}
```

Usamos a Função Public para chamar uma Função na YSI invés de Public usamos... hook, Exemplo
```c 
hook OnGameModeInit()
{
     print("olá Mundo!");
     return true; 
}
```
Não Temos Limites de Publics, Limites de Linhas nada! você e livre pra fazer oque quiser com os Módulos, e na Main poderá fazer oque quiser também, se quiser adicionar algo a Ela, Também e Possível nada te impede! 


[Manipulacao de callback com carecteres maiores que 31!](../Aulas/curso4.md)

