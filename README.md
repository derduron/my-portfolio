# IoT Fullstack Engineer Portfolio

Репозиторий содержит исходный код моего персонального сайта-портфолио, построенного на генераторе статических сайтов **Hugo** с использованием темы **Toha**.

## 🌐 Живая версия сайта
Вы можете посмотреть мое портфолио вживую по ссылке:
 **[https://derduron.github.io/my-portfolio](https://derduron.github.io/my-portfolio)**

## 🛠 Технологический стек проекта
* **Генератор:** Hugo (Extended) v0.161+
* **Тема шаблона:** Toha v4 (Hugo Modules)
* **Языковое окружение:** Go (Golang), Node.js (для сборки npm-зависимостей стилей)

## 💻 Локальное развертывание для разработки

Если вам необходимо запустить проект локально для внесения правок, выполните следующие команды:

1. Клонируйте репозиторий:
```bash
git clone https://github.com/derduron/my-portfolio
cd my-portfolio
```

2. Инициализируйте и скачайте модули Hugo/Go:
```bash
hugo mod tidy
```

3. Установите зависимости шрифтов и иконок темы:
```bash
hugo mod npm pack
npm install
```

4. Запустите локальный сервер разработки:
```bash
hugo server -w
```
Сайт станет доступен по адресу: `http://localhost:1313/my-portfolio/`
