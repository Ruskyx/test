meme_dict = {
            "PRESS F": "in genere utilizzato quando un personaggio muore eroicamente",
            "REFRESHARE": "quando si ricarica una paginadi un sito",
            "CRINGE": "Qualcosa di eccezionalmente strano o imbarazzante",
            "LOL": "Una risposta comune a qualcosa di divertente",
            
            }

parola = input("Scrivi una parola che non capisci (usa solo lettere maiuscole!): ")

if parola in meme_dict.keys():
    print(meme_dict[parola])
else:
    print("parola non trovata")
