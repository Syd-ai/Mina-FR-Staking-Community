# GUIDE - Mina FR Staking Community - Syd

DISCORD : Syd#9907 - Discord Mina (https://discord.com/invite/Vexf4ED) - Tags : Genesis Founding Member - Community MVP

TELEGRAM : @Sydai

MINA PROTOCOL : https://minaprotocol.com/

MINA TOKENOMICS : https://minaprotocol.com/blog/mina-token-distribution-and-supply

TOUT SAVOIR SUR LE STAKING (Source Officielle - en anglais) : https://minaprotocol.com/blog/staking-rewards-on-mina

GROUPE FR TELEGRAM (notifications + informations) : https://t.me/joinchat/GOXwI_VMnJ5kYWRk

## PRESENTATION 

Bonjour,

Je suis Syd, gestionnaire de nodes et validateur depuis quelques temps sur de nombreux projets crypto (Avalanche, Hopr, Nyzo, Idena, Bismuth, Stafi, Certik, Zelcash, Stakenet, Buzzer etc.) et, plus récemment, "GFM" (Genesis Founding Member) sur Mina. J'ai été sélectionné également durant le dernier Testnet pour recevoir une délégation de la Fondation Mina (Top 100) et fais partie des "Community MVP". Par ailleurs, je suis actif sur de nombreux Discord cryptos FR tels que La Baleine (https://discord.gg/m93GeFer), Crypto Sisyphe (https://discord.gg/k59aVwwV) ou La Cryptosphère (https://discord.gg/xa3jpQyuJC) sur lesquels vous m'avez peut-être déjà croisé :smile: 

## OBJECTIF DE LA POOL

**Mon but est donc de proposer un pool de staking MINA pour la communauté FR**. Il s'agit d'un pool accessible et personnalisé avec pour vous un contact français actif. Je ne souhaite pas m'étendre à l'international étant donné que mon objectif est principalement de garder un contact privilégié avec les personnes me faisant confiance pour déléguer leur MINA. Vous pourrez ainsi me contacter sur Discord ou Telegram à tout moment, en communiquant en Français. Inversement, je vous contacterai pour transmettre toute information importante ayant trait au Staking sur MINA. 

## CARACTERISTIQUES

Le Block Producer (BP) sera mis en place sur deux **serveurs dédiés de haute qualité** (12 et 16 cores - 128 go RAM) ainsi que d'un server cloud de backup (16 cores et 32 go) et bénéficiera d'un **monitoring permanent**. Avoir 3 serveurs permet de back-up l'un et l'autre serveur en cas de failure. Aucun Snark-Worker (SW) ne sera en fonction sur les machines. Très actif sur le projet, je suis également les développements, mise à jour et forks de près. La délégation vous permet ainsi de staker vos MINA en toute sérénité, sans que vous n'ayiez rien à ne vous soucier.

***Ma commission est de 5% et NE CHANGERA PAS pendant 4 ans (jusqu'au 31 mars 2025)***. 

Mon pool de staking dispose aujourd'hui d'un stake de **3,906,975 Mina (0,48 %)** (au lancement du RC - 16/03/2021). Il fait partie du top 15 actuel (https://mina.staketab.com/) et **vous garantit ainsi un résultat moins aléatoire et lissé, puisque vous serez rémunéré à hauteur de votre participation dans le pool**.

## VOS RECOMPENSES 

J'effectuerai les paiements à l'aide du script de jrwashburn#0765 (https://github.com/jrwashburn/mina-pool-payout) qui permet de déterminer les payouts de chacun. 
**Les paiements seront effectués à chaque fois qu'une époque est complétée (~ tous les 15 jours)**.

Basiquement, le calcul est effectué ainsi : si par exemple le pool mine un block avec une récompense totale de 720 MINA (block + frais de transaction), il sera d'abord déduit les 5% (36 MINA) de commission. Les 684 MINA restants seront ensuite redistribués à hauteur de la contribution de chacun dans la pool (sachant qu'il y a une pondération selon que vos MINA soient supercharged ou non).

Pour estimer vos récompenses, cela dépendra de votre stake et du statut de vos MINA (vested ou non). Vous pouvez utiliser la calculatrice de Towerstake pour obtenir une estimation plus précise : https://towerstake.com/calculatrice-de-gains-delegateurs/. Toutes les informations sur les tokenomics de MINA sont retrouvables ici : https://minaprotocol.com/blog/mina-token-distribution-and-supply

Pour faire simple, si vos coins sont locks, vous pouvez compter sur environ un retour annuel (APY) de 12% pour les deux premières années. Si vos coins sont unlock, ce taux augmente à 24% (mais retombe progressivement à 15% après 14 mois).

Notez que je n'enverrai pas les récompenses lorsqu'elles sont inférieurs à 0.01 mina (ce qui correspond à peu près à un staking inférieur à 1 mina)

## COMMENT DELEGUER VOS MINA ?

Pour staker vos MINA à travers la Pool, il faut déléguer à l'addresse suivante :

> **B62qnR6HKx34NCyDkSeRcJ44KATjUCs4xmQYDbwTXPJPQ4J6ebfeQe4**

> **UPDATE : un wallet communautaire est désormais disponible et vous permet de déléguer plus facilement grâce à une interface plus accessible >> https://clor.io/** - l'interface permettant de déléguer est assez claire, mais vous pouvez utiliser ce guide étape par étape rédigé par le développeur : https://docs.clor.io/how-to-delegate)

> **UPDATE 2 : un deuxième wallet communautaire de qualité (extension chrome et bientôt sur Android/iOS) vous permet également de déléguer facilement :** https://www.aurowallet.com/)

Si vous préférez procéder avec le wallet CLI, il faudra donc utiliser les commandes suivantes :

`mina account unlock -public-key $MINA_PUBLIC_KEY`

`mina client delegate-stake \
    -receiver B62qnR6HKx34NCyDkSeRcJ44KATjUCs4xmQYDbwTXPJPQ4J6ebfeQe4 \
    -sender $MINA_PUBLIC_KEY \
    -fee 0.1`

($MINA_PUBLIC_KEY ou votre clé publique).
(Guide officiel MINA : https://docs.minaprotocol.com/en/using-mina/staking)

Attention, ne m'envoyez pas vos fonds. **En délégant, vous gardez intégralement le contrôle sur vos MINA.**

Vous pouvez également mettre fin à la délégation à tout moment (notez qu'il y a un délai protocolaire de 1 ou 2 époques selon les cas).

Notez également que les Minas délégués peuvent être transférés à tout moment (mais bien entendu vous ne stakerez plus dessus)

## CONTACT 

Idéalement, avant toute délégation, prenez au préalable contact avec moi sur Discord ou Telegram :

DISCORD : Syd#9907 - Discord Mina (https://discord.com/invite/Vexf4ED) (Vérifiez les tags : Genesis Founding Member - Community MVP, afin d'éviter de contacter un fake)

TELEGRAM : @Sydai

N'hésitez pas si vous avez des questions sur la Délégation, le Staking, la Pool, ou même sur Mina en général.

A bientôt et profitez de vos récompenses sur ce fabuleux projet qu'est MINA Protocol :)

Syd
