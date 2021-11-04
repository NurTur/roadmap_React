# Webpack vs create-react-app https://medium.com/@imbudhiraja/webpack-vs-create-react-app-cb72c47f8100

Webpack и react-scripts немного отличаются.

1) `Модуль Bundler против пакета NPM`

Webpack - это сборщик модулей, тогда как react-script - это пакет npm с зависимостями. Проект на основе react может потребоваться для быстрого запуска проекта, 
такого как babel, и webpack в списке react-script зависимостей.

2) `Environment контроль`

Приложение Create-react-app объявляет «нет конфигурации сборки», и они имеют в виду , что вы не можете настроить этот инструмент. Если вы хотите что-то добавить или изменить, вам нужно «eject». Запуск «npm run eject» выводит все файлы конфигурации, так что вы можете редактировать их самостоятельно.
Тогда как в случае с webpack, вы имеете полный контроль среды разработки. Вы можете настроить свои конфигурации в соответствии с вашими потребностями.

3) `Server Side Rendering`

Реализация ssr в приложении Create-react-app - головная боль.

4) `Сопровождение проекта`

При использовании Webpack вы полностью отвечаете за обновление и поддержание конфигураций веб-страниц. Для create-react-app все управляется сообществом React.

5) `Знание webpack как навык`

Заключение
Приложение Create-react-app лучше всего подходит для небольших проектов, этого не всегда достаточно для более крупных и сложных приложений.



