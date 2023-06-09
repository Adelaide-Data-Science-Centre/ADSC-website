The quarto files in this folder are the website pages.

After edits, you can check on the website appearance by knitting `index.qmd` or *building* the project (Cmd-Shift-B). For best results, open `website.Rproj` so that you work in the correct project.

## How to edit

-   Clone the project on your local machine
-   Make edits (most often in either the data documents or in the webpages quarto documents (one for each page). Note quarto is similar to markdown in formatting
-   Render locally (using R Studio, needs to be a recent version)
-   This should update files in the docs folder
-   Push changes to Github, which should update on website within 10 minutes.

## Website Appearance and Navbar

-   Set in `_quarto.yml`.
-   If you make a new page, look under `navbar:` in `_quarto.yml` and add your page.

## Structure (May '23)

-   data documents, e.g. spreadsheet of members, in `./resources`
-   webpages: `index`, `Our People`, `Industry Partners`, `Events`, `Work With Us`.
