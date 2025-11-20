# FgSite

Update Github Pages like this 

git add .
git commit -m "..."
git push
npx ng build --configuration production --base-href="/fg-site/"
npx angular-cli-ghpages --dir=dist/fg-site/browser
