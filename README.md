# mpsamp.open - MP Multiplayer website

Live at **https://mpsamp-open.github.io**

The site source (pages, downloads, regions.txt) lives in [ThirtyFoxMCx00E1/wagu](https://github.com/ThirtyFoxMCx00E1/wagu) (`docs/` + the release files).
This repo only publishes it: `.github/workflows/deploy.yml` checks wagu every 10 minutes and redeploys when there is a new commit. wagu is private, so it is read with a read-only deploy key (secret `WAGU_DEPLOY_KEY`) and only the public site files are published: the pages, the downloads, the HiveMQ kit, the Day Z models / mapping, the media and the GIFs.

Discord: https://discord.gg/tbsDknk34y
