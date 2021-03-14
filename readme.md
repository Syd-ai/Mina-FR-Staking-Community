# GUIDE - Mina-FR-Staking-Community

DISCORD : Syd#9907 - Discord Mina (https://discord.com/invite/Vexf4ED) - Tags : Genesis Founding Member - Community MVP

TELEGRAM : @Sydai

MINA PROTOCOL : https://minaprotocol.com/

MINA TOKENOMICS : https://minaprotocol.com/blog/mina-token-distribution-and-supply


Bonjour,

Je suis gestionnaire de nodes et validateur depuis quelques temps sur de nombreux projets crypto (Avalanche, Nyzo, Idena, Bismuth, Stafi, Certik, Zelcash, Stakenet etc.) et depuis peu, "GFM" (Genesis Founding Member) sur Mina. J'ai été sélectionné également durant le dernier testnet pour recevoir une délégation de la Fondation Mina (Top 100) et fais partie des "Community MVP".

**Mon but est donc de proposer un pool de staking MINA pour la communauté FR**. Il s'agit d'un pool accessible avec pour vous un contact français actif. Je ne souhaite pas m'étendre à l'international étant donné que mon objectif est principalement de garder un contact privilégié avec les personnes me faisant confiance pour déléguer leur Mina. Vous pourrez ainsi me contacter sur Discord ou Telegram à tout moment, en communiquant en Français. Inversement, je vous contacterai pour transmettre toute information importante ayant trait au Staking sur MINA.

Le Block Producer (BP) sera mis en place sur un **serveur de haute qualité** et bénéficiera d'un **monitoring permanent**. Aucun Snark-Worker ne sera en fonction sur la machine. Très actif sur le projet, je suis également les développements, mis à jour et forks de près. La délégation vous permet ainsi de staker vos MINA en toute sérénité, sans que vous n'ayez rien à ne vous soucier.

***Ma commission est de 5% et NE CHANGERA PAS pendant 4 ans (jusqu'au 31 mars 2025)***. 

Mon pool de staking dispose aujourd'hui d'un stake de **3,906,975 Mina (0,48 %)**. Il fait partie du top 10 actuel (https://mina.staketab.com/) et **vous garantit ainsi un résultat moins aléatoire et lissé, puisque vous serez rémunéré à hauteur de votre participation dans le pool**.

J'effectuerai les paiements grâce au script de garethtdavies#4963 (https://docs.minaexplorer.com/minaexplorer/calculating-payments) de façon mensuelle et également sur requête personnelle. Le calcul est simple : si par exemple le pool mine un block avec une récompense totale de 200 MINA, il sera d'abord déduit 5% (10 MINA) de commission. Les 190 MINA restants seront ensuite redistribués à hauteur de la contribution de chacun dans la pool.


Pour staker vos MINA, il faut déléguer à l'addresse suivante :
**B62qnR6HKx34NCyDkSeRcJ44KATjUCs4xmQYDbwTXPJPQ4J6ebfeQe4**

Il n'y a pas de wallet GUI pour le moment, il faudra donc utiliser les commandes CLI suivantes :

`mina account unlock -public-key $MINA_PUBLIC_KEY`

`mina client delegate-stake \
    -receiver B62qnR6HKx34NCyDkSeRcJ44KATjUCs4xmQYDbwTXPJPQ4J6ebfeQe4 \
    -sender $MINA_PUBLIC_KEY \
    -fee 0.1`

($MINA_PUBLIC_KEY ou votre clé publique).

Attention, ne m'envoyez pas vos fonds. En délégant, vous gardez intégralement le contrôle sur vos MINA.

Vous pouvez également mettre fin à la délégation à tout moment (notez qu'il y a un délai protocolaire de 1 ou 2 époques selon les cas).

Idéalement, prenez au préalable contact avec moi sur Discord ou Telegram :

DISCORD : Syd#9907 - Discord Mina (https://discord.com/invite/Vexf4ED) (Vérifiez les tags : Genesis Founding Member - Community MVP, afin d'éviter de contacter un fake)

TELEGRAM : @Sydai

N'hésitez pas si vous avez des questions sur la Délégation, le Staking, la Pool, ou même sur Mina en général.

A bientôt!

Syd
