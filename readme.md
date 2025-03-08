# Setup development server  
Doc URL: https://itobuztech.github.io/nestkit-doc/

```
brew install hugo
git clone git@bitbucket.org:itobuztech/nest-starter-template-docs.git or 
git submodule init 
git submodule update
hugo server
```

# Public doc 
```
git branch -D gh-pages
git checkout --orphan gh-pages 
HUGO_ENV=production hugo  -d docs  --minify --baseURL="https://itobuztech.github.io"
git add .
git commit -m "Deploy site"
git push github gh-pages --force
```