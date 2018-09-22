# People

Right now this repo serves as a placeholder for self-publishing members of the foundation. Translation: when new content is compiled into HTML, profile information is taken from this repo.

Example:
[Segah Mir](https://github.com/Keetro/people/blob/master/authors/segah.json)
```
{
  "name": "Segah A. Mir",
  "email": "segah@caura.co",
  "description": "...",
  "url": "https://segah.me",
  "teams": {
    "caura": {
      "name": "Caura & Co.",
      "email": ...
    },
    "payments": {
      "name": "PaymentsBI Consulting",
      ...
    }
  }
}
```
Key important details based on current design of the CMS:
1) **emails** are used to pull profile images from gavatar. If you want an image for your organization, please setup a gravatar profile for the team email
2) each post is associated with at least one team
3) **commentary articles** *(the ones where you are consolidating the research, rather than producing your own 100% original article)* only display team image
