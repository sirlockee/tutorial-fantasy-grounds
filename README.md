# Tutoriais de Fantasy Grounds

Neste repositório eu mantenho um conjunto de tutoriais relacionados ao uso do **Fantasy Grounds**, um software de tabletop para jogos de RPG, como Dungeons & Dragons, por exemplo. O Fantasy Grounds é agnóstico, ou seja, ele é capaz de funcionar de acordo com vários sistemas de RPG diferentes.

![alt Sistemas do Fantasy Grounds](https://github.com/sirlockee/tutorial-fantasy-grounds/raw/master/imagens/tutorial0_img1.jpg)

 Ele possui as versões *Demo*, *Standard* e *Ultimate*. Para iniciar uma campanha (como DM, Dungeon Master) publicada com o Fantasy Grounds *Ultimate*, os jogadores precisam da licença *Demo* (que é grátis). Para iniciar uma campanha compartilhada com a licença *Standard*, os jogadores também precisam de uma licença *Standard* (ou seja, eles terão que comprar o software). A licença *Demo* também permite criar campanhas de teste, publicadas para apenas um jogador que também tenha a licença *Demo*. Então, para os mestres, sugiro comprar a licença Ultimate.

O Fantasy Grounds pode ser adquirido diretamente pelo site https://www.fantasygrounds.com/, ou através do **Steam**. O preço oferecido pelo **Steam** chega a ser 50% mais barato do que o valor apresentado no site. A execução do software nos sistemas operacionais *Mac OS* e *Linux* é realizada através do emulador Wine (sem nenhuma perda de performance relevante). O único problema é que há casos que isso pode causar problemas na execução do software diretamente pelo **Steam**. Eu particularmente comprei minha licença *Ultimate* no **Steam** e a copie para a versão baixada diretamente de https://www.fantasygrounds.com/ - isso não é treta ;) ... há fóruns no site oficial do Fantasy Grounds e do Steam indicando este procedimento.

Uma última observação: diferente do sistema **Roll20**, o Fantasy Grounds não possui versão direto pelo browser. Os jogadores precisam obrigatoriamente baixar (ou comprar) uma das versões do executável. Na minha opinião, isso não traz nenhuma desvantagem em relação ao Roll20. Veja no tutorial [Roll20 vs Fantasy Grounds](#roll20-vs-fantasy-grounds) maiores detalhes.

## Como ingressar em uma campanha

Baixe o software **Fantasy Grounds** em https://www.fantasygrounds.com/, ou o **Fantasy Grounds Demo** no **Steam**. Instale-o em seu computador e execute-o. Na primeira tela, você verá várias opções. Clique na opção *Join Game*.

![alt Sistemas do Fantasy Grounds](https://github.com/sirlockee/tutorial-fantasy-grounds/raw/master/imagens/tutorial1_img1.jpg)

Dentro da janela principal (do lado direito), digite o nome de seu personagem (ou o nome do Jogador, conforme acordado com o DM) no campo *Username*. No campo *Host address*, digite o endereço IP que o DM informou aos jogadores (atenção: o endereço apresentado na imagem abaixo é apenas um exemplo). Por fim, clique no botão *Start*.

![alt Sistemas do Fantasy Grounds](https://github.com/sirlockee/tutorial-fantasy-grounds/raw/master/imagens/tutorial1_img2.jpg)

A conexão do client (Fantasy Grounds do Jogador) com o servidor (Fantasy Grounds do DM) pode demorar alguns segundos, dependendo da sua conexão com a Internet. Isso pode parecer demorado, mas a vantagem é que muita coisa disponível em sua campanha será baixada para os clients, evitando loading pesados durante o jogo. Um último detalhe relevante: o software pode consumir bastante energia do computador. Se você estiver jogando em um notebook, lembre-se de conectá-lo à tomada.

## Como Mestrar e Jogar no mesmo computador?

As vezes é útil usar o **Fantasy Grounds** em mesas presenciais. Para isso, eu particularmente utilizo meu notebook com um monitor auxiliar: na tela do notebook (que só eu vejo), mantenho um **Fantasy Grounds** com a visão de mestre, enquanto que no monitor mantenho outra instância do **Fantasy Grounds** exibindo a visão de jogador.

É isso mesmo: você precisa de dois executáveis do Fantasy Grounds. Sugiro comprar sua "versão do mestre" (*Ultimate*, *Standard* ou até mesmo *Demo*) no Steam e baixar uma "versão do jogador" (*Demo*) direto no site. Rode a "versão do mestre" primeiro, abra sua campanha publicando-a no endereço 127.0.0.1 (endereço *localhost* do seu computador). Depois execute a "versão do jogador" entrando (*Join Game*) no mesmo endereço 127.0.0.1.

## Roll20 vs Fantasy Grounds

Bom, este é um assunto meio polêmico (tipo Star Wars vs Star Trek), mas vou deixar algumas ponderações pessoais. Antes de começar: já mestrei (e às vezes mestro) no Roll20, mas prefiro o Fantasy Grounds.

Ah sim, claro: não confunda as excelentes streams produzidas pelos mestres brasileiros no Roll20 com uma comparação entre ambas ferramentas. Também sou fã do [AzeCos](https://www.twitch.tv/azecos), do [Gruntar](https://www.twitch.tv/gruntartv), do [Tchelo e Lina](https://www.rpgplanet.com.br/), entre outros. Depois veja algumas streams dos gringos realizadas no Fantasy Grounds.

| Recurso      | Roll20 | Fantasy Grounds | Voto |
| ------------ | ------ | --------------- | :----: |
| Interface | Mais fácil, mas é meio antiquada (feiosa) | Mais rebuscada e muito mais imersiva | FG |
| Mapas | Configuração simples, porém um pouco chato para alinhar a grid (se houver) do mapa com a do Roll20. Possui os recursos de Fog of War (mostra o mapa conforme o DM vai liberando) e Dynamic Lighting (mostra com perspectiva do personagem) | Configuração simples, com alinhamento "desenhado" sobre o mapa. Possui Fog of War (mostra o mapa conforme o DM vai liberando), mas NÃO possui Dynamic Lighting (mostra com perspectiva do personagem). | Roll20 |
| Dynamic Lighting | Sim (na versão assinada) | Não. Está em desenvolvimento. | Roll20 |
| Fog of War | Sim. É um pouco chato alinhar a grid com o mapa | Sim. A grid é gerada a partir de um quadrado desenhado sobre o mapa | FG |
| Licenciamento | Versão *Base* é muito boa, porém sem o Dynamic Lighting (ponto forte do Roll20). A versão *Plus* possui assinatura mensal de $4,99 e anual de $49,99. A versão *Pro* possui assinatura mensal de $9,99 e anual de $99,99. Não há uma modalidade de compra única. | No site oficial, é possível assinar por $3,99 (*Standard*) ou $9,99 (*Ultimate*) ou comprar uma única vez (sem assinatura) por $39 (*Standard*) ou $149 (*Ultimate*). Também é possível comprar pelo Steam. Os preços variam, mas a compra única da *Ultimate* está na faixa de R$ 250,00 | FG |
| Help | Muitos vídeos e wiki's (inclusive em Português) | Muitos vídeos e wiki's (só em Inglês) | Empate |
| Tokens | Facilidade de obter tokens (pagos e livres) diretamente na ferramenta, sendo que há muito conteúdo grátis disponível | Facilidade de obter tokens (pagos e livres) diretamente na ferramenta, sendo que há tokens associados a material oficial dos sistemas que podem ser carregados (a maioria são pagos, neste caso) | Empate |
| Preparar Campanha | Ok, bem legal. Só acho chato o vai e volta de janelas e popups para configurar tudo. Não é muito intuitivo (para novos usuários) | Excelente. Os botões laterais são bem intuitivos e auxiliam muito na preparação da campanha | FG |
| Parcels (itens) | Manual. Digo, você pode preparar handouts ou documentos para auxiliar, mas deve ser repassado para as planilhas dos personagens um a um. | Excelente. Há um mecanismo de distribuição bem inteligente e rápido (Parcels). Exige preparação prévia, mas na hora da aventura é muito rápido distribuir os itens e moedas (que é o que importa). | FG |
| Aventuras | Há formas de preparar handouts com conteúdo auxilar, anotações na GM Layer, entre outros recursos paliativos. Não há uma seção própria para a organização da aventura. | Muito bom! Há um botão próprio para criar as aventuras, indicar quais inimigos (itens, etc) serão encontrados em cada momento, com fácil localização no mapa e distribuição de XP. | FG |
| Música | Muito bom! Compartilha músicas para os jogadores. Utiliza o SoundCloud. | Não possui, porém é possível compartilhar música externamente pelo Shoutcast. | Roll20 |
| Layers | Possui camadas de mapa, jogador, mestre e Dynamic Lighting. | Não trabalha com o conceito de camadas, porém o compartilhamento de mapas com os jogadores é excelente (seria equivalente às camadas). | Empate |
| Criação dos personagens | Há um mecanismo bugado de criação das planilhas dos jogadores. Digo bugado porque as telas apresentam vários probleminhas. Só utilizei a do D&D 5ed, mas existem outras. No final das contas, compensa mais utilizar o site D&D Beyond. | Existe um mecanismo excelente. Veja [este tutorial](https://youtu.be/thbasZ8VXg4) ou a [wiki](https://www.fantasygrounds.com/wiki/index.php/5E_Character_Sheet) e tire suas conclusões. A planilha do jogador do Fantasy Grounds é sinistra! | FG |
| Como executar? | No Browser, que no geral consome algo entre 50MB a 100MB de RAM. Eu o utilizo no Chrome, no Mac OS X, mas no Linux e Windows os resultados são semelhantes. O Firefox consome o dobro de RAM. | Aplicativo próprio, que consome 20MB no Mac OS X ou Linux e 250MB no Windows. | Empate |
| Andamento do Jogo | O melhor recurso do Roll20 para facilitar o andamento do jogo é a disposição dos personagens em um mapa específico (menu superior). O mestre transfere a visão dos jogadores através deste recurso. A desvantagem é que o mestre pode estar focado em um trecho específico da dungeon (ou mapa) enquanto os jogadores em outro. Há um recurso de "ping" (segurar botão esquerdo do mouse) para auxiliar a localização. | Uma coisa excepcional do FG: o mestre, ao exibir uma dungeon (ou mapa) para os jogadores, pode fazer com que eles vejam uma parte específica da imagem. Imagine por exemplo que o mestre esteja exibindo o mapa full de Forgotten Realms, em um trecho particular próximo de Baldur's Gate. Ele pode "compartilhar" o zoom e posição do mapa que está em sua tela com a tela dos jogadores e ir atualizando isso sempre que necessário. Outro recurso excelente é a Party Sheet, uma tela para visualizar todos os dados dos jogadores de uma vez, com recursos de loot de itens, distribuição de XP, entre outros (este recurso não existe no Roll20). | FG |
| D&D 5e | Compatível | Compatível | Empate |
| Call of Cthulhu | Compatível | Compatível | Empate |
| Pathfinder | Compatível | Compatível | Empate |

Não considere este resultado como uma simples soma de pontos dos recursos. Minha avaliação fica mais a critério do feeling mesmo. Digo, o objetivo final é a diversão. Eu me divirto mais em uma mesa online com o Fantasy Grounds. Se você se divertir mais com o Roll20, ou o GM Forge, ou o Tabletop Simulator... enfim, é contigo!

## Tutoriais no YouTube

* [Fantasy Grounds For Beginners](https://youtu.be/BW2Y45Bjwpo)
* [Fantasy Grounds for Dummies](https://www.youtube.com/playlist?list=PLTCVdZUjxeLzb4K8hX-L9zC8AsLValVPw)

## Contatos

### Sir Lockee

![alt Sir Lockee](https://github.com/sirlockee/tutorial-fantasy-grounds/raw/master/imagens/sirlockee.png)

* https://www.facebook.com/sirlockee
* https://www.twitch.tv/sirlockee
* https://twitter.com/sirlockee
* https://github.com/sirlockee
* https://www.instagram.com/sirlockee
* sirlockee@rpg.house
