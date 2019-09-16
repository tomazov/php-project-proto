# php-project-proto
Prototype for PHP Project with GitLab Pipeline, docker-compose.yml, docker images

# Usage
- Install submodule `git submodule add --name .gitlab-ci-functions -b master -- https://github.com/sysadmws/gitlab-ci-functions .gitlab-ci-functions`
- Substitute `__RUNNER_TAG__` with needed runner tag
- Set vars `DEPLOY_SERVER`, `DEPLOY_URL`, `DEPLOY_APP` for CI for scope `proto` or change `proto` env in CI for something else
- [Symfony Install](https://symfony.com/download)
- Update `.env` from symfony with `.env.addons`
- Use `make help` for make commands help for docker-compose preps
