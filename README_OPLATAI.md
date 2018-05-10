# Oplatai website source code

Based on Feeling responsive theme. See README.md.

## Workflow
1. [Develop locally using Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
  - See also `_config_dev.yml`
2. Store to cloud, ask for review on Gitlab
  - `git@gitlab.com:oplatai-bussiness/website.git`  (remote named `origin`)
3. Approved changes and ready to public changes deploy to `gh-pages` branch on github
  - git@github.com:oplatai/oplatai.github.io.git (remote named `public`)

## Git remote setup
Please use following remote naming conventions

    oplatek@440:master:website$ git remote -v
    origin  git@gitlab.com:oplatai-bussiness/website.git (fetch)
    origin  git@gitlab.com:oplatai-bussiness/website.git (push)
    public  git@github.com:oplatai/oplatai.github.io.git (fetch)
    public  git@github.com:oplatai/oplatai.github.io.git (push)
    upstream        https://github.com/Phlow/feeling-responsive.git (fetch)
    upstream        https://github.com/Phlow/feeling-responsive.git (push)
