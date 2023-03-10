# USC Lira Lab
USC Lira Lab's website, hosted on GitHub Pages!

## Developing the Website
To develop, **you must do your work on the `source` branch**. `main` is autogenerated via a `rake` job (you can see the details in `Rakefile`). The `source` branch contains all the Jekyll code. To do this, simply execute
```
git checkout source
```

## Publishing the Website
When you've made the desired changes and are in the `source` branch, simply execute:
```
rake publish
```
If you want commit with a custom commit message, do:
```
rake publish["custom commit message\, and this is how to use a comma"]
```

This will rebuild the site, commit your changes to the `source` branch, and deploy the generated site to the `main` branch. GitHub Pages will pick up on this change and update `usc-lira.github.io` with the new changes.

**NOTE**: This GitHub Pages link is the where the `liralab.usc.edu` proxies point to, so this repository and the corresponding GitHub Page is the "actual" website.
