### Create the Github repo
#### Let's install the hub gem to create a Github repo from your terminal without opening your browser (very useful when you are lazy 😉)

```gem install hub```

#### Now you can init(ialize) a git repository, commit your changes, and create the associated Github repo:

```git init
git add .
git commit -m "my profile page"
hub create # this creates the associated repo on Github!```
```

#### To open the Github repo from your browser you can run:

```hub browse```

### Github Pages
#### Github Pages is a sub-service of Github that makes it easy to deploy any static website in 10 seconds (static == not a Rails app). It is based on a "magic" branch, called gh-pages. When Github detects this branch, it puts your website online. Awesome right? Let's create this magic branch and push it. ✨🌿✨

```git co -b gh-pages
git push origin gh-pages # we push the gh-pages branch, not master!```
```

#### Now you can build the URL https://xiaohupei.github.io/wx-mini-app (this is the URL built automatically by Github) and have a look at your masterpiece online! Share the link on Slack with your buddies.
