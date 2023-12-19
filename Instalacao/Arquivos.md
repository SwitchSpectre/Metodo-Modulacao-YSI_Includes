# Arquivos

O metodo y_hook Arquivos Necessarios

# Arquivos Uteis
- [Gamemode Samp Original](https://www.sa-mp.mp/downloads/) - caso queira comecar uma do zero.
- [Pawn Compiler 3.10.10](https://github.com/pawn-lang/compiler/releases) - Melhor Compilador Pawn Atualmente. (Recomedo a Utilizacao)
- [Visual Studio Code](https://code.visualstudio.com/) - IDE que Estarei Utilizando(Caso Seja Android Podera Utilizar o Exagear ou [VHeditor](https://github.com/vhqtvn/VHEditor-Android/releases)).
- [(YSI_Includes)](https://github.com/pawn-lang/YSI-Includes/releases) - Includes YSI que contem o Metodo Que Vamos Utilizar.

# Pawn Compiler 3.10.10

Apos Baixar os arquivos do compilador Pegue todos os Arquivos que estao na Pasta `bin` e coloque na pasta `pawno` da sua Gamemode, de Preferencia Baixe os plugins e includes principais 
```c
[Plugins]
sscanf(ja contem a include)
streamer(ja contem a include)

[Includes]
zcmd(caso use esse processador de comando)
```
Sempre bom utilizar a versao mais atualizada do Plugin/include

# Iniciando Sua Gamemode
Apos Baixar Os Arquivos Da Gamemode, Crie Uma Nova Gamemode
![Utilize o Pawn Normal Para Abrir uma Nova Gamemode](../Imagens/Gamemode2.png)
Apos Voce Criar Uma Nova Gamemode Ela Estara Definida Como um FS(Filterscript) Por Tanto Devemos Apagar Toda essa Parte;


```c
// This is a comment
// uncomment the line below if you want to write a filterscript
//#define FILTERSCRIPT

#include <a_samp>

#if defined FILTERSCRIPT

public OnFilterScriptInit()
{
	print("\n--------------------------------------");
	print(" Blank Filterscript by your name here");
	print("--------------------------------------\n");
	return 1;
}

public OnFilterScriptExit()
{
	return 1;
}

#else
```

Essa Parte Sera Inutil Para Nos

# Visual Studio Code
Caso Nunca Tenha Instalado Recomendo Procure um Tutorial No Youtube, Tambem Pode ser Utilizado Sublime Text.

# YSI_Includes
baixe a Biblioteca de Includes YSI e pegue a pasta YSI_Includes e coloque na pasta da sua Gamemode em `pawno`

Vamos Para Proxima Aula!
[Manipulacao Dos Modulos](../Aulas/curso1.md)