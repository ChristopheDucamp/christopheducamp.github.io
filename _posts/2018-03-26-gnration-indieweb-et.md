---
layout: post
title: "Génération IndieWeb 4 et domaines hébergés"
microblog: false
audio: 
date: 2018-03-26 21:37:46 +0200
guid: http://xtof.micro.blog/2018/03/26/gnration-indieweb-et.html
---
Convaincu par les arguments de [Manton Reece](https://manton.org/) pour essayer le service [micro.blog](https://micro.blog).  

## Génération IndieWeb 4 et domaines hébergés

([Source : IndieWeb generation 4 and hosted domains](http://www.manton.org/2018/03/indieweb-generation-4-and-hosted-domains.html))

> Naturellement et en raison des objectifs de Micro.blog, je vois beaucoup de discussions sur la "possession de votre contenu". C'est un élément important de la mission de Micro.blog que de prendre le contrôle des réseaux sociaux fermés et financés par la publicité et d'accepter à nouveau de poster sur nos propres blogs.

> Mais que signifie posséder notre contenu ? Devons-nous installer WordPress ou un système de blogging développé en interne pour qu'il soit considéré comme une véritable propriété de contenu, où nous avons le code source et l'accès direct SFTP au serveur ? Non. Si c'est notre définition, la propriété du contenu sera réservée en permanence aux programmeurs et aux techniciens qui ont des heures à consacrer à la configuration du serveur.

> [IndieWebCamp a un tableau des générations](https://indieweb.org/generations) illustrant le cheminement des adopteurs précoces aux utilisateurs traditionnels. Eli Mellen soulignait [dans un post récent](https://eli.li/entry.php?id=20180318015703) la nécessité de combler le fossé entre les aspects techniques des outils IndieWeb et les plateformes plus accessibles. Avec Micro.blog spécifiquement, l'objectif c’est la "génération 4" et je pense que nous sommes sur la bonne voie pour y parvenir.

> Je veux que la publication de blog soit aussi facile que de tweeter. Rien de moins n'est suffisant pour Micro.blog. Vous remarquerez que lorsque vous utilisez Twitter, ils ne vous demandent jamais d'accéder à SFTP à l’intérieur de twitter.com afin de configurer votre compte. Ils ne vous demandent pas d'installer quoi que ce soit.

> Des logiciels plus puissants que vous pouvez personnaliser sans cesse auront toujours leur place. Il est bon d'avoir une gamme d'options, y compris de l'open source à bricoler. C'est souvent là que commencent certaines des meilleures idées. Mais trop souvent, je vois des gens se perdre dans les mauvaises herbes des plugins et des thèmes, attirés par le mythe selon lequel vous devez vous auto-héberger avec WordPress pour faire partie de l'IndieWeb.

> Posséder votre contenu ne concerne pas les logiciels portables. Il s'agit d'URLs et de données portables. Cela concerne les noms de domaine.

> Lorsque vous écrivez et publiez des photos sur votre propre nom de domaine, votre contenu peut survivre à n'importe quelle plateforme de blogging. Ce mois-ci c’était le 16ème anniversaire de mon blog sur manton.org. Et durant cet intervalle j'ai changé plusieurs fois de plateformes de blog et de fournisseurs d'hébergement. Les messages et les URLs peuvent tous être conservés lors de ces modifications, car il s'agit de mon propre nom de domaine.

> J'ai été déçu quand Medium a annoncé qu'ils [cessaient de soutenir les noms de domaine personnalisés](http://web.archive.org/web/20180301231401/https://help.medium.com/hc/en-us/articles/115005579728-Get-started-with-custom-domains). Je suis lié à la copie de l’Archive Internet parce que la page d'aide de Medium à ce sujet n'est plus disponible. Si leur politique est toujours « pas de domaines personnels »  , c'est un revers pour le web ouvert, et ça condamne Medium à la même impasse que les URL `twitter.com/nomutilisateur`.

> Si vous ne pouvez pas utiliser votre propre nom de domaine, vous ne pouvez pas le posséder. Votre contenu sera toujours coincé dans ces URLs silos, sujet aux caprices de la timeline algorithmique et des priorités changeantes de l'équipe de direction.

> En ce qui concerne les blogs hébergés sur Micro.blog, nous encourageons tout le monde à associer un domaine personnalisé à son contenu, nous lançons un SSL gratuit et conservons les redirections pour les anciens messages sur le contenu WordPress importé. Nous pouvons faire plus.

> Je travaille maintenant sur la prochaine version de l'app macOS pour Micro.blog, qui comporte plusieurs comptes et même plusieurs blogs sous le même compte. Voici une capture d'écran de l'écran des paramètres :

<img style="display:block; margin-left:auto; margin-right:auto;" src="https://microblog.ducamp.me/uploads/2018/cb45a7eef6.jpg" alt="Macos microblog prefs accounts" title="macos-microblog-prefs_accounts.png" border="0" width="512" height="415" />

> L'objectif de Micro.blog n'est pas d'être un fournisseur d'hébergement temporaire, avec des utilisateurs vraiment "sérieux" qui finissent par passer à autre chose (bien que nous rendions cela si facile). Nous voulons que l'hébergement Micro.blog soit la meilleure plate-forme pour posséder votre contenu et participer aux communautés Micro.blog et IndieWeb.


## Statut

(edit : 2018-04-01)
Parti sur un essai gratuit de 10 jours afin d'explorer quelques fonctionnalités indieweb pour relancer un site personnel délaissé sur une motorisation statique. Les premiers pas ont été parfois difficiles, mais j'ai été très aidé grâce aux ressources et astuces publiées dans le <a href="https://microblogging.slack.com/">slack de la communauté</a> et sur la page [micro.blog sur le wiki indieweb](https://indieweb.org/microblog).

À cette heure, j'en suis encore à parcourir les très bonnes <a href="http://help.micro.blog/">pages d'aide</a>. Redirection CNAME facile pour pointer un sous-domaine personnel hébergé che Gandi. (`microblog` pointe `micro.blog/xtof`)

### Principaux bégaiements :  
- la publication croisée et le rendu des copies sur POSSE FB et twitter me donne parfois quelques surprises (besoin de pratiquer)... 
- [Sauvegarde sur GitHub pré-configurée Jekyll](https://github.com/ChristopheDucamp/christopheducamp.github.io) mais étouffée par un import d'une timeline d'un flux twitter incomplet 
- Suivi d'utilisateurs du service en cours. À l'écoute mais je prends le temps avant de me lancer dans l'interaction. Selon la [page micro.blog indieweb](https://indieweb.org/micro.blog#Criticism)

> les webmentions sortantes sont entièrement prises en charge, mais seules les webmentions entrantes des sites qui se sont enregistrés sur le service en utilisant leur URL de base d'envoi. 

Aussi, ce cherche des débutants à qui pouvoir parler en français pour explorer le système de conversations par webmentions.

### UI MarsEdit 
Sinon je suis ravi de retrouver une interface de publication agréable dans l'éditeur [MarsEdit](http://ducamp.me/MarsEdit) que je ne peux que recommander pour publier votre micro.blog. 

## Conclusion 
Pour conclure, en attendant l'<a href="https://mikehaynes.blog/2018/03/29/i-havent-had.html">app micro.blog Android</a>, je compte m'équiper d'un iPhone pour essayer l'[app iOS](http://ducamp.me/Micro.blog#Apps). Et je (chrono)rêve déjà de bricolages de workflows de publication moderne pour publier sur le web !

<img style="display:block; margin-left:auto; margin-right:auto;" src="https://microblog.ducamp.me/uploads/2018/7b5e7135de.jpg" alt="Slackjamstatic fr 2018 03 30" title="Slackjamstatic-fr 2018-03-30.png" border="0" width="170" height="248" />


## Pourquoi nous rejoindre sur Micro.blog  

Parce qu'il y trop peu de français sur l'indieweb ! Et que Micro.blog est un excellent moyen de démarrer facilement sur l'IndieWeb quelle que soit votre <em>génération</em>.

<img style="display:block; margin-left:auto; margin-right:auto;" src="https://microblog.ducamp.me/uploads/2018/caedea49bf.jpg" alt="Indieweb generations diagram" title="indieweb-generations-diagram.jpg" border="0" width="324" height="252" />

1. **Voulez-vous essayer l'IndieWeb sans domaine ?** Si vous n'avez pas de nom de domaine mais que vous voulez essayer certaines des fonctionnalités de l'IndieWeb, vous pouvez créer un compte micro.blog, suivre les gens là-bas et répondre aux messages à la fois sur micro.blog et ailleurs sur l'IndieWeb. Si vous décidez d'acquérir un nom de domaine, micro.blog vous aidera à faire la transition en utilisant son site (voir 2), ou même à exporter vos posts vers un nouveau site vous appartenant à partir duquel vous pourrez connecter votre compte micro.blog (voir 3).
1. **Vous disposez d'un nom de domaine mais n'avez pas encore de site ?** Si vous n'avez pas de site principal, vous pouvez enregistrer un domaine et le connecter à micro.blog comme service d'hébergement pour un montant mensuel minimal. Micro.blog vous permettra ensuite de publier facilement des [notes](https://indieweb.org/note), [articles](https://indieweb.org/article), [photos](https://indieweb.org/photo) et d'autres types de messages. S'ils le choisissent, il existe une excellente importation/exportation leur permettant de migrer relativement facilement entre les plateformes.
1. **Vous avez déjà un site ?** Si vous disposez déjà d'un site principal sur un autre service ou une autre plateforme, vous pouvez facilement syndiquer son contenu (via [RSS](https://indieweb.org/RSS) ou [JSON](https://indieweb.org/JSON)) dans le service micro.blog. Et vous pouvez utiliser le lecteur du service pour interagir avec d'autres utilisateurs tout en possédant vos propres contenus et en recevant des réponses/commentaires via webmention. Si leur site supporte également micropub, ils peuvent utiliser le service pour composer leur contenu et le [micropublier](https://indieweb.org/Micropub) sur leur propre site, après quoi le contenu apparaîtra sur micro.blog via un flux.




[3]:[web.archive.org/web/20180...](http://web.archive.org/web/20180301231401/https://help.medium.com/hc/en-us/articles/115005579728-Get-started-with-custom-domains)


