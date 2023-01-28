Les differentes etapes pour la base de données :
1: Telechargez et installez MongoDBCompass
2: Se connecter à une base de donnée 
3: creez une Database et creer deux table (User et Marker)
4: Importez un fichier CSV telechargez sur OSM, pour importez données (localisation) sur la map  


Dans le fichier Map api se trouve mon API avec avec toute mes methodes.
Pour le connectez a la BD que vous venez de creez sur MongoDB :
1: Ouvrer le fichier Map-API dans un editeur de code 
2: Depliez "Models" et ouvrez le fichier "DbConfig"
3: Dans la fonction Mongoose.connect remplacez le lien le lien localhost par le lien de votre BD pour les connectez


Pour afficher le site :
1: Copiez la path du fichier HTML et collez le dans votre navigateur et le tour est jouer
