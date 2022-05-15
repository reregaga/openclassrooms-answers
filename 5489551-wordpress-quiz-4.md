[Quiz](https://openclassrooms.com/en/courses/5489551-creez-un-site-moderne-et-professionnel-avec-wordpress-5/exercises/4094)
# Personnalisez les contenus et le design d'un site WordPress

## Question 1
**Quel est l'intérêt de définir une charte graphique avant de se lancer dans le design d'un site ?**
- [x] Garantir la cohérence du design
- [ ] Définir la structure des pages
- [x] Définir l'ambiance graphique du site
- [ ] Définir l’expérience utilisateur
- [x] Valider la direction graphique avec le client

_La charte graphique va permettre de définir l'ambiance graphique et de la faire valider par le client, tout en posant les guidelines qui permettront d'avoir un design cohérent sur toutes les pages. La charte graphique ne définit en revanche pas la structure des pages ni l’expérience utilisateur (appelée aussi UX)._

## Question 2
**Combien de polices de caractères différentes est-il recommandé de trouver sur une page ?**
- [x] Entre 1 et 3
- [ ] Entre 3 et 6
- [ ] Plus de 6

_Tout comme pour les couleurs, il faut limiter le nombre de polices différentes utilisées sur une page. Sinon, à moins d'être un graphiste chevronné, vos pages vont vite ressembler à un sapin de Noël !_

## Question 3
**Où est-il préférable de paramétrer les tailles, couleurs et polices de caractères utilisées ?**
- [ ] Dans l’onglet Style des modules Elementor
- [x] Dans les options du thème

_Toujours dans l'optique d'être cohérent sur toutes les pages du site, il est préférable de définir ses polices de caractères et ses couleurs une fois pour toutes dans les options du thème, plutôt que de les configurer sur chaque élément dans votre page builder. Vous me remercierez le jour où un client vous demandera par exemple de changer les polices de tous les titres une fois toutes les pages déjà réalisées. ;-)_

## Question 4
**Combien d'occurrences de titre de premier niveau (H1) est-il recommandé d'avoir sur une page ?**
- [x] 1 seule
- [ ] 2 à 3
- [ ] Plus de 3

_Il ne faut qu'une unique occurrence de titre de niveau 1 sur vos pages. Attention, d'ailleurs, pour les articles de blog, le thème génère en général ce titre automatiquement, et il ne faut donc pas utiliser de titres H1 dans la zone de contenu._

## Question 5
**Je souhaite insérer une image en arrière-plan d’une section Elementor. Comment le paramétrer ?**
- [ ] Avec le module Image d'Elementor
- [x] Dans les options de style de la section

_Le module “Image” d’Elementor va créer un bloc HTML de type image &lt;img&gt;. Or, une image d'arrière-plan n'est pas un bloc HTML indépendant, c'est une image appliquée en arrière-plan d'un autre bloc HTML (généralement une section)._

## Question 6
**Toujours dans cette même section, je souhaite ajouter de la marge interne pour donner plus d’espace à mon image. Sur quel paramètre dois-je jouer ?**
- [x] Le padding
- [ ] Le margin

_C’est le padding (marge interne). La marge externe (margin) augmenterait l’espace à l’extérieur de la section, ce qui aurait l’effet inverse de celui souhaité, puisque la section, et donc l’image, rétréciraient._

## Question 7
**Toujours dans cette section, je souhaite maintenant créer un bouton faisant scroller vers la section suivante de ma page. Quelles solutions s’offrent à moi ?**
- [ ] Ajouter une classe “section1” à la section et mettre “.section1” dans le champ Lien de mon bouton
- [x] Ajouter un ID “section1” et mettre “&num;section1” dans le champ Lien de mon bouton

_Eh oui, une ancre HTML (permettant de scroller à un endroit précis d'une page) cible un ID CSS particulier. Elementor propose aussi le module "Ancre de menu" pour créer facilement un élément HTML avec l'ID souhaité, mais il est plus propre de passer par un ID de section, puisque cela nous évite d’ajouter un module supplémentaire._

## Question 8
**Mon client Le Caviste Bordelais souhaite une section présentant un carrousel de témoignages clients facilement administrable. J’ai trouvé une extension qui répond à ce besoin. Où chercher les paramètres de cette extension une fois celle-ci installée ?**
- [ ] Dans le customizer
- [x] Dans une rubrique dédiée du dashboard WordPress
- [ ] Dans la rubrique Extensions du dashboard WordPress
- [ ] Dans Elementor

_Les plugins génèrent généralement une rubrique supplémentaire dans votre dashboard WordPress. Celle-ci peut parfois être "cachée" dans "Réglages", "Outils", ou d'autres rubriques de premier niveau, ce qui fait qu'il est souvent nécessaire d'explorer le menu d'administration pour la retrouver !_

## Question 9
**Je souhaite maintenant ajouter mes témoignages clients dans la page Elementor. L’extension n’a pas généré de module “Témoignages” dans Elementor ; est-il tout de même possible d’insérer mes témoignages dans Elementor ?**
- [x] Oui
- [ ] Non

_Oui, Elementor permet d’insérer au choix des shortcodes (module Shortcode) ou des widgets (que vous retrouverez dans la section “WordPress” des modules Elementor)._

## Question 10
**Le design de mes témoignages clients ne convient pas à mon client, et il me demande de le personnaliser. Quelles solutions s’offrent à moi ?**
- [ ] Modifier le code du plugin
- [ ] Modifier le fichier styles.css du thème
- [x] Modifier le fichier styles.css du thème enfant
- [x] Ajouter des règles CSS dans Apparence &gt;&gt; Personnaliser &gt;&gt; CSS personnalisé

_Il ne faut surtout pas modifier le code d'un thème ou d'un plugin, les modifications seraient perdues lors de la prochaine mise à jour de ce dernier ! Il faut donc soit passer par un thème enfant, soit utiliser le champ “CSS personnalisé” du customizer._