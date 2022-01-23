# Portfolio 

# To build the project
    yarn run build

# To preview the project
    yarn run preview

# To deploy to github-pages
    yarn run build
    git add dist -f
    git commit 
    git subtree push --prefix dist origin gh-pages
    git reset HEAD~