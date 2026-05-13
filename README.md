# Te Gao Academic Homepage

This is the GitHub Pages source for Te Gao's academic homepage, based on the `RayeRen/acad-homepage.github.io` Jekyll template.

## Local Preview

```bash
cd ~/GoatCsu.github.io
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

If Ruby reports a missing Bundler version, install the version shown in `Gemfile.lock`, or run `bundle update --bundler` in a clean Ruby environment.

## Deploy

Create a public repository named `GoatCsu.github.io`, then push this directory:

```bash
cd ~/GoatCsu.github.io
git init
git add .
git commit -m "Initialize academic homepage"
git branch -M main
git remote add origin git@github.com:GoatCsu/GoatCsu.github.io.git
git push -u origin main
```

GitHub Pages will publish the site at `https://GoatCsu.github.io/`.
