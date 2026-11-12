# PolyPlan
Cheminement Interactif pour Baccalauréat à Polytechnique

[PolyPlan - Genie Mecanique](https://samuelguerinstud.github.io/PolyPlan/PolyPlan-Mecanique.html)

OBJECTIF:
	Simulateur interactif de cheminement du baccalauréat en génie mécanique. Il affiche l'arborescence des cours avec leurs préalables et corequis, pour planifier son parcours.

** Note: 
	L'application ne prend pas en compte les conditions de trimestres (si un cours se donne uniquement à l'automne par exemple), c'est donc à vous de le vérifier à l'aide du PDF de cheminement fourni par la Polytechnique.

** Modification:
Vous pouvez ajouter une session d'été en ajoutant un .5 après la session correspondante. Par exemple: pour une session d'été après le premier trimestre, mettre session 1.5 dans un cours et le programme ajoutera la session d'été automatiquement.


1. BOUTONS
- Ajouter un cours : ajoute un cours personnalisé à l'arborescence.
- Réinitialiser : remet tout à zéro.
- Sauvegarder JSON : exporte votre état (cours réussis/en cours) dans un fichier JSON.
- Importer : recharge un fichier JSON exporté.
- Restaurer : rétablit une sauvegarde précédente.

2. ÉTATS DES COURS (LÉGENDE)
- Réussi / Validé : cours complété, crédits comptés.
- Débloqué / Prêt à suivre : tous les préalables sont satisfaits.
- Débloqué ensuite : sera disponible après des cours en cours.
- Bloqué (préalables manquants) : préalables non satisfaits.
- En cours : cours en train d'être suivi.
- Sélectionné : cours cliqué pour inspection.

3. LIENS DE DÉPENDANCE
- Préalable direct : cours à réussir avant.
- Corequis : cours à suivre en même temps (ou avant).
- Débloquera plus tard : cours qui dépendent du cours sélectionné.

4. UTILISATION
	1. Cliquez sur un cours pour voir ses flux de dépendances.
	2. Marquez les cours réussis ou en cours; les états et crédits se mettent à jour automatiquement.
	3. Repérez les cours « prêts à suivre » pour choisir votre prochain trimestre.
	4. Modifiez les cours au choix et de concentration en utilisant le bouton « Modifier les paramètres du cours »
	5. Sauvegardez en JSON pour conserver votre progression.

 Pour récupérer votre progression, simplement appuyez le bouton « Restaurer » et sélectionnez le fichier JSON enregistré.


Fait par Samuel Guérin (90% Gemini 👍)
Si vous avez plus de questions, contactez moi par courriel au samuel.guerin@etud.polymtl.ca
