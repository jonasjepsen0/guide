# Git templates

Git templates er filer/mapper som automatisk kopieres ind når du opretter et nyt repository.
Det kan være en god idé at bruge et template hvis du over flere forskellige repositories vil bruge en bestemt mappe struktur eller filer.

## Opsætning

Start med at oprette et template:

1. Naviger til et eksisterende git repository.
2. Under generelle indstillinger ser du en "Template repository" checkbox.
3. Her trykker du bare på checkboxen og din template er oprettet.

## Brug af template

Via GitHub.com:
  1. Gå til template repoet, klik den grønne "Use this template", "Create a new repository"
  2. Vælg navn, owner og visibility, klik Create repository

  Via CLI:

  gh repo create mit-projekt --template owner/template-repo --public
