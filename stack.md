# Наш стек: 

Когда наш Head of Technology Антон пришёл в компанию, поисковый движок был на Ruby, а страницы рендерились с помощью PHP. Дело было в 2011 году, и сейчас от этого стека в компании ничего не осталось. 

### Бэкенд

В 2024 году бэкенд продуктовой разработки живет у нас преимущественно на **Go**. Шиной данных выступает **Kafka**, основным хранилищем у большинства команд является **PostgreSQL** либо **MongoDB**, а поисковой движок хранит результаты поиска в **Кvrocks**. 

### Фронтенд

Фронтенд мы пишем преимущественно на актуальном стеке **TypeScript** + **React**, **Node.js**. В качестве стейт-менеджера используем **Effector**. Часть страниц рендерится сервером на Elixir, есть участки легаси, но мы стремимся придти к единым инструментам для продуктовой разработки

### Дата-платформа

Наша дата-инженерная платформа написана на **Python** и **Scala**, из основных фреймворков у нас **Apache Spark**, **Apache Airflow**, **DBT**, **Trino**, **DataHub**. Платформа позволяет ML-инженерам и аналитикам быстро и удобно взаимодействовать с данными. 

### Инфраструктура

Инфраструктура Авиасейлс развернута в облаках. Все приложения запакованы в **Docker** и деплоятся в **Kubernetes**. Параметрами конфигураций K8s управляют сами разработчики. А благодаря **Terraform** они лучше понимают, что происходит с инфрой, и могут своими руками участвовать в её создании и изменении.

### Мобильные платформы

О мобильной разработке вы можете почитать в [разделе про наш iOS](iOS.md). Android-раздел на подходе! 