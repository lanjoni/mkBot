# mkBot

Este é um bot, programado em Python, para ouvir músicas no Discord!

Você pode facilmente adicionar todo o diretório com os arquivos em seu editor de texto favorito (eu gosto de utilizar o VSCode - e recomendo-, mas utilize o de sua preferência), porém, seria necessário adicionar algumas "dependências", e para isso, após adicionar todos os arquivos necessários (instalar o Python pelo site oficial - caso esteja no Windows - e sua extensão no VSCode), abra seu terminal (pelo VSCode, caso esteja utilizando) e execute os seguintes comandos:

```
pip3 install discord
```

- Para instalar a dependência relacionada com a execução do discord (pode ser necessário instalar o comando pip em seu SO, e fique tranquilo para instalar).

```
pip3 install youtube_dl
```

- Para instalar a dependência relacionada com a pesquisa de vídeos no YouTube.

```
pip3 install -U discord.py[voice]
```

- Para instalar a função de conectar a uma conversa, e pela voz, "liberar" o som da música.

Basicamente, após iniciar uma procura de música no YouTube, o bot registra a primeira URL encontrada, e assim, toca a música.

Caso deseje alterar o código de acordo com suas preferências, basta baixar o arquivo e alterar o token de acesso para seu próprio bot! Fique atento com "cogs/music.py", pois é exatamente neste local que comandamos o registro de músicas, adição de uma fila, e até mesmo pular a sequência. 

Agora é só executar o bot e aproveitar! 😉

##

This is a bot, programmed in Python, to listen to music on Discord!

You can easily add the entire directory with the files in your favorite text editor (I like to use VSCode - and I recommend it -, but use the one you prefer), however, it would be necessary to add some "dependencies", and for that, after adding all the necessary files (installing Python from the official website - if you are on Windows - and its extension in VSCode), open your terminal (through VSCode, if you are using it) and run the following commands:

```
pip3 install discord
```

- To install the dependency related to running discord (you may need to install the pip command on your OS, and feel free to install).

```
pip3 install youtube_dl
```

- To install the dependency related to searching videos on YouTube.

```
pip3 install -U discord.py[voice]
```

- To install the function of connecting to a conversation, and by voice, "release" the sound of music.

Basically, after starting a music search on YouTube, the bot records the first URL found, and thus plays the song.

If you want to change the code according to your preferences, just download the file and change the access token for your own bot! Keep an eye out for "cogs/music.py", as this is exactly where we'll be able to register songs, add a queue, and even skip the sequence.

Now just run the bot and enjoy! 😉

<img alt="GitHub followers" src="https://img.shields.io/github/followers/gutoso?style=social"> ⠀<img alt="Twitch Status" src="https://img.shields.io/twitch/status/holly1v4?style=social"> ⠀<img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/gutolanjoni?style=social">
