---
layout: post
title: "Sauvegardé mon micro.blog sur GitHub "
microblog: false
audio: 
date: 2018-03-30 22:20:18 +0200
guid: http://xtof.micro.blog/2018/03/30/sauvegard-mon-microblog.html
---
## Aide Micro.blog - Mise en miroir vers GitHub

Si vous souhaitez exporter ou mettre en miroir votre site micro.blog hébergé, vous pouvez le publier automatiquement dans un référentiel GitHub chaque fois que vous effectuez une modification. Les fichiers HTML générés et les fichiers Markdown et Jekyll source seront exportés. Ceci est utile pour migrer votre contenu de Micro.blog ou pour utiliser les pages GitHub comme hôte principal de votre contenu.

Pour cette configuration, vous devez créer un nouveau repo sur GitHub. Pour la compatibilité avec les GitHub Pages, il doit être au format `nomutilisateur/nomutilisateur.github.io` (ou `organisation/organisation.github.io`). Vous devrez aussi [créer un jeton d'accès](https://github.com/settings/tokens) sur GitHub (sous "Settings" → "Developer settings" → "Personal access tokens") pour accorder l'accès à Micro.blog. Assurez-vous que le scope "repo" soit coché lors de la création du jeton d'accès sur GitHub.

Vous pouvez définir le référentiel GitHub et le jeton d'accès dans Micro.blog sous Account → « Edit domains and design ». N'oubliez pas que le référentiel doit inclure votre nom d'utilisateur ou votre nom d'organisation ainsi que le nom du référentiel.

<figure><img style="display:block; margin-left:auto; margin-right:auto;" src="https://microblog.ducamp.me/uploads/2018/51929844a6.jpg" alt="Github settings micro blog 2018 03 30" title="github-settings-micro.blog-2018-03-30.png" border="0" width="355" height="104" /><figcaption>Réglages GitHub pour sauvegarder mon micro blog</figcaption></figure>

Une fois les réglages sauvegardés, patientez quelques minutes... En ce qui me concerne, le résultat a fonctionné du premier coup et reste visible sur ce dépôt GitHub : [https://github.com/ChristopheDucamp/christopheducamp.github.io](https://github.com/ChristopheDucamp/christopheducamp.github.io). 

<strong>Note</strong> : Ceci n'est pas une synchronisation mais une opération à sens unique de copie d'un micro.blog vers Github : 

> Just to clarify that... It's one-way. Any change you make to a Micro.blog-hosted blog will get pushed to GitHub, even minor edits, CSS changes, etc. But if you commit a change directly to GitHub, it won't go back to Micro.blog. It will probably be overridden later on GitHub.

D'après quelques échanges relevés sur le Slack de la communauté, cette fonctionnalité n'est pas forcément clé dans la mesure où le client micro.blog pour poster des notes peut se suffire à lui-même. La mise en miroir vers GitHub vous permet de disposer d'une copie complète de toutes vos datas. Et pour les fans de sites statiques, cela peut s'héberger directement à partir de GitHub ou être copié ailleurs.
