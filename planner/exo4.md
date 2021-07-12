# Exo 4

<ins>Elements de réponse :</ins>

Il faut configurer un **reverse-proxy** (nginx ?). De plus, les services de multiplications et d'additions disposeraient chacun d'une plage de ports.

Par exemple, on pourrait avoir : <br>

-   add: 3000-3999 : 3000
-   mult: 4000-4999 : 3000

Le reverse-proxy serait chargé de rediriger les requêtes aux services concernés.

