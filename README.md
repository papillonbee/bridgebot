# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgebot/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                     |    Stmts |     Miss |   Cover |   Missing |
|------------------------- | -------: | -------: | ------: | --------: |
| bridgebot/action.py      |       56 |        4 |     93% |35, 41, 69-70 |
| bridgebot/agent.py       |       59 |        8 |     86% |25-28, 40, 44, 48, 52 |
| bridgebot/dataencoder.py |       59 |        2 |     97% |    17, 22 |
| bridgebot/env.py         |       87 |       11 |     87% |48, 95, 101-103, 139, 142, 145-146, 149-150 |
| bridgebot/exception.py   |       22 |        7 |     68% |6, 10, 14, 18, 22, 26, 30 |
| bridgebot/observation.py |      194 |       23 |     88% |49-51, 54-57, 83, 89, 100, 107, 113, 115, 121, 125, 130-132, 139, 142, 147, 150, 193, 202 |
| bridgebot/util.py        |       25 |        0 |    100% |           |
|                **TOTAL** |  **502** |   **55** | **89%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/papillonbee/bridgebot/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgebot/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/papillonbee/bridgebot/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgebot/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Fpapillonbee%2Fbridgebot%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgebot/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.