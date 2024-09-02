
# Descriptif du projet 
Je souhaite créer un projet Strapi innovant en utilisant l'IA pour remplir automatiquement certains champs. Pour cela, j'ai décidé d'utiliser n8n pour automatiser cette tâche en créant un lien entre les champs de mon projet Strapi et l'IA, afin de gagner du temps et d'améliorer l'efficacité de mon projet.

**Exemple 1 :** Pour écrire le descriptif d'un artiste, je vais utiliser Strapi pour créer un modèle de données qui contiendra les informations sur l'artiste, telles que sa description. Ensuite, j'utiliserai n8n pour automatiser la tâche de remplissage de ce champ, en utilisant l'IA pour générer un texte cohérent et précis. Cela me permettra de gagner du temps et de fournir un descriptif de qualité professionnelle pour l'artiste.

**Exemple 2 :** Pour décrire une image, je vais utiliser Strapi pour créer un modèle de données qui contiendra les informations sur l'image, telles que sa description. Ensuite, j'utiliserai n8n pour automatiser la tâche de remplissage de ce champs, en utilisant l'IA pour générer une description précise et détaillée de l'image. Cela me permettra de fournir des descriptions de qualité pour mes images sans avoir à les écrire manuellement.

**Exemple 3 :** Pour générer une image à partir d'une description, je vais utiliser Strapi pour créer un modèle de données contenant les informations sur l'image, telles que sa description. Ensuite, j'utiliserai n8n pour automatiser le remplissage de ce champ, en employant l'IA pour générer l'image. Cela me permettra d'obtenir des images pour mes descriptions sans avoir à les créer manuellement.

 # Technologie
## Strapi 
Strapi est un système de gestion de contenu (CMS) open source et headless, ce qui signifie qu'il fournit une interface d'administration pour gérer le contenu d'un site web ou d'une application, mais ne fournit pas de front-end. Il permet aux développeurs de créer des API REST ou GraphQL pour accéder au contenu et de le consommer dans n'importe quelle application ou site web.

Strapi est flexible, facile à utiliser et peut être personnalisé pour répondre aux besoins spécifiques d'un projet.

Les principales fonctionnalités de Strapi sont les suivantes :

1. Interface d'administration : Strapi fournit une interface d'administration conviviale pour gérer le contenu d'un site web ou d'une application.
2. API REST et GraphQL : Strapi permet aux développeurs de créer des API REST ou GraphQL pour accéder au contenu et de le consommer dans n'importe quelle application ou site web.
3. Gestion des utilisateurs : Strapi permet de gérer les utilisateurs et les rôles pour contrôler l'accès au contenu.
4. Personnalisation : Strapi est facilement personnalisable pour répondre aux besoins spécifiques d'un projet.
5. Sécurité : Strapi offre des fonctionnalités de sécurité avancées telles que la gestion des autorisations, la protection contre les attaques CSRF et XSS, etc.
6. Extensibilité : Strapi est extensible grâce à une communauté active qui contribue à l'ajout de nouveaux plugins pour étendre les fonctionnalités de base.
7. Multi-langues : Strapi permet de gérer facilement des sites web ou des applications multilingues.  

## n8n 
n8n est un outil open source de workflow d'automatisation qui permet de connecter différentes applications et services en utilisant des nœuds préconstruits pour créer des flux de travail automatisés. Il permet aux utilisateurs de créer des workflows personnalisés pour automatiser des tâches répétitives, telles que l'envoi de courriels, la création de tâches dans un outil de gestion de projet, la publication de contenu sur les réseaux sociaux, etc.

n8n est facile à utiliser et peut être personnalisé pour répondre aux besoins spécifiques d'un projet. Il est également extensible grâce à une communauté active qui contribue à l'ajout de nouveaux nœuds pour connecter de nouveaux services.

Les principales fonctionnalités de n8n sont les suivantes :

1. Connectivité : n8n permet de connecter différentes applications et services en utilisant des nœuds pré-construits pour créer des flux de travail automatisés.
2. Workflow Builder : n8n dispose d'un éditeur de workflow visuel qui permet de créer des workflows personnalisés en utilisant des nœuds pré-construits.
3. Automatisation : n8n permet d'automatiser des tâches répétitives en créant des workflows personnalisés.
4. Notifications : n8n peut envoyer des notifications par courriel, SMS ou Slack lorsqu'un événement se produit dans un workflow.
5. Intégration : n8n peut être intégré à d'autres outils de développement tels que Git, GitHub, Bitbucket, etc.
6. Personnalisation : n8n est facilement personnalisable pour répondre aux besoins spécifiques d'un projet.
7. Extensibilité : n8n est extensible grâce à une communauté active qui contribue à l'ajout de nouveaux nœuds pour connecter de nouveaux services.

