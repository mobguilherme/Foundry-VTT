# Foundry-VTT
Esse repositório tem como objetivo ajudar aqueles que querem usar o Foundry VTT junto do sistema Tormenta20

Esse post venho como ideia de "ensinar" os meus amigos proximas a usar o Foundry VTT.

# Sistema de T20 no Foundry
O sistema T20 tem suporte para o Foundry, no momento em que eu escrevo isso, o sistema não é oficial e não é verificado pela Jambô, mas é bem compotente para algo feito por poucas pessoas, ele possui tudo sistema base + as distinções básicas (não a do Heróis&Deuses de Arton), tudo isso para a versão Jogo do Ano.

Para instalar, basta procurar na lista de sistemas dentro do próprio foundry. Para ler sobre o sistema e o modo como a ficha/efeitos/programação funciona. Leia sobre no site feito pelos desenvolvedores:
https://vizael.gitlab.io/tormenta20-fvtt/

Como eu disse, tudo na ficha funciona a base de efeitos, eles podem ser editados e modificados para caber nos efeitos que você queira, talvez uma homebrew ou até mesmo de um suplemento que não tenha suporte direto para o Foundry.

# Foundry V11 e Compatibilidade
A versão que eu tenho disponível no drive acima é a versão 11.314, uma ótima versão do foundry que tem recursos built-in que junto ao sistema pode gerar uma mesa bem feita. Os módulos que irei falar mais abaixo estão todos compatíveis para a a V11. Nem todos os módulos e funcionalidades que você pode ver em vídeos/posts são compatíveis com a V11.
Os módulos que aparecem na lista de instalação dentro do foundry são todos compatíveis com a versão que você está usando no momento.

