# Hi boulder-fans,
this is a working algorithm for all boulder gyms, which are using the boulderado-services. You simply need to clone this project and store the new data in [Cities.csv](Cities.csv).
## Examples:
Have a look at my [GitHub Steinbock repository](https://github.com/bloedboemmel/Steinbock)
Also very fresh, but already working: [StudioBloc](https://github.com/bloedboemmel/StudioBloc)
## What you need?
- A boulder-gym website with some bars like this:
<img src="./png/Example.png">
- A GitHub-account with GitHub actions

## How do you start?
- Clone this project
- Visit your gym website and right-click on the colored bar, which indicates the visitors right now. Clickon inspect and search for the long link from boulderado. Copy it, but remoth the "&Ampel=1" -bit at the end.
- Save all your data in [Cities.csv](Cities.csv)
- Rename README.example.md to README.md and adjust your text. Don't override strings like "<!-- BEGIN UPDATINGDATA BOARD-->"
- Rename .github/_workflows to .github/workflows
- Change the cronjob to your needs in the .github/workflows/*.yaml -files
- Wait for your jobs to start!