## Hugging Face
Hugging Face est une entreprise spécialisée dans le développement de technologies d'intelligence artificielle (IA) pour le traitement du langage naturel (NLP). Elle est surtout connue pour sa plateforme open source de modèles de NLP pré-entraînés appelée "Transformers". Cette plateforme fournit des modèles de NLP pré-entraînés pour une variété de tâches, telles que la classification de texte, la génération de texte, la traduction automatique, etc. Les modèles de Hugging Face sont utilisés par des entreprises et des organisations du monde entier pour améliorer leurs produits et services basés sur le langage naturel. Hugging Face est également connue pour son engagement envers la communauté open source et pour sa contribution à la recherche en NLP.

Les principales fonctionnalités de Hugging Face sont les suivantes :

1. Plateforme de modèles de NLP pré-entraînés : Hugging Face fournit une plateforme open source de modèles de NLP pré-entraînés appelée "Transformers".
2. Modèles pour une variété de tâches : Les modèles de Hugging Face sont disponibles pour une variété de tâches de NLP, telles que la classification de texte, la génération de texte, la traduction automatique, etc.
3. Facilité d'utilisation : Les modèles de Hugging Face sont faciles à utiliser et peuvent être intégrés dans des applications et des services existants.
4. Haute performance : Les modèles de Hugging Face sont connus pour leur haute performance et leur précision.
5. Personnalisation : Les modèles de Hugging Face peuvent être personnalisés pour répondre aux besoins spécifiques d'un projet.
6. Engagement envers la communauté open source : Hugging Face est engagée envers la communauté open source et contribue régulièrement à des projets open source.
7. Recherche en NLP : Hugging Face est également connue pour sa contribution à la recherche en NLP et pour son engagement envers l'avancement de la technologie de traitement du langage naturel.

# Strapi 
## Création d'un projet Strapi 
**Guide s'installation officielle :**  https://docs.strapi.io/dev-docs/installation/cli
**Conditions préalables :** Node.js

**Installez Strapi en utilisant la commande suivante :** 
`npx create-strapi-app@latest strapiDemo`
- Nom du projet : strapiDemo
- Version de Strapi : 4
- Type d'installation choisie : Quickstart 
- Base de données utiliser : SQLite

## Lancer votre projet Strapi
Pour lancer votre projet Strapi placez vous dans le bon dossier
`npm run develop`
Lien local du projet : http://localhost:1337/admin 

Création de votre compte admin :
![1.png](/images/1.png)
- Email : strapi@gmail.com
- Password : Strapi321

### Strapi exemple 1 "Génération de la description de l'artiste"
**création de collection-Types "artiste" dans content-type-builder** 
![2.png](/images/2.png)
	
	Artiste contiendra deux champs : 
		- name (type : text ->short text)
		- description (type : text →Long text)
	Enregistrer les modifications 

**saisit des données dans "artiste"  grâce au content-manage**
![3.png](/images/3.png)
| Ps : n'oubliez pas de publier chaque entrée

![4.png](/images/4.png)



### Strapi exemple 2 "Génération de la description d'une image"
**création de collection-Types "postImageDescription" dans content-type-builder** 
![5.png](/images/5.png)

	postImageDescription contiendra trois champs : 
	- title (type : text ->short text)
	- description (type : text →Long text)
	- image (type : media → single media)
	
**saisit des données dans "artiste"  grâce au content-manage**
![6.png](/images/6.png)

### Strapi exemple 3 "Génération d'une image à partir d'une description "
**création de collection-Types "postDescriptionToImage" dans content-type-builder** 
![7.png](/images/7.png)
	postDescriptionToImage contiendra trois champs : 
	- name (type : text ->short text)
	- description (type : text →Long text)
	- image (type : media → single media)

**saisit des données dans "postDescriptionToImage"  grâce au content-manage**
![8.png](/images/8.png)

### Activation de l'API 
Pour accéder à l'API, il est nécessaire de créer un API Token. Pour cela, vous devez vous rendre sur :	Settings  → API Tokens →  Create new API Token
![9.png](/images/9.png)


- Name : ApiTokenFullAccess
- Token duration : Unlimited
- Token type : custom
- Accordez toutes les autorisations sur toutes les routes.

### Test de l'Api
URL :
- http://localhost:1337/api/artistes
- http://localhost:1337/api/post-image-descriptions
- http://localhost:1337/api/upload

