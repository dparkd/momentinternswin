# momentinterns.win
The main page for the moment intern side projects

***

# Background
There are two branches `master` and `gh-pages`. 

`gh-pages` branch is for the <http://momentinterns.win> page 
`master` branch is for the source code 

The source code is build using [Middleman](https://middlemanapp.com/) . 

***

# How to Deploy 

-Clone repository 
`git clone git@github.com:momentdesign/momentinternswin.git`

-Checkout master branch
`git checkout master`

-Make changes to the source code and push to master
```
git add .
git commit -m 'your changes'
git push origin master
```

-Build using middleman (From the master branch)
`bundle exec middleman bulid`

-cd into the build folder 
`cd build`

-Change into gh-pages 
`git checkout gh-pages`

-Add code and push to gh-pages
```
git add .
git commit -m 'changes and build'
git push origin gh-pages
```

DONE!



