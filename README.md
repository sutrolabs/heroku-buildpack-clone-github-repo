Environment variables:
----------------------
* GITHUB_REPO: `<org/repo>`, e.g. 'sutrolabs/heroku-buildpack-clone-github-repo'
* GITHUB_AUTH_TOKEN: `<your-token>` (create a [personal access token](https://github.com/settings/tokens) with minimal scope permissions for this)

Install:
--------
Replace `--app` and environment variables with appropriate values:
```
heroku buildpacks:add --app <app> https://github.com/sutrolabs/heroku-buildpack-clone-github-repo
heroku config:set --app <app> GITHUB_REPO=<org/repo> GITHUB_AUTH_TOKEN=<token>
```
