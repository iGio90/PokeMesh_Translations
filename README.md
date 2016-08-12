PokéMesh translation project.

How to translate:

- Fork the repository

Step by step if you are going to create a new translation:
- Create the localized directory with the localized name (I.E values-fr for French, values-it for Italian, values-es for Spanish etc.)
- Copy and paste the two files with the original strings /values/strings.xml and /values/faq.xml in the new directory.
- Start the translations by leaving the key unmodified (I.E <string name="pokemesh_stop_scan">Stop scan</string> - pokemesh_stop_scan is the key and doesnt need translations. "Stop scan" is what you have to translate. Checkout the italian translation to understand the way)
- Create pull requests to submit your translations

Step by step if you are going to update an existing translation:
- On each update we will update the original resources inside the directory "values". The new strings will be added at the bottom of the file.
- Copy and paste the new strings to the bottom of the localized file
- Translate and submit with a new pull request

Additional notes:
- Resources that have the special key translatable="false" doesn't require translations. These strings will be added at the top of the original file and you don't have to copy paste them into your origianl file.
- Resources that include characters like %s or %d needs translations and you need to add them to your translations. (I.E there are %s around. would be translated in italian as follow (Italian): "Ci sono %s nei dintorni".)
- Translations that includes a ', must be precedeed by a slash. (I.E I'll buy some candies should be added as this: i\'ll buy some candies. An italian example: "L'app funziona" should be add as "L\'app funziona")

Get the app: www.pokemesh.com
