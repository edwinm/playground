# playground
Easily do proof of concepts and experiments

# Upgrade

Upgrade the playground to your own repository? First remove the playground repository,
then add your own repository.

```
git remote rm origin
git remote add origin https://github.com/<your-github-username>/<repository-name>.git
```

Update the information in `package.json` and recreate `package-lock.json`.

`npm install --package-lock`
