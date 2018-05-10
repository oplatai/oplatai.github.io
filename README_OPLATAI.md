# Oplatai.com website source code

Based on Feeling responsive theme. See README_FEELING_RESPONSIVE.md.

# Dev docs

## Workflow
1. [Develop locally using Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
  - See also `_config_dev.yml`
2. Store to cloud, ask for review on Gitlab
  - `git@gitlab.com:oplatai-bussiness/website.git`  (remote named `origin`)
3. Approved changes and ready to public changes deploy to `master` branch on github (`master` branch is used for organization site, `gh-pages` for project site)
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

## [Custom domain docs](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)
- Follow the guide for github but mainly you need to configure DNS names for `wedos`

          * 1800	A	192.30.252.154
          * 1800	A	192.30.252.153
        vps	1800	A	185.8.165.173

1. Go to https://client.wedos.com/dns/
2. Select domain
3. `Editace DNS zaznamu`
4. Change the names
5. Do not forget to `Aplikovat zmeny`
6. Wait for DNS to update. (Check it via `dig +noall +answer oplatai.com`)

original DNS records for `wedos` hosting

    1800	A	46.28.105.3
		1800	AAAA	2a02:2b88:1:4::17
	*	1800	A	46.28.105.3
	*	1800	AAAA	2a02:2b88:1:4::17
