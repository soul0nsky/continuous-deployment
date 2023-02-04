# continuous-deployment

# 1. Рабочее окружение

[![Github Actions](https://github.com/soul0nsky/continuous-deployment/actions/workflows/web.yml/badge.svg)](https://github.com/soul0nsky/continuous-deployment/actions/workflows/web.yml)

[![Build status](https://ci.appveyor.com/api/projects/status/s2u6giegy70ny66w?svg=true)](https://ci.appveyor.com/project/soul0nsky/continuous-deployment)

### Continuous Deployment

#### Описание

Воспользуйтесь пошаговой инструкцией ниже, чтобы развернуть тестирование, сборку и deployment на GitHub Actions и GitHub Pages.

В качестве шаблона для развёртывания используйте [проект](https://github.com/netology-code/ahj-code/tree/master/env).

Не забудьте поставить бейджик со статусом в `README.md`.

**В качестве результата пришлите проверяющему ссылку на ваш GitHub-проект.**

### Инструкция

1. Скачать репозиторий <https://github.com/netology-code/ahj-code/tree/master/env>
2. Создать новый репозиторий на github
3. Скопировать в новый репозиторий папку `env`
4. Настроить новый репозиторий. Указать в нём использование GitHub Action для публикации приложения, вместо публикации из ветки (gh-pages)
   ![alt text](./github-setup.png)
5. В файле `README.md` в строке:
