# CV (сurriculum vitae) - документ, в котором соискатель описывает своё образование и опыт работы. В отличие от резюме, которое редактируется под требования каждой конкретной вакансии, в CV отображаются профессиональные достижения и навыки за весь период учёбы и работы.

# CV#1. Markdown & Git

## Порядок работы

1. В своём GitHub аккаунте создайте публичный репозиторий с названием `rsschool-cv`.
   В главной ветке данного репозитория (`main`) должен находиться только один файл `README.md`.
2. От ветки `main` создайте ветку `gh-pages`.
3. В процессе работы над проектом в ветку `gh-pages` необходимо сделать не меньше 3-х коммитов. Согласно [гайдлайну](https://docs.rs.school/#/git-convention) название каждого коммита должно начинаться с одного из перечисленных префиксов `init:`, `feat: `, `fix: `, `refactor: `, `docs:`.
4. В ветке `gh-pages` разместите файл `cv.md`.
5. Используя markdown-разметку в файле `cv.md` создайте своё CV.  
   Требования к содержанию CV и рекомендации к его составлению перечислены в [описании задания](cv.md#содержание-cv).
6. В файл `README.md` ветки `gh-pages` добавьте ссылку вида `https://GITHUB-USERNAME.github.io/rsschool-cv/cv`, в которой вместо `GITHUB-USERNAME` укажите свой никнейм на сайте GitHub. По этой ссылке должна открываться страница CV задеплоенная на GitHub Pages.
7. Создайте Pull Request из ветки `gh-pages` в ветку `main`.  
   Название Pull Request `Markdown & Git`  
   [Описание Pull Request дайте по схеме](https://docs.rs.school/#/pull-request-review-process?id=Требования-к-pull-request-pr).  
   Мержить Pull Request из ветки `gh-pages` в ветку `main` не нужно.
   
# CV#2. HTML, CSS & Git Basics
    
## Порядок работы
1. Работу ведёте в репозитории `rsschool-cv`, созданном при выполнении предыдущего задания [Markdown & Git](git-markdown.md)
2. От ветки `gh-pages` создайте ветку `rsschool-cv-html`
3. В процессе работы над проектом ведите историю коммитов. Следуйте [гайдлайну](https://docs.rs.school/#/git-convention), согласно которому название каждого коммита должно начинаться с одного из перечисленных префиксов `init:`, `feat: `, `fix: `, `refactor: `, `docs:`.
4. В ветке `rsschool-cv-html` разместите файлы `index.html` и `style.css`, предварительно добавив в них любое содержимое.  
Вёрстка и стилизация CV будет выполняться в следующем задании. 
5. В файл `README.md` ветки `rsschool-cv-html` добавьте ссылку `https://GITHUB-USERNAME.github.io/rsschool-cv/` в которой вместо `GITHUB-USERNAME` укажите свой никнейм на сайте GitHub.  
По этой ссылке будет открываться страницы CV в виде свёрстанной страницы.  
Саму вёрстку добавим в ходе выполнения следующего задания
6. Создайте Pull Request из ветки `rsschool-cv-html` в ветку `gh-pages`  
Название Pull Request `HTML, CSS & Git Basics`  
[Описание Pull Request дайте по схеме](https://docs.rs.school/#/pull-request-review-process?id=Требования-к-pull-request-pr).  
Замержите Pull Request из ветки `rsschool-cv-html` в ветку `gh-pages`
