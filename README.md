basicBot
========

Um bot não tão básico para o plug.dj

[CONSIGA A EXTENSÃO DO GOOGLE CHROME AQUI!!!](http://s.bnzi.uk/bscbtxtnsn)
---------------------------------------------------------------------

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/motelbible/basicBot)

Criado por [Yemasthui](https://github.com/Yemasthui) mas agora mantido por [Benzi](https://github.com/Benzi) e traduzido por [Motel Bible](https://github.com/motelbible)

(Você pode me mandar uma mensagem no [Gitter](https://gitter.im/motelbible) se tiver alguma dúvida ou problema com o bot)

!!!PARA CUSTOMIZAR: USE [ESTE REPOSITÓRIO](https://github.com/motelbible/basicBot-customization)!!!
==============================================================================================

IMPORTANTE
----------

__basicBot tem sido atualizado para funcionar com a nova atualização do plug.dj. Ainda podem haver erros e bugs.__

__Certifique-se de atualizar seu atalho na barra dos favoritos já que o link mudou recentemente!!!__

__Mudanças importantes na versão 2.x.x:__

- Agora totalmente compatível com Firefox.
- Você pode mudar o nome do bot sem precisar fazer cópia (fork) do repositório. Disponível em configurações personalizadas como "botName".
- A variável do bot está agora exposta fora do script. Isso deve permitir a extensão de scripts secundários sem precisar fazer cópia do repositório e perder o suporte de sua base.
- __Agora há suporte à chat personalizado. Isso significa que você pode criar seu próprio dicionário de palavras ou traduzir o mesmo para sua própria língua.__

Uso
---

Adicione o código abaixo à barra de favoritos do seu navegador. Para iniciar o bot, clique no script.

`javascript:(function(){$.getScript('https://rawgit.com/motelbible/basicBot/master/basicBot.js');})();`

Se não funciona, acesse https://rawgit.com/Yemasthui/motelbible/master/basicBot.js , copie todo o seu conteúdo e cole no console javascript do seu navegador (F12) quando estiver na janela do plug.dj em sua comunidade.

###Comandos###

Os comandos podem ser encontrados [aqui](https://github.com/Yemasthui/basicBot/blob/master/commands.md).


###Extending functionality and custom default settings###

basicBot can be customized to fit your needs. Please refer to [the customization repository](https://github.com/Yemasthui/basicBot-customization) for more info.
Please do not try to if you are not confident in your javascript capabilities.


###Translations###

Official translations will be supported. Available ones can be found under [the language folder](https://github.com/Yemasthui/basicBot/blob/master/lang/langIndex.json). You can set a language in the room settings.
You can use your own translation or wording by translating the values of in [the English pack](https://github.com/Yemasthui/basicBot/blob/master/lang/en.json) and uploading it to a public hosting service. Put the link into your custom room settings, under chatLink.

__When translating the chat messages, please not that it is a json format, meaning it is structured as ```"key":"value"```, please only translate the "value" parts, and leave anything between %% (eg. %%NAME%%) as is, they are variables that get filled in by the bot.__


Credits
-------

I would like to thank the following people:

- Fungus: His Tastybot has been a source of inspiration for most of the features, and his help with coding problems has been invaluable to make this bot.
- TAT, Origin and other Litebot contributors: Their Litebot has inspired features like Roulette.
- Henchman: Never knew this undertaking would give me a friend too.

|Language | Translator|
|:------:|:---------:|
|Portuguese|[Motel Bible](https://github.com/motelbible)|
|French|[NDA](https://github.com/NDAthereal)|


Copyright
---------

Copyright &copy; 2014 Yemasthui

Modifications (including forks) of the code to fit personal needs are allowed only for personal use and should refer back to the original source.
This software is not for profit, any extension, or unauthorised person providing this software is not authorised to be in a position of any monetary gain from this use of this software. Any and all money gained under the use of the software (which includes donations) must be passed on to the original author.


Disclaimer
----------

This bot is developed independently. Changes may be made without notice. There is no guarantee for the bot to be functioning perfectly.
Plug.dj admins have the right to request changes. 
By using this chatbot you agree to not use it for violating plug.dj's Terms of Service. 
You also agree not to alter the bot's code, unless in the cases explicitly stated above, for personal use, or for the sole purpose of submitting a pull request with a bug fix or a feature update, at which point it will be looked at and decided by the authors of the project.
Please refer to the original author/repository at all times, even on personal forks that are not private.
Any requests for changes can be requested via email, through github or via plug.dj.
