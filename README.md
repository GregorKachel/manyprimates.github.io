# ManyPrimates new website

## Making changes to the content

- Edit the Markdown `.md` files. When you push changes to the remote repo, github will build the site (typically within a few minutes).
- Put images in the `assets/images` folder
- Use relative urls whenever possible, e.g. `pilot.html` instead of `https://manyprimates.github.io/pilot.html`
- **Do not touch the files in the folders that start with an underscore `_` unless you're sure you know what you're doing!**

## Setting up a local site to preview changes

- Have a clone of the github repo on your local machine
- Install Jekyll: `gem install bundler jekyll`
    - If that gives you any errors, google them... or check [here](https://jekyllrb.com/docs/installation/)
- `cd` into the git repo for the website
- Build local Jekyll site `bundle exec jekyll serve`
- Open browser and open `http://localhost:4000`
- You should see any changes you save on your local `.md` files (refresh)
- Push your changes when you're happy with the preview!

