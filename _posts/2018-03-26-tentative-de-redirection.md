---
layout: post
title: "Domaine personnel vers un micro.blog : premier essai peu concluant"
microblog: false
audio: 
date: 2018-03-26 21:53:30 +0200
guid: http://xtof.micro.blog/2018/03/26/tentative-de-redirection.html
---
Après les paramétrages Gandi, redirection de mon instance micro.blog vers un sous-domaine personnel à partir de l'UI. 

## Les instructions en bref

(Extraite de [micro.blog - Help - Custom domains]([help.micro.blog/2015/cust...](http://help.micro.blog/2015/custom-domains/) "Permalink to Micro.blog Help - Custom domains"))

(...) 
Si vous hébergez votre <em>microblog</em> avec un plan payant de Micro.blog, envisagez de pointer un domaine personnalisé. Cela pourrait être quelque chose ressemblant à  `microblog.votredomaine.com` ou même juste `votredomaine.com`. Mapper un domaine personnalisé sur Micro.blog est inclus gratuitement dans le plan, dès que vous aurez enregistré votre domaine. (Regardez [DNSimple](https://dnsimple.com/r/9fc1dd2e59824b) si vous cherchez à enregistrer un nouveau domaine.

Pour démarrer, mettez à jour votre enregistrement DNS pour pointer vers Micro.blog. Les instructions pour ça dépendront de votre registrar, mais tous les registrars supporteront les types standards d’enregistrements : "A" et "CNAME".

Si vous voulez utiliser un sous-domaine tel que `microblog.votredomaine.com` ou  `www.votredomaine.com`, créez un enregistrement "CNAME" quel que soit l’endroit où vous hébergez votre domaine et utilisez la valeur `nomutilisateur.micro.blog` (en prenant soin de remplacer `nomutilisateur` par votre propre nom d’utilisateur).

Après avoir mis à jour vos enregistrements DNS, cliquez sur « Account » dans la barre de menu de  Micro.blog, puis faites défiler jusqu'à « Paids microblogs" et cliquez sur « Edit Domains & Design". À côté du nom de l’hôte (Hostname) auquel vous souhaitez mapper un domaine personnalisé, cliquez sur le bouton « Edit. Remplissez ensuite le nom d'hôte (par exemple `microblog.votredomaine.com`) que vous souhaitez utiliser pour votre site.

## Essai avec Gandi : 

Pour Gandi, j’ai donc ajouté la ligne suivante dans les enregistrements DNS afin de faire pointer le sous-domaine `microblog.ducamp.me` vers le service :

    `microblog 10800 IN CNAME xtof.micro.blog.`
