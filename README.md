<<<<<<< HEAD
# black-hat-ru

Русские переводы книг по наступательной безопасности (offensive security).

В репозитории — полные русские переводы двух книг: **Black Hat Rust** и **Black Hat Ruby**. Перевод сделан вручную, с сохранением структуры, нумерации глав, кода и иллюстраций оригинала.

---

## Что внутри

### Black Hat Rust

- **Оригинал:** <https://github.com/skerkour/black-hat-rust>
- **Автор:** Сильвен Керкур (Sylvain Kerkour)
- **Объём:** 14 глав + авторские права и предисловие (`ch00`–`ch14`)

| # | Глава |
|---|-------|
| 1 | Введение |
| 2 | Многопоточное обнаружение поверхности атаки |
| 3 | Полный газ с async |
| 4 | Модули с помощью объектно-трейтовых объектов (trait objects) |
| 5 | Обход веба для OSINT |
| 6 | Поиск уязвимостей |
| 7 | Разработка эксплойтов |
| 8 | Написание шеллкодов на Rust |
| 9 | Фишинг с помощью WebAssembly |
| 10 | Современный RAT |
| 11 | Защита коммуникаций сквозным шифрованием |
| 12 | Многоплатформенность |
| 13 | Превращаем наш RAT в червя для увеличения охвата |
| 14 | Заключение |

### Black Hat Ruby

- **Оригинал:** книга Сабри Хассаньяха (Sabri Hassanyah), ISBN 13: 9798687311946
- **Автор:** Сабри Хассаньях
- **Объём:** 17 глав + авторские права и предисловие (`ch00`–`ch17`)

| # | Глава |
|---|-------|
| 1 | Введение |
| 2 | Настройка среды Ruby |
| 3 | Ruby в терминале |
| 4 | Преобразование, извлечение и генерация строк |
| 5 | Работа с файлами |
| 6 | Криптография |
| 7 | Выполнение системных команд |
| 8 | Техники Red Teaming в Windows |
| 9 | Ruby Socket для хакеров |
| 10 | Сетевые сервисы и клиенты |
| 11 | Манипуляция сетевыми пакетами и атаки на протоколы |
| 12 | Работа с HTTP в Ruby |
| 13 | Охота и эксплуатация XSS с помощью автоматизации браузера |
| 14 | Эксплуатация веб-сервисов и API для C2 |
| 15 | Расширение и управление Burp Suite |
| 16 | Написание фаззеров и разработка эксплойтов |
| 17 | Разработка модулей Metasploit |

---

## Как это сделано

- Исходники перевода — Markdown, по главам: `rust/ch00.md` … `ch14.md`, `ruby/ch00.md` … `ch17.md`
- Иллюстрации оригинала — в `figures/`
- PDF собираются из Markdown с сохранением вёрстки и шрифтов оригинала
- Терминология унифицирована, английские термины оставлены как есть (они общеупотребительные в IT)

## Статус

| Книга | Главы | PDF | Вычитка |
|-------|-------|-----|---------|
| Black Hat Rust | 14 / 14 | готово | в процессе |
| Black Hat Ruby | 17 / 17 | готово | в процессе |

Нашли опечатку или кривой перевод? Открывайте **Issue** или присылайте **Merge Request** — правки принимаются.

---

## Что переводить дальше?

**Оставляйте комментарии прямо здесь — в Issues или Discussions.** Накидайте, какие книги и статьи стоит перевести следующими, и голосуйте лайком за нужное: возьму самый популярный запрос.

Что переводить дальше — пока не знаю. Решит этот раздел ваш рейтинг: скидывайте варианты прямо в комментариях, голосуйте лайком за интересующие, и я возьму в работу то, что окажется в топе.

Что имеет смысл перевести следующим? Пишите, обсудим.

---

## Поддержка

Перевод делается в свободное время, бесплатно и без регистрации. Если пригодилось — можно поддержать автора на USDT:

**Сеть:** Ethereum (ERC-20)
**Адрес:** `0x9a5134Ac44c22DDb832055A27032aDC7FD490E96`

> Отправляйте **только USDT (ERC-20) в сети Ethereum**. Перед отправкой убедитесь, что в кошельке выбран Ethereum Mainnet, а не BSC/Polygon/другая сеть — перевод в другой сети приведёт к потере средств.

---

## Правовая информация

Переводы принадлежат их авторам:

- © 2021 Sylvain Kerkour — *Black Hat Rust*
- © 2020 Sabri Hassanyah — *Black Hat Ruby*

Русский перевод сделан **неофициально**, исключительно в образовательных целях и для русскоязычного сообщества. Все права на оригинальные произведения принадлежат их правообладателям. Этот репозиторий не связан с авторами и не продаёт контент.

Все примеры в книгах приведены в учебных целях. Используйте полученные знания только там, где у вас есть явное разрешение — на своих машинах, в своей лаборатории или в рамках авторизованного пентеста.

## Лицензия

Перевод: см. файл `LICENSE` в корне репозитория. Исходный код примеров принадлежит авторам книг.
=======
# Black hat ru



## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

* [Create](https://docs.gitlab.com/user/project/repository/web_editor/#create-a-file) or [upload](https://docs.gitlab.com/user/project/repository/web_editor/#upload-a-file) files
* [Add files using the command line](https://docs.gitlab.com/topics/git/add_files/#add-files-to-a-git-repository) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/xzscripts-group/black-hat-ru.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

* [Set up project integrations](https://gitlab.com/xzscripts-group/black-hat-ru/-/settings/integrations)

## Collaborate with your team

* [Invite team members and collaborators](https://docs.gitlab.com/user/project/members/)
* [Create a new merge request](https://docs.gitlab.com/user/project/merge_requests/creating_merge_requests/)
* [Automatically close issues from merge requests](https://docs.gitlab.com/user/project/issues/managing_issues/#closing-issues-automatically)
* [Enable merge request approvals](https://docs.gitlab.com/user/project/merge_requests/approvals/)
* [Set auto-merge](https://docs.gitlab.com/user/project/merge_requests/auto_merge/)

## Test and Deploy

Use the built-in continuous integration in GitLab.

* [Get started with GitLab CI/CD](https://docs.gitlab.com/ci/quick_start/)
* [Analyze your code for known vulnerabilities with Static Application Security Testing (SAST)](https://docs.gitlab.com/user/application_security/sast/)
* [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/topics/autodevops/requirements/)
* [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/user/clusters/agent/)
* [Set up protected environments](https://docs.gitlab.com/ci/environments/protected_environments/)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thanks to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README

Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Choose a self-explaining name for your project.

## Description
Let people know what your project can do specifically. Provide context and add a link to any reference visitors might be unfamiliar with. A list of Features or a Background subsection can also be added here. If there are alternatives to your project, this is a good place to list differentiating factors.

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
>>>>>>> origin/main
