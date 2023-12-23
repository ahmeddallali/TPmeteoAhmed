# TP3+TP4
## Etape5
  ### -Spring Web :
    faciliter le développement d'applications web avaServer Faces, Spring MVC, prenant en compte les requêtes HTTP.
  ### Spring Data JPA :
    permet de gerer et faciliter la communication  avec la couche de données en utilisant des  annotations .
  ### H2 Database :
    Système de gestion de bases de données relationnelles qui facilite la tâche aux développeurs de faire les tests
    liés à la base des données sans avoir connecté à une base de données externe.
  ### Spring Boot DevTools :
    outils permet de faciliter et améliorer le développement des applications web (par exemple le compilation automatique de l'application
    aprés chaque modification ).
  ### Thymeleaf :
    C'est un moteur de template qui permet de créer et génerer des vues.
  ### Hibernate :
    c'est un framework qui permet de faciliter l'accès aux données en mappant les objets  aux tables de la base de données.
## Etape13
    1. On a paramétré l'url d'appel /greeting en utiliasant : @GetMapping("/greeting")
    2. On a choisi le fichier HTML à afficher avec : return "greeting"
    3. On a envoyé le nom à qui nous disons bonjour avec le second lien en utilisant  Model.addAttribute() qui remplace ${nomTemplate} par name 
## Etape17
    Création d'un nouveau tableau  address.
## Etape18
    la table Address a été crée automatiquement grace à l'annotation @Entity sur la classe 'Address' (annotation de l'Hibernate qui  permet de genérer 
    une table correspondant à une entité ) 
## Etape20
    Aprés l'execution de la requete select je peux voir tout le contenu de data.sql
## Etape22
    @Autowired:annotation utilisée pour effectuer l'injection de dépendances automatique. Elle peut être utilisée pour injecter des
    dépendances via des constructeurs, des setters ou des champs.
## Etape27
    oui on peut rajouter une navbar pour naviguer entre chaque page .
## Etape29
    Pour utiliser Bootstrap, j'ai telechargeé les fichiers css et js Bootstrap en provenance de la page officielle(version 4)et j'ai les mis dans 
    le dossier static de mon projet puis j'ai mis leurs paths  dans les pages où j'ai besoin de Bootstrap.

 
# TP4  
 ## Etape6
  1. Pour des raisons sécurité et du protection de l'API il est necessaire d'utilisation une clé API(token) pour accéder à MeteoConcept API 
  2. l'URL à utiliser est : [https://api.meteo-concept.com/api/forecast/daily/0?token=ca460ba21adb470f6a0507c0054f268729727475686382ff4a417da665a0bfe4](https://api.meteo-concept.com/api/forecast/daily/0?token=ca460ba21adb470f6a0507c0054f268729727475686382ff4a417da665a0bfe4)
  3. La méthode GET est utilisée pour obtenir les informations
  4. Les paramètres sont passés en ajoutant "&latlng=" puis le couple de valeurs séparées par une virgule.
  5. La température et Les prévisions météo  se trouvent dans la section  forecast.
## Lien Github : [https://github.com/ahmesd/TPAPI-DALLALI-AHMED.git](https://github.com/ahmeddallali/TPmeteoAhmed.git)https://github.com/ahmeddallali/TPmeteoAhmed.git

    

