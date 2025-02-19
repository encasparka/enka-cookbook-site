---
weight: 21
title: "Commencer !"
description: "Créer un compte et s'y connecter"
icon: "article"
date: "2024-01-18T13:59:39+01:00"
lastmod: "2024-01-18T13:59:39+01:00"
draft: false
toc: true
zoomable_img: true
gallery: true
---
<!-- {{< load-photoswipe >}} -->


## Inscription / Connexion
En cliquant sur le bouton de la barre de menu en haut du site, vous pouvez créer un compte ou vous connecter à l'interface d'édition si vous avez déjà un compte. 

### Création d'un compte github
Pour s'inscrire sur ce site, il vous faut un compte github (plateforme hébergeant le site).
- Cliquez sur "se connecter"
- Puis sur "se connecter avec Github"
- Créez un compte github avec le lien "create an account"
- Renseignez le formulaire d'inscription
- Autorisez "netlify" 
- Si une erreur est affichée, c'est pas grave. Fermez la page d'erreur et retournez sur la page de [connexion](/admin). Acceptez de créer un "fork" (actualisez la page si ça ne vous est pas proposé). Cela vous permettra de commencez à proposer des modifications au site sans avoir de compte authentifié (voir plus bas), mais les modifications que vous proposerez devront être validées par le compte administrateur du site avant d'être publiées sur le site.


{{< img-grid 
  from="content" 
  match="img/connexion/*connexion*" 
  size="12 lg:4" 
  >}}


### Compte authentifié
Une fois votre compte github créé, complétez le formulaire pour obtenir un compte authentifié. Les comptes authentifiés peuvent directement publier ou modifier des recettes, créer des évenements, etc, sans modération préalable. 

Une fois la demande effectuée, vous recevrez un email vous signalant que vous avez été invité à collaborer au site encas-parka/enka-cookbook-site (le traitement des demandes de comptes se fait manuellement, vous devrez peut-être patienter quelques jours avant de recevoir cet email.). Cliquez sur le lien pour acceptez l'invitation. Vous serez redirigé·e vers votre compte github: acceptez l'invitation. 

Vous pouvez fermer la page github, et vous connecter à enka-cookbook. Vous pouvez maintenant avoir accés au bouton "publier" sur les pages d'édition, et à la colonne "prêt" sous l'onglet "Flux". Voir ["publier des recettes"](/docs/editer/recettes/#publier-une-recette).

{{< img-grid 
  from="content" 
  match="img/connexion/*auth*" 
  size="12 lg:4" 
  >}}


## L'interface d'édition
{{< figure src="/docs/editer/commencer/img/cms-recettes.jpg" alt="Decap-cms" width="90%" >}}
Depuis l'interface d'édition, vous pouvez créez ou modifier une recette, un événement, un ingrédient, etc.

{{< bs/row >}}  
{{< bs/col >}}
{{< card title="Les recettes" content="Ajouter, modifier, dupliquer une recette" link="/docs/editer/recettes" >}}
{{< /bs/col >}}
{{< bs/col >}}
{{< card title="Les événements" content="Ajouter, modifier, dupliquer un événement/menu" link="/docs/editer/evenements" >}}
{{< /bs/col >}}
{{< bs/col >}}
{{< card title="Autres données" content="Ajouter des ingrédients, catégories, etc." link="/docs/editer/autres" >}}
{{< /bs/col >}}

{{< /bs/row >}}
