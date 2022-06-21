# jfxs / Demo Gitlab-ci Robot Framework

[![Software License](https://img.shields.io/badge/license-GPL%20v3-informational.svg?style=flat&logo=gnu)](LICENSE)
[![Pipeline Status](https://gitlab.com/fxs/demo-gitlab-ci-robot-framework/badges/master/pipeline.svg)](https://gitlab.com/fxs/demo-gitlab-ci-robot-framework/pipelines)
[![Robot Framework Tests](https://fxs.gitlab.io/demo-gitlab-ci-robot-framework/all_tests.svg)](https://fxs.gitlab.io/demo-gitlab-ci-robot-framework/report.html)

An example of project to run [Robot Framework](https://robotframework.org/) tests in a [Gitlab-ci](https://docs.gitlab.com/ce/ci/) pipeline.

Last test report is published with Gitlab pages and is available [here](https://fxs.gitlab.io/demo-gitlab-ci-robot-framework/report.html).

## Run tests locally (debug)

In order to run tests locally you need docker and make.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

Example to run Robot Framework tests in your current directory:

```shell
# To show available commands:
make
# Example: to run Selenium tests with Chrome browser:
make tests-local browser=gc
```

## Authors

* **FX Soubirou** - *Initial work* - [Gitlab repositories](https://gitlab.com/users/fxs/projects)

## License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. See the [LICENSE](https://gitlab.com/fxs/docker-robot-framework/blob/master/LICENSE) file for details.
