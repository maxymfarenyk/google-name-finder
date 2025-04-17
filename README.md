# Google-name-finder

Веб-застосунок, що дозволяє знайти статті на вікіпедії про людей із твоїм іменем доступний за [посиланням](https://google-name-finder-doc.onrender.com/)

## 1. Deploy application to some cloud

Веб-застосунок було розгорнуто у хмарному середовищі Render.

## 2. Deploy as a containter unit

Спершу було стоврено Docker образ за допомогою Dockerfile локально (за допомогою ```docker build```), після цього образ було закинуто на dockerhub та розгорнуто у Render як ```Deploy from Docker```.

## 3. Configure CI/CD

Було створено файл за шляхом ```.github/workflow/deploy.yml```, за допомогою якого автоматично запускається деплой кожного разу, коли у github пушаться нові коміти.
