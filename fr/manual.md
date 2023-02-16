# Aide

## Recherche simple

Depuis la page d’accueil, vous pouvez saisir un terme pour lancer une recherche simple dans l’ensemble des procès-verbaux.

L’axe chronologique vous permet de restreindre votre recherche à une période précise.

## Recherche avancée

La recherche approximative prend en compte aussi des mots similaires aux mots-clés.

Vous pouvez également utiliser les options de recherche avancée suivantes:

- Recherche d’une expression (mot ou phrase) exacte en utilisant les guillemets\
Exemple: “Canton de Zurich”
- Recherche par métacaractères: ? (caractère unique), * (plusieurs caractères), ~ (recherche approximative)\
Exemples: Z?rich, Zur*, Zurich~
- Opérateurs booléens: && (AND), || (OR), ! (NOT)\
Exemples: Canton && Berne, Berne || Zurich, Canton !Ville (ou Canton AND Berne, Berne OR Zurich, Canton NOT Ville)

## Liste de résultats

La liste de résultats affiche les procès-verbaux dans lesquels apparaît le terme recherché.

En cliquant sur le procès-verbal de votre choix, vous ouvrez le document à l’endroit de la première occurrence.

L’algorithme de recherche calcule la pertinence des résultats sur la base des correspondances trouvées sur chaque page (plus il y a de correspondances, plus la page est pertinente). La liste des résultats affiche les pages qui contiennent les termes recherchés. Il est donc possible qu’un procès-verbal apparaisse plusieurs fois dans la liste si le système a trouvé des correspondances sur différentes pages du même document.

## Répertoire chronologique

Les procès-verbaux sont classés par ordre chronologique. La recherche par date vous permet d’accéder facilement à un procès-verbal spécifique.

![Écran d'impression "Recherche par date"](/md/assets/fr-scrn-browser.png)

## Présentation interactive (vue détaillée)

La consultation des procès-verbaux se fait via le visionneur [Archival IIIF](https://archival-iiif.github.io/){target="_blank"} (IIIF = [International Image Interoperability Framework](https://de.wikipedia.org/wiki/International_Image_Interoperability_Framework){target="_blank"}).

Basé sur le moteur de navigation de [Mirador](https://projectmirador.org/){target="_blank"}, ce visionneur offre différentes fonctionnalités:

- Affichage en parallèle de l’original numérisé et du texte retranscrit par le logiciel OCR
- Correspondance ligne par ligne entre le texte manuscrit et le texte retranscrit par le logiciel OCR
- Options de zoom et de navigation dans les pages
- Possibilité de faire défiler les pages du document
- Possibilité de sauter d’une page à l’autre
- Possibilité d’effectuer des recherches à l’intérieur du document
- Possibilité de télécharger le texte retranscrit par le logiciel OCR ou les procès-verbaux au format PDF

![Écran d'impression Mirador](/md/assets/fr-scrn-mirador.png)
HTR: reconnaissance de l’écriture manuscrite (*handwritten text recognition*)\
OCR: reconnaissance optique de caractères (optical character recognition)