Assurez-vous de saisir le Token API que vous avez créé.
Exemple 1 :
![10.png](/images/10.png)
Exemple 2 : 
![11.png](/images/11.png)
Exemple 3 : 
![12.png](/images/12.png)

# n8n
**Guide s'installation officielle :**  https://docs.n8n.io/hosting/installation/npm/
**Conditions préalables :** Node.js
**Installez n8n en utilisant la commande suivante :** 
`npm install n8n -g`
**lancer le projet** 
`sudo npx n8n`

## crée un workflow pour l'exemple 1 
*Name:  strapiDemo génération description*

**création d'un triggers qui déclenchera  le workflow**
Élément de listetype : Manually

**création d'un node Strapi ( get many entry)**
afin de se connecter il faut saisir le Token créé précédemment dans "Credential to connect with"
![13.png](/images/13.png)
dans le content Type saisir le nom de notre collection "artistes"
![14.png](/images/14.png)
**création d'un Flow if qui test si le champ description est vide et le champ name est non vide dans le but de remplir la description grâce a l'IA**
![15.png](/images/15.png)
**création d'un Flow Loop ower items**
![16.png](/images/16.png)
**création d'un node Basic LLM Chain à la sortie de loop** 
![17.png](/images/17.png)

**saisir Hugging Face Inference Model à la sortie du mode du LLM**
pour cela rendez vous sur le site https://huggingface.co/settings/tokens après  avoir crée votre compte et saisie la clé API dans Credential to connect with
![18.png](/images/18.png)
ensuite choisie le model mistralai/Mistral-7B-Instruct-v0.3 
![19.png](/images/19.png)

**création d'un node Data transformation → Edit Fiels dans le but de récupérer la description générer par l'IA** 
![20.png](/images/20.png)
**création d'un node Strapi ( update an entry)**
![21.png](/images/21.png)

**workflow entier :**
![22.png](/images/22.png)

### Résultat dans Strapi : 
![23.png](/images/23.png)

## crée un workflow pour l'exemple 2
*Name:  strapiDemo génération image description*

**création d'un triggers qui déclenchera  le workflow**
type : Manually

**création d'un node Strapi ( get many entry)**
afin de se connecter il faut saisir le Token créé précédemment dans "Credential to connect with"
![24.png](/images/24.png)
dans le content Type saisir le nom de notre collection "post-image-descriptions"
![25.png](/images/25.png)
**création d'un Flow if qui test si le champ description est vide et le champ image est non vide dans le but de remplir la description grâce a l'IA**
![26.png](/images/26.png)
**création d'un Flow Loop ower items**
![27.png](/images/27.png)
**création d'un node Basic LLM Chain à la sortie de loop** 
![28.png](/images/28.png)
**saisir Hugging Face Inference Model à la sortie du mode du LLM**
pour cela rendez vous sur le site https://huggingface.co/settings/tokens après  avoir crée votre compte et saisie la clé API dans Credential to connect with
![29.png](/images/29.png)
ensuite choisie le model mistralai/Mistral-7B-Instruct-v0.3 
![30.png](/images/30.png)
**création d'un node Data transformation → Edit Fiels dans le but de récupérer la description générer par l'IA** 
![31.png](/images/31.png)
**création d'un node Strapi ( update an entry)**
![32.png](/images/32.png)
**workflow entier** 
![33.png](/images/33.png)
### Résultat dans Strapi
![34.png](/images/34.png)

## crée un workflow pour l'exemple 3
*Name:  strapi génération d'image à partir d'une description*

**Création d'un triggers qui déclenchera  le workflow**
type : Manually

