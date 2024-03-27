{
  "posts": [
    { "id": 1, "title": "Post 1" },
    { "id": 2, "title": "Post 2" },
    { "id": 3, "title": "Post 3" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 },
    { "id": 2, "body": "some comment", "postId": 1 }
  ],
  "profile": {
    "name": "typicode"
  }
}

---

Create a json structure as above for the following resouces:

Pakbon
  Pakbon_id
  Naam (required)
  Voorletters (required)
  Achternaam (required)
  Emailadres (required)
  Organisatie 
  Telefoonnummer 
  Depot (required)
  xml_pakbon (files)
  zip_bestanden (files)
  gebruiker_id (belongs to 1 Gebruiker)
  project_id (belongs to 1 Project)

Gebruiker
  gebruiker_id
  achternaam
  voornaam
  emailadres
  telefoonnummer
  organisatie
  actief
  rol
  aangemaakt
  laatst_ingelogd

Project
  project_id
  naam
  omschrijving
  status
  aangemaakt
  gebruiker_id (belongs to Gebruiker)
