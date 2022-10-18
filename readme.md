# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
First, create your codespace by going to https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=549023708 and clicking the "Create Codespace" button and wait for it to boot.
Then, in the terminal, enter the command "docker-compose up" to load the front end and back end.
Next, verify the back end is working by going to https://obelusfamily-anythink-market-5i6i2-5xx49pv5pgphpxx-3000.githubpreview.dev/api/ping and verifying the output.
Finally, make sure the front end and back end are talking by creating a new user at: https://obelusfamily-anythink-market-5i6i2-5xx49pv5pgphpxx-3001.githubpreview.dev/register
