Gitlab Runner
=========
[![Galaxy](https://img.shields.io/badge/galaxy-samdoran.gitlab_runner-blue.svg?style=flat)](https://galaxy.ansible.com/samdoran/gitlab_runner)

Install [GitLab Runner](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwiupsyYhZrjAhWQdN8KHSZ7DG4QFjAAegQIBRAC&url=https%3A%2F%2Fdocs.gitlab.com%2Frunner%2F&usg=AOvVaw30T7uu8OuWI1eaxx2M1S_M). Once installed, you will need to [register the runner](https://docs.gitlab.com/runner/register/index.html).

Requirements
------------

None

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `gitlab_runner_packages` | `['gitlab-runner']` | List of packages to install |


Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - samdoran.gitlab_runner

License
-------

Apache 2.0