# Conexão e Como Jogar com os amigos
Uma das coisas que mais dificultou o uso do foundry da minha parte foi a conexão e como jogar com os meus jogadores, diferente do Roll20/OwlBear, o Foundry deixa na mão de quem usa a conexão, apesar de dar alguns tutorais de Port Forwarding, eles são em inglês e dependem mais da sua operadora de internet do que de você.
Dito tudo isso, tem certas maneiras que a comunidade resolve essa situação:
- Port Forwarding: Resolva com a sua operadora e faça o redirecionamento de portas para que as pessoas possam acessar a sua máquina como host. O ponto negativo disso é que possa ser que a sua operadora negue o pedido, além de todo o trabalho que você vai ter que fazer pra ter essa opção.
- Usar uma VPN (ZeroTier): É possível usar uma vpn gratuita para rodar um IP comum para todos usarem e então acessar a sua máquina como host. Acho que o lado mais negativo disso é que quando um jogador queira acessar a mesa, o mestre tem que estar com o computador ligado, a vpn ativada (o jogador também) e o foundry aberto, e então usar o foundry. Eu particurlamente uso esse atualmente e consegui faze-lo graças ao vídeo do canal Dados Críticos (https://youtu.be/-3XTsCeydas?si=LZf_4i20ovdvJd37).
- Servidor Oracle: Também há a possibilidade de você querer a mesa funcionando a todo tempo, eu particularmente nunca usei esse, mas basicamente você cria um servidor em algum site que disponibiliza, a Oracle (Amazon), por exemplo, pode vir a lhe servir, tudo depende do quanto você quer pagar e quão grande são os arquivos que você quer colocar na mesa. Há um video muito bom sobre isso no canal Mestre Digital (https://youtu.be/Y1Nw2B4NvKM?si=Hmd_QTPpaF9ljL4m).
- Playit.gg: Uma das opções mais ascendentes que eu tenho visto é o uso de um aplicativo chamado Playit, que faz o redirecionamento de IP de todos os participantes da mesa para a máquina daquele que estiver rodando o aplicativo. É possível achar um tutorial curto no próprio canal deles, mas o vídeo está em inglês (https://youtu.be/8B_lm72Lgic?si=Amw9VkRzXUorY0TU).

Todas as opções acima são opções que eu sei que funcionam e válidas para o uso do Foundry, vale ressaltar que o uso do aplicativo do foundry é único do mestre, apenas ele precisa usar o aplicativo, os jogadores podem acessar a mesa a partir de um navegador comum.

# Recomendações e Conteúdos
Aqui é uma região de vídeos e canais que falam sobre o uso do Foundry, módulos e afins. Alguns deles são brasileiros, outros não.
- Dados Críticos (https://www.youtube.com/@dadoscriticos): Um canal de RPG geral que tem campanhas e diversos vídeos sobre o foundry, é um ótimo canal para quem está começando a usar o aplicativo.
- Mestre Digital (https://www.youtube.com/@MestreDigital): Outro canal brasileiro, mas que foca o seu conteúdo no Foundry, falando sobre diversos vídeos sobre os módulos com diversas compatibilidades para as versões do foundry e sistemas. Ele fala sobre as versões mais recentes do Foundry nos vídeos mais novos.
- Alaustin (https://www.youtube.com/@alaustin./videos): Um canal em inglês que tem poucos vídeos sobre alguns outros sistemas e alguns tutorias mais simples, o vídeo dele que pode mais ajudar é pra quem estiver transicionando do Roll20 gratuito (sem luz dinâmica) para o Foundry (com luz dinâmica). https://youtu.be/Jssi4RGDL9Y?si=NmtNk2FbqoQlmONU
- Youtube: Uma dica óbvia, mas que é bom deixar explícito aqui, o youtube é seu amigo, pesquisar palavras chaves em inglês do que você queira fazer junto a palavra Foundry pode ter um resultado bem positivo.
- Reddit (https://www.reddit.com/r/FoundryVTT/): A comunidade do Foundry no reddit pode ser bem agradavel para algumas dúvidas mais específicas, mas, um conselho, evite falar que a sua versão é pirateada, os gringos podem ser bem agressivos com quem pratica pirataria, eles apenas ignoram a realidade brasileira e acham um absurdo você não querer pagar 280 reais em um produto de RPG.

# Módulos para T20
Eu não vou deixar os links aqui, pois pode ter um erro de compatibilidade com as versões, mas eu vou falar o nome e pra que eu uso o módulo.
- Automated Animations: Uma interface completa que lhe dar a possibilidade de ter animações dentro do Foundry, mas não lhe dá as animações diretamente, apenas a interface, a maioria das animações são feitas pela comunidade, dentro de outros módulos, mas que costumam ser pagas por meio de um Patreon. Mais abaixo há o JB2A que lhe dá algumas gratuitamente (veja mais abaixo);
- Brazilian Portuguese: Faz a tradução do foundry do inglês para o português;
- Chat GIFs: Permite com que os jogadores usem gif's no chat;
- Chat Images: Permite com que os jogadores mandem imagens no chat, seja do copiar ou upar uma imagem para o chat;
- Chat Reactions: Permite com que os jogadores adicionem reações a mensagens no chat;
- Combat Carousel: Cria um carrossel que controla a iniciativa e mostra para o mestre e os jogadores;
- DFreds Chat Pins: Permite fixar mensagens do chat;
- Dfreds Droppables: Melhora a mecânica para dropar as coisas na mesa, seja um token, uma pasta inteira e etc;
- Dice So Nice!: Cria dados 3D costumizáveis para as rolagens;
- Dice Tray: Cria uma calculadora rápida para fazer rolagens rápidas no Foundry;
- Drag Anything to Hotbar: Permite que qualquer um arraste algo para a barra de macros para criar um macro, uma habilidade, um ataque, etc;
- Drag Ruler: Adiciona várias métodos de régua, além de permitir que haja conversão de medidas, para metros, por exemplo;
- Dungeon Draw: Adiciona uma interface para que o mestre possa desenhar uma dungeon do zero, diretamente no Foundry, consegue ser bem útil a depender da campanha;
- Filepicker Improvements: Modifica a interface do Foundry para visualização de arquivos, consegue adicionar muitas coisas interessantes para o mestre;
- Forien's Quest Log: Adiciona uma nova interface para criação e aceitação de missões, como um quadro de missões interativo;
- FXMaster: Adiciona efeitos ao Foundry, especialmente de clima, como chuva, nevasca, furação etc;
- Item Piles: Permite adiconar drops ao mapa, esses drops são altamente configuráveis e criar recipientes como caixotes e baús, além de configurar a moeda do jogo, junto a isso, em estágios mais altos de configuração, até fazer um token interativo, como um mercante automático, onde os jogadores gastam o dinheiro e pegam os itens;
- JB2A: Conteúdo gratuito para fazer animações de ataques, magias, entre outros. Ele interage diretamente com o Automated Animations (descrito acima);
- Forgotten Adventures Battlempas: Adiciona uma interface interna que lhe dar acesso ao site https://www.forgotten-adventures.net/ que possui mapas pagos e gratuitos dos mais diversos cenários de RPG, podendo importar ele diretamente para o Foundry, o que pode facilitar o uso de mapas improvisados.
- Universal Battlemap Importer: Adiciona um botão na aba de cenas que possibiita importar alguns arquivos especiais, especialmente do DungeonDraft que já vem com algumas configurações prontas, como portas, janelas, pareces e luzes;
- Minimal UI: Permite mudar a interface do Foundry, para algo mais espalhafatoso ou mais minimalista;
- Module Management: Um módulo que permite uma melhor interface para mexer nos módulos;
- Monk's Active Tiles Triggers: Permite ter diversas interações com tiles (peças) que você pode upar, mas, por exemplo, colocar uma imagem transparente permite ter uma tela interativa para os jogadores, dentre outras funcionalidades como abrir jornais, mudar cenas, rolar um macro, teleportar personagens para regiões diferentes, entre outras;
- Monk's Little Details: Adiciona as condições de T20 ao um menu no token do personagem, adicionando os efeitos direto ao personagem, praticamente indispensável;
- Monk's Player Settings: Permite com que o mestre mude as configurações dos jogadores um por um ou até mesmo de todos de uma vez;
- Multilevel Tokens: Junto do Monk's Active Tiles Triggers adiciona mecânicas de níveis diferentes, como andar 1 e andar 2 de uma casa, com a interação de tiles e escadas;
- Note Licker: Permite com que um jogador pegue uma nota (journal) e drope no mapa, ajuda muito nas descrições de dungeons;
- PDF Pager: Permite adicionar pdf's ao Foundry;
- PopOut!: Adiciona um botão de popout para os jogadores que funciona no navegador, fazendo com que uma ficha possa ser destacada do Foundry e aberta em outra aba, como outro monitor por exemplo.
- Quick Insert: Adiciona um atalho que permite dropar no mapa algo no Foundry, ele procura em toda base de dados do Foundry;
- Share Media: Adiciona um botão para mostrar imagens aos jogadores;
- Simple Calendar: Adiciona um calendário ao Foundry, que permite adicionar notas as datas, além de controlar o horário. Na base, não há compatibilidade com o calendário de Arton, mas a comunidade de T20 criou um, acesse https://www.reddit.com/r/Tormenta/comments/xvuw6q/calendário_de_arton/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button
- Tile Scroll: Adiciona um efeito nos tiles para criar um efeito de paralaxia, algo que pode fazer uma cena que passe a sensação de movimento, como uma perseguição a cavalo.
- Token Auras: Em T20, muitos personagens tem efeitos de aura e os efeitos do Foundry não se arrastar junto dos personagens, esse módulo adiciona essa funcionalidade.
- Tokens Frames: Adiciona bordas para fazer tokens dentro do Foundry, ele apenas adiciona as bordas, para criar o token, você precisa ter o Tokenizer (abaixo);
- Tokenizer: Adiciona uma interface para criar tokens dentro do Foundry, Tokens Frames adiciona várias bordas diferentes, mas você também pode adicionar a sua própria;
- Token Magic FX: Adiciona um Compendium completo com macros com efeitos para os tokens, como uma borda brilhante, um token pegando fogo, entre outros;
- Torch: Adicona um botão ao token que permite ao token emitir uma luz configurável como se o personagem estivesse com uma tocha;

Vários desses módulos possuem pendências, outros módulos que são necessários para fazer eles rodarem, eu não listei eles aqui, mas eles serão pedidos assim que forem instalados, o Foundry irá perguntar se você quer também instalar as pendências, basta aceitar que a instalação será feita em conjunto. 

# Ameaças & Atlas de Arton para FoundryVTT
 