**Création d'un node Strapi ( get many entry)**
Afin de se connecter il faut saisir le Token créé précédemment dans "Credential to connect with"
![35.png](://images/35.png)
Dans le content Type saisir le nom de notre collection "post-description-to-images?populate=*"

![36.png](/images/36.png)

**Création d'un Flow if qui test si le champ description est non vide dans le but de crée une image grâce a l'IA**
![37.png](/images/37.png)

**Création d'un Flow Loop ower items**
![38.png](/images/38.png)

**Création d'un node HTTP Request à la sortie de loop de type Post**
![39.png](/images/39.png)

- Dans URL saisir votre API_URL qui est présent dans huggingface Inference API (serverless)
	- pour cela  rendez vous sur le site https://huggingface.co/models?pipeline_tag=text-to-image&sort=likes afin de choisir votre modèle. Pour cette exemple nous utilisons le modèle stabilityai/stable-diffusion-xl-base-1.0
![40.png](/images/40.png)
![41.png](/images/41.png)
- Ensuite choisissez  HuggingFaceApi comme Credential Type
- Créez la clé API sur le site https://huggingface.co/settings/tokens 
![42.png](/images/42.png)
- Activez send headers de type UsingJson  où vous allez insérez votre clé API crée précédemment 
`{"Authorization": "Bearer hf_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"}`
- Activez send Bondy 
```
Body Content Type = Raw
Content Type = json
Body = 
{
  "inputs": {{ $('getData').item.json.attributes.description }},
  "parameters": {
    "max_new_tokens": 64,
    "return_full_text": false,
    "num_return_sequences": 1,
    "do_sample": true,
    "temperature": 0.7,
    "top_k": 50,
    "top_p": 0.95,
    "repetition_penalty": 1.0,
    "length_penalty": 1.0,
    "use_cache": true,
    "model_name_or_path": "stabilityai/stable-diffusion-xl-base-1.0"
  }
}
```

**Création d'un node Http Request de type  dans le but de envoyer l'image générer dans Strapi** 
![43.png](/images/43.png)
![44.png](/images/44.png)
![45.png](/images/45.png)
![46.png](/images/46.png)


- Send Headers
	- Specify Headers
		- Using Fields Below
			- Header Parameters
				- Name = Content-Type
				- Value = multipart/form-data
- Send Body
	- Body Content Type
		- Form-Data
			- Body Parameters 1
				- Parameter Type = Form Data
				- Name = ref
				- Value = api::post-description-to-image.post-description-to-image
			- Body Parameters 2
				- Parameter Type = Form Data
				- Name = refId
				- Value = {{ $('Loop Over Items').item.json.id }}
			- Body Parameters 3
				- Parameter Type = Form Data
				- Name = field
				- Value = image
			- Body Parameters 4
				- Parameter Type = n8n Binary File
				- Name = files
				- Value = data

workflow entier 
![47.png](/images/47.png)
Résultat dans Strapi
![48.png](/images/48.png)
![49.png](/images/49.png)

## Importer les workflows JSON dans n8n des deux exemples ci-dessus :
Pour importer un workflow JSON dans n8n, suivez ces étapes :
- Accédez à votre instance n8n 
- Cliquez sur Add workfow 
![50.png](/images/50.png)

Sélectionnez import from file en cliquant sur trois petits points : Autres macros
![51.png](/images/51.png)

- Les workflows de n8n utilisés dans les exemples sont les suivants : 
- [strapi_generation_description.json](/images/strapi_generation_description.json)
- [strapi_generation_image_description.json](/images/strapi_generation_image_description.json)
- [strapi_generation_descrption_to_image.json](/images/strapi_generation_descrption_to_image.json)


# Comment utiliser un webhook pour générer du contenu grâce à l'IA lors de la réception d'une entrée ?
## Définition 
Un webhook est un moyen pour deux applications de communiquer entre elles en temps réel. Lorsqu'un événement se produit dans une application, elle envoie une notification à l'autre application via une requête HTTP. Cette notification peut contenir des données sur l'événement qui s'est produit, telles que des informations sur un nouvel utilisateur créé ou une commande passée.

Dans le contexte de n8n et Strapi, un webhook peut être utilisé pour envoyer des données de Strapi à n8n ou vice versa. 

## Les étapes pour créer un webhook entre n8n et Strapi
Tout d'abord, ouvrez votre compte n8n et créez un workflow.
![52.png](/images/52.png)

Ajoutez un nœud "Webhook" à votre workflow en cliquant sur le bouton "+" et en recherchant "Webhook" dans la barre de recherche
![53.png](/images/53.png)
Configurez le nœud "Webhook" en définissant un nom pour votre webhook (exemple : strapiWebhook) et en choisissant une méthode HTTP (GET, POST, PUT, DELETE) pour votre webhook, ici nous allons choisir la méthode Post
![54.png](/images/54.png)
Activer le webhook
![55.png](/images/55.png)
Copiez l'URL générée par le nœud "Webhook" et enregistrez-la pour une utilisation ultérieure.
![56.png](/images/56.png)

Ouvrez votre compte Strapi et accédez à la section "Webhooks" dans le menu principal.

- Cliquez sur le bouton "Créer un webhook" et configurez le webhook en définissant un nom, une URL et les évents .
- Collez l'URL générée par le nœud "Webhook" de n8n dans le champ "URL" du webhook Strapi.
- Enregistrez les modifications
- Vous pouvez maintenant utiliser votre webhook pour envoyer des données de Strapi à n8n ou vice versa.
![57.png](/images/57.png)


