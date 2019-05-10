# MKdocs builder && Static runner

```bash
# Heroku:
heroku buildpacks:add https://github.com/plotly/heroku-buildpack-python -a docs-devel-org-ua
heroku buildpacks:add https://github.com/bielorusov/buildpack-mkdocs -a docs-devel-org-ua
heroku buildpacks:add https://github.com/heroku/heroku-buildpack-static.git -a docs-devel-org-ua
```
