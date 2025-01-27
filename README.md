# Museum landing page
Implement landing page according to [Figma design](https://www.figma.com/file/cRBCqE06cDrY3s4jX7h3iY/%D0%9D%D0%90%D0%9C%D0%A3-(Edit)?node-id=0%3A1) - Use BEM and SCSS

Check font styles. Use [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans?query=ibm), [Montserrat](https://fonts.google.com/specimen/Montserrat?query=mon)

- Large screens 2560px
- Full HD 1920px
- The design 1600px
- Notebook 1280px
- Tablet 1024
- Mobile (> 320px)

1. Implement the header with hamburger menu.
1. Implement `Художній Музей` block.
1. Implement `Актуальні події` block with two similar blocks `Йду і повертаюсь`, `І спогади і мрії`.
1. Implement `Від класицизму до романтизму` block.
1. Implement `Галерея` block and slider.
1. Implement `Підписка` block.
1. Implement footer.

## HR important moments

- Скорость анимаций на всем лендинге одинаковые (например увеличение при наведении или выезд блоков при скроле)
- Placeholder в формах подсказывают что именно ввести, а если стоит валидация формы, то понятно в каком формате вводить номер телефона 
- Убедитесь, что с мобильных выглядит все аккуратно и без горизонтальной прокрутки
- Добавьте favicon
- Добавьте мягкий скрол при клике на меню до соответствующего блока страницы
- Кнопки "відвідування" и "квитки" должны вести на блок с актуальными событиями
- Кнопка "про нас" должна вести на дайджест
- Для пользователя удобно, когда при клике на Address, он открывался в новой вкладке в гугл-картах
- Кнопки фейсбук и инстаграм внизу страницы должны  быть кликабельными и вести на страницы музея в соцсетях (и открываться в новой вкладке)
- Картинки в галерее и в событиях должны увеличиваться при ховере
- В мобильной версии нужно сделать слайдер, чтобы юзер смог просмотреть все картинки в галерее


## Github flow
1. **Fork** the repo.
2. **Clone** the forked one. (The project link should have your name but not `mate-academy`)
3. Run `npm install` (or just `npm i`).
4. Run `npm start`.
5. Open one more terminal window for the next steps.
6. `git checkout -b develop` - to create new branch and switch on it.
7. Write you code in `src` folder.
8. Run `npm run lint` and fix code style errors.
9. Run `npm run deploy` to deploy your solution to `gh-pages`.
10. `git add . && git commit -m 'solution'` to save your changes.
11. `git push origin develop` - to send you code for PR.
12. Create a Pull Request (PR) from your branch `develop` to branch `master` of original repo.
13. Replace `<your_account>` with your Github username in the
  [DEMO LINK](https://<your_account>.github.io/Museum/).
14. Copy `DEMO LINK` to the PR description.

> To update you PR repeat steps 7-11.
