# Etude_de_marche

Grâce à la récolte des données, des méthodes de clustering et une analyse en composantes principales, 
nous avos ressorit 7 pays potentiels d'ecportation des poulets de la Poule qui chante.<br><br>

Nous avons accompagné l'entreprise agroalimentaire la Poule qui chante dans l'identification des pays les plus propices à l'exportation de ses poulets.<br>
Pour cela, nous avons d'abord collecté et analysé des données sur 192 pays.<br>
Nous avons utilisé des techniques de clustering pour regrouper les pays en 4 groupes  distinct.<br>
Enfin, une analyse en composantes principales nous a permis d'avoir 3 axes d'analyse : 
<ul> 
  <li>Le niveau économique</li>
  <li>La disponibilité alimentaire</li>
  <li>La capacité de production</li>
</ul>
La projection des groupes sur les composantes principales nous a permis de faire ressortir 2 cluster pertinent.<br>
4 pays cibles et 3 pays potentiels ressortent de cette démarche.

# Clustering
<h2>Définition du nombre de cluster avec le score de silhouette</h2>
<img width="1326" height="654" alt="image" src="https://github.com/user-attachments/assets/835b51d2-15d9-4c05-97cb-6e838384bf6d" />
<br>
<h2>Application de KMeans sur notre jeu de données</h2>
<img width="1234" height="644" alt="image" src="https://github.com/user-attachments/assets/a04b4329-15b7-42eb-ad2e-ccace570296d" />
<h2>Caractéristiques des 2 clusters principaux</h2>
<img width="908" height="620" alt="image" src="https://github.com/user-attachments/assets/ce5196fb-75ed-4641-b7dd-74f20b28fc4d" />

# Analyse en composantes principales
<h2>Définition du nombre de composantes</h2><br>
Choix de créer 6 composantes principales pour avoir au moins 80% variance expliquée<br><br>
<img width="1390" height="627" alt="image" src="https://github.com/user-attachments/assets/17f18c6f-2b4e-4047-b5f5-cc2f6e8e5576" /><br>
<h2>Choix des composantes principales</h2><br>
Nous avons retenu 3 composantes principales majeurs :
<ul>
  <li>PC1 : Niveau économique</li>
  <li>PC2 : Disponibilité alimentaire</li>
  <li>PC3 : Capacité de production</li>
</ul>
<h2>Projection des clusters sur nos composantes princiaples</h2>
La projection nous permet de faire ressortir 2 clusters pertinent<br>
<img width="818" height="674" alt="image" src="https://github.com/user-attachments/assets/ad3cacf3-6820-4784-8417-b8a2b5514c79" /><br><br>
On termine donc avec 4 pays cible et 3 pays potentiels en ajoutant un filtre avec nos critères : 
<ul>
  <li>PC1 positif</li>
  <li>PC2 négatif</li>
  <li>PC3 autour de 0</li>
</ul>
<img width="890" height="821" alt="image" src="https://github.com/user-attachments/assets/e829dc2c-d39b-4ba2-be57-1a6b8fb92cf4" /><br><br>
<img width="1218" height="687" alt="image" src="https://github.com/user-attachments/assets/396172b1-0e32-4cd3-aaa9-ec041c680766" />

