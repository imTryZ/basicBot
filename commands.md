Comandos:
=========

X especifica um número  
Argumentos dentro de ( ) são opcionais


Coordenador
-----------

|Comando | Argumentos |  Descrição |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | Define o tempo máximo para AFK |
|!clearchat | | Limpa o chat por completo |
|!cycle | | Ativa/desativa o ciclo de DJs |
|!cycletimer | X | Define o tempo máximo do ciclo de DJ quando 'cycleguard' estiver ligado |
|!locktimer | X | Define o tempo máximo que a fila de espera fica travada quando 'lockguard' estiver ligado |
|!refresh | | Recarrega a página do navegador de quem estiver usando o bot |
|!usercmdcd | X | Set o tempo de espera nos comandos para usuários comuns (cinzas) |
|!usercommands | | Ativa/destiva os comandos para usuários comuns |
|!voteskip | X | quando não há argumento, mostra o limite do 'voteskip', quando X for especificado, o limite do 'voteskip' será definido para o limite especificado. |

Segurança+ 
----------

|Comando | Argumentos |  Descrição |
|:------:|:---------:|:--------------------------------------:|
|!add | @usuário | Adiciona o usuário à fila de espera |
|!afkremoval | | Ativa/desativa remoção de AFKs |
|!autoskip | | Pula músicas automaticamente quando elas terminarem (use somente quando o bug de círculos aparece) |
|!bouncer+ | | Ativa/desativa o 'bouncer+' |
|!deletechat | @usuário | Deleta toda as mensagens do usuário especificado ***Atualmente removido devido a um bug (esperando correção)*** |
|!lock | | Trava a fila de espera |
|!lockdown | | Trava o chat para toda a sala: somente staff pode conversar |
|!maxlength | X | Especifica o tempo máximo de duração dos vídeos tocados na comunidade quando 'timeguard' estiver ligado |
|!move | @usuário (X) | Move o usuário para a posição X na fila de espera (padrão de 'move' é 1) |
|!remove | @user | remove user from the waitlist |
|!roulette | | Inicia uma roleta |
|!songstats | | Ativa/desativa estatísticas |
|!unlock | | Destrava a fila de espera |
|!welcome | | Ativa/desativa mensagens de boas-vindas para usuários que entram na comunidade |

Segurança
---------

|Comando | Argumentos |  Descrição |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | Mostra quantos usuários têm conversado nos últimos X minutos. Se X não for especificado, 60 é o padrão |
|!afkreset | @usuário | Reseta o tempo AFK do usuário |
|!afktime | @usuário | Mostra por quanto tempo o usuário esteve AFK |
|!autodisable | | Ativda/desativa o 'autodisable' |
|!ban | @usuário | Bane o usuário da comunidade por 1 dia |
|!blacklist / !bl | nome da blacklist | Adiciona a música à blacklist especificada |
|!blinfo | | Mostra informação requerida para tornar uma música 'proibida' |
|!cycleguard | | Ativa/desativa o cycleguard |
|!dclookup / !dc | (@usuário) | Mostra se o usuário foi desconectado (dentro do tempo nas configurações), re-adiciona-o à fila de espera e move para a posição que foi registrada |
|!english | @usuário | Pede para que o usuário fale em inglês (padrão do basicBot) (faz o pedido na linguagem que o usuário tem configurado seu plug) |
|!eta | (@usuário) | Mostra em quanto tempo o usuário tocará sua música |
|!filter | | Ativa/desativa filtro de palavras no chat |
|!jointime | @usuário | Mostra por quanto tempo o usuário esteve na comunidade |
|!kick | @usuário (X) | Chuta o usuário por X minutos, padrão é 0.25 minutos (15 segundos) |
|!kill | | Desliga o bot |
|!lockguard | | Ativa/desativa o lockguard |
|!lockskip | (razão) | Pula uma música e move o DJ para uma posição próxima da cabine (padrão é 3) |
|!lockskippos | X | Define a posição do "lockskip" |
|!motd | (X)/(mensagem) | Quando o argumento não é especificado, retorna a mensagem do dia, quando X é especificado, a mensagem do dia é dada num intervalo de X músicas, quando "mensagem" é especificado, a mesma se torna a mensagem do dia |
|!mute | @usuário (X) | Muta o usuário por X minutos se X for especificado, caso contrário, por um tempo indefinido |
|!reload | | Reinicia o bot |
|!restricteta | | Ativa/desativa a restrição em ETA: usuários comnuns só podem usar o comando uma vez por hora |
|!sessionstats | | Mostra estatísticas da sessão atual |
|!skip | | Pula a música atual |
|!status | | Mostra o status do bot e algumas configurações |
|!timeguard | | Ativa/desativa o timeguard |
|!togglebl | | Ativa/desativa a blacklist |
|!togglemotd | | Ativa/desativa a mensagem do dia |
|!togglevoteskip | | Ativa/desativa o voteskip |
|!unban | @usuário | Remove o usuário do banimento |
|!unmute | @usuário | Desmuta um usuário |
|!voteratio | @usuário | Mostra as estatísticas de voto do usuário especificado |

DJ Residente
------------

|Comando | Argumentos |  Descrição |
|:------:|:---------:|:--------------------------------------:|
|!link | | Mostra o link da música atual |



Usuário
-------

|Comando | Argumentos |  Descrição |
|:------:|:---------:|:--------------------------------------:|
|!autowoot | | Mostra o link do plugCubed, script/plugin de autowoot aconselhado para uso |
|!ba | | Explica o cargo de um Embaixador de Marca |
|!commands | | Retorna o link para comandos do bot |
|!cookie | (@usuário) | Oferece um biscoito ao usuário especificado |
|!dclookup / !dc | | Verifica se você foi desconectado e o moverá para a posição que foi registrada |
|!emoji | | Retorna um link para a lista de emojis |
|!eta | | Mostra em quanto tempo você tocará |
|!fb | | Retorna o link de uma página do Facebook (se for adicionada nas configurações) |
|!help | | Retorna um link de uma imagem para ajudar membros novos a conhecer o plug |
|!join | | Entra na roleta se a mesma tiver sido iniciada |
|!leave | | Sai da roleta se você tiver entrado |
|!link | | Quando o usuário for o DJ, retorna um link para a música atual no YouTube |
|!op | | Mostra uma lista de músicas muito tocadas (se for adicionada nas configurações) |
|!ping | | Pong! |
|!rules | | Mostra o link das regras da comunidade (se for adicionada nas configurações) |
|!theme | | Mostra o link do tema da comunidade (se for adicionada nas configurações) |
|!website | | Retorna um link para o site/blog/fórum da comunidade (se for adicionada nas configurações) |
|!youtube | | Mostra o link do canal do YouTube dda comunidade (se for adicionada nas configurações) |
