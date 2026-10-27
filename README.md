# Atlas website

Play at https://kmarchais.github.io/atlas/.

The game source lives in [kmarchais/geography-game](https://github.com/kmarchais/geography-game). This repository holds only the Pages deployment workflow. It builds an explicitly verified source commit and publishes an artifact, without committing generated website files.

The API and database remain on Cloudflare Free. Publishing here does not copy or replace the database. Set the ATLAS_API_URL repository variable to the HTTPS API. Run Publish Atlas with the source commit and its successful build, hosting, and Android verification run.
