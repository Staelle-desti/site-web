<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma page de connexion</title>
	<link href="page2.css" rel="stylesheet">
   
 
</head>
<body>

    <header>
        <h1>Validez votre commande</h1>
    </header>

    <section>
        <h2>Veuillez entrez vos informations personnelles</h2>
        <form action="#" method="post">
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
			
			<label for="name">Prenom :</label>
            <input type="text" id="name" name="name" required>

			<label for="telephone">Numéro de téléphone :</label>
            <input type="tel" id="telephone" name="telephone" required>


            <label for="email">E-mail :</label>
            <input type="email" id="email" name="email" required>
			
			<label for="name">Adresse :</label>
             <input type="text" id="adresse" name="adresse" required>
			
			<label for="name">Pays :</label>
             <input type="text" id="pays" name="pays" required>
			 
			 <label for="name">Code postal :</label>
             <input type="code" id="postal" name="postal" required>
             
			 <label for="name">Ville :</label>
             <input type="text" id="ville" name="ville" required>
			 
            <label for="message">Suggestion de message :</label>
            <textarea id="message" name="message" rows="4" required></textarea>
			

            <button type="submit"> <a href="page8.html">Envoyer</a> 
			</button>
        </form>
    </section>
	<button type="button"> <a href="site.html">Retour au menu</a> 
	</button>

</body>
</html>
