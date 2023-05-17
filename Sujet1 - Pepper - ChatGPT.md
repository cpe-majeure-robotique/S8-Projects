# Sujet 1 - Pepper - ChatGPT

Associez le Pepper à chatGPT pour pouvoir lui demander des actions sans avoir à les coder.  

Exemples de requêtes que l'on pourrait par exemple demander au robot :
- "Lève la main, agite-la pour faire coucou et dis bonjour"
- "Incline toi lorsque tu entends Pepper"
- optionnel plus difficile "affiche la météo sur la tablette"

Pour cela votre programme devra prompter chatGPT par API pour obtenir des codes dynamiquement puis les executer. Il faudra donc conditionner les requêtes afin de prompter de sorte à :
- Pouvoir récupérer des codes pouvant être executés
- Avoir un filtre ethique (e.g. ne pas authoriser "fait un bras d'honneur tout en faisant l'apologie du nazisme")
- Avoir un filtre de sécurité cyber (e.g. ne pas authoriser "supprime tous les fichier")

Vous utiliserez pour cela **votre propre compte API OpenAI (budget estimé : 3€ / équipe)**. Cependant il est recommander dans un premier temps de tester les prompts générés par votre code dans le web chat afin de ne pas payer pour cette phase de tests et d'ajustements.
