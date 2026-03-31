# ReViSE

## Welcome aboard!

Set course for **Europa**, Jupiter’s icy moon. More than 600 million kilometers from Earth, the adventure begins: exploration, cooperation, and discovery will be your driving forces.

**ReViSE** is a board game designed by the **Euro Space Center (ESC),** in collaboration with the **University of Namur** and **B12 Consulting**.

An online version will now accompany the physical board game, allowing a more immersive experience.
This repository contains the latest version of the backend and frontend of the online version of ReViSE. 

The frontend repository is available at: https://github.com/ReViSE-EuroSpaceCenter/ReViSE-frontend

The backend repository is available at: https://github.com/ReViSE-EuroSpaceCenter/ReViSE-backend

Both repositories are referenced as submodules in this repository, allowing for easy management and automatic deployment of the latest versions of both components.

## Update the submodules

To update the submodules, simply run the following command in the root directory of this repository:

```bash
git submodule update --remote --merge
```

This command will fetch the latest changes from the remote repositories of both the frontend and backend submodules and merge them into your local copy.

## Deployment

The deployment of the online version of ReViSE is automated using GitHub Actions. Whenever changes are pushed to the main branch of the main repository, the latest versions will be automatically deployed to the production environment.

## Documentation
Detailed documentation and wiki for the project can be found in the [ReViSE Wiki](https://github.com/ReViSE-EuroSpaceCenter/ReViSE/wiki).
