<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <link href="Site.css" type="text/css" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <title></title>
</head>
<body>
    <div class="page-body">
        <div class="page-head">
            <div class="ref-container">
                <a href="#lab1">Лабораторная №1</a>
                <a href="#lab2">Лабораторная №2</a>
                <a href="#lab3">Лабораторная №3</a>
                <a href="#lab4">Лабораторная №4</a>
                <a href="#lab5">Лабораторная №5</a>
                <a href="#lab6">Лабораторная №6</a>
                <a href="#lab7">Лабораторная №7</a>
            </div>
        </div>
        <div class="page-content">
            <div id="lab1" class="lab-page">
                <h2>Лабораторная работа №1</h2>
                <hr />
                <div>
                    <img src="CommonUml.png" />
                </div>
                <h4>1. Идентификатор прецедента</h4>
                <div>Рекламный сайт</div>
                <h4>2. Название прецедента</h4>
                <div>Рекламный сайт услуг организаторов дегустаций</div>
                <h4>3. Контекст</h4>
                <div>Разработка сайта</div>
                <h4>4. Участники (actors) и цели (goals)</h4>
                <table>
                    <thead>
                        <tr>
                            <th align="left">Участник</th>
                            <th align="left">Категория</th>
                            <th align="left">Цель (goal)</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td align="left">Разработчик</td>
                            <td align="left">Основной</td>
                            <td align="left">Разработка кода</td>
                        </tr>
                        <tr>
                            <td align="left">Руководитель</td>
                            <td align="left">Внешний</td>
                            <td align="left">Финансирование и отслеживание работы</td>
                        </tr>
                        <tr>
                            <td align="left">Дизайнер</td>
                            <td align="left">Основной</td>
                            <td align="left">Графически оформить работу</td>
                        </tr>
                        <tr>
                            <td align="left">Тестировщик</td>
                            <td align="left">Основной</td>
                            <td align="left">Сократить количество ошибок</td>
                        </tr>
                        <tr>
                            <td align="left">Управляющий проектом</td>
                            <td align="left">Основной</td>
                            <td align="left">Оформление документов</td>
                        </tr>
                        <tr>
                            <td align="left">Репозиторий</td>
                            <td align="left">Инструмент</td>
                            <td align="left">Предоставить место размещения</td>
                        </tr>
                        <tr>
                            <td align="left">Среда разработки</td>
                            <td align="left">Инструмент</td>
                            <td align="left">Разработать сайт</td>
                        </tr>
                        <tr>
                            <td align="left">Хостинг</td>
                            <td align="left">Инструмент</td>
                            <td align="left">Размещение сайта</td>
                        </tr>
                        <tr>
                            <td align="left">PlantUML</td>
                            <td align="left">Инструмент</td>
                            <td align="left">Предоставить средства генерации диаграмм</td>
                        </tr>
                    </tbody>
                </table>
                <h4>5. Предусловия</h4>
                <ul>
                    <li>Заказчик сформировал свою идею и подготовил требования.</li>
                    <li>Выбрана технология разработки</li>
                </ul>
                <h4>6. Постусловия</h4>
                <ul>
                    <li>Сайт разработан в срок, указанный в договоре.</li>
                    <li>Ресурсы не превышены</li>
                    <li>Заказчик доволен качеством работ</li>
                </ul>
                <h4>7. Основной поток</h4>
                <table>
                    <thead>
                        <tr>
                            <th align="left">Участник</th>
                            <th align="left">Действие</th>
                            <th align="left">Ожидаемый результат</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td align="left">Разработчик</td>
                            <td align="left">Формирует личную веб-страницу</td>
                            <td align="left">Личная веб-страница на хостинге</td>
                        </tr>
                        <tr>
                            <td align="left">Разработчик</td>
                            <td align="left">Описывает выбранный прецедент</td>
                            <td align="left">Описание прецедента на хостинге</td>
                        </tr>
                        <tr>
                            <td align="left">Разработчик</td>
                            <td align="left">Формирует диаграмму User Case</td>
                            <td align="left">Диаграмма прецедента на хостинге</td>
                        </tr>
                        <tr>
                            <td align="left">Заказчик</td>
                            <td align="left">Формирует требования</td>
                            <td align="left">Следит за выполнением</td>
                        </tr>
                    </tbody>
                </table>
                <h4>8. Исключения</h4>
                <ul>
                    <li>Не выполнение требований заказчика</li>
                    <li>Превышение ресурсов</li>
                    <li>Превышение сроков</li>
                </ul>
                <h4>9. Альтернатива</h4>
                <ul>
                    <li>Изменение требований заказчика</li>
                </ul>
            </div>
            <br />
            <hr />
            <div id="lab2" class="lab-page">
                <h2>Лабораторная работа №2</h2>
                <hr />
                <br />
                <h4>Роли в команде</h4>
                <h5>СП Системное программирование - Реализатор (Доводчик, Аналитик, Completer-Finisher) - System analyst</h5>
                <div>
                    Реализаторам присущи практический здравый смысл и хорошее чувство самоконтроля и дисциплины. Они любят тяжелую работу и преодоление проблем в системном режиме.
                    <br />
                    <br />
                    В web-разработке люди, связанные с базами данных и серверами, пишут то, что не видит клиент. Их цель в проекте -написать основу страницы (разметку и структуру страницы). При использовании внешнего сервера или cms - их настройка и вывод информации на экран.
                </div>
                <h4>Проект</h4>
                <ul>
                    <li>Рекламный сайт услуг организаторов дегустаций</li>
                </ul>
                <h4>Задача проекта</h4>
                <ul>
                    <li>Программная реализация функций</li>
                </ul>
                <h4>Стратегия управления рисками</h4>
                <ul>
                    <li>Снижение</li>
                    <li>Принятие</li>
                </ul>
                <h4>Мероприятия управления рисками</h4>
                <ul>
                    <li>Повышение квалификации специалистов путем изучения учебного материала</li>
                </ul>
                <h4>Статусы задач в канбан-доске</h4>
                <ul>
                    <li>Бэклог</li>
                    <li>Разработка</li>
                    <li>Внедрение</li>
                    <li>Завершено</li>
                </ul>
            </div>
            <br />
            <hr />
            <div id="lab3" class="lab-page">
                <h2>Лабораторная работа №3</h2>
                <hr />
                <br />
                <h4>Задача</h4>
                <ul>
                    <li>Своя задача по проекту рекламного сайта дегустаций</li>
                </ul>
                <div>Реализовать механизм покупки бронирования на дегустации</div>
            </div>
            <br />
            <hr />
            <div id="lab4" class="lab-page">
                <h2>Лабораторная работа №4</h2>
                <hr />
                <br />
                <img src="XyHZmUY3Q6U.jpg"/>
            </div>
            <br />
            <hr />
            <div id="lab5" class="lab-page">
                <h2>Лабораторная работа №5</h2>
                <hr />
                <br />
                <h4>Распределение ролей в команде</h4>
                <ul>
                    <li><b>Владимир Головцов</b> - ВН, КО</li>
                    <li><b>Майорко Денис</b> - БА, ПП</li>
                    <li><b>Михаил Поляков</b> - РП, СП, НИ, АД</li>
                </ul>
            </div>
            <div id="lab6" class="lab-page">
                <h2>Лабораторная работа №6</h2>
                <hr />
                <br />
                <h4>Создать тест для тестирования конечного программного продукта</h4>
                <a href="ProductControllerTest.cs">Код</a>
            </div>
            <div id="lab7" class="lab-page">
                <h2>Лабораторная работа №7</h2>
                <hr />
                <br />
                <h4>Программный модуль</h4>
                <a href="https://savoryfest.com/events/2">Проект и пример реализации</a>
                <br />
                <br />
                <h4>Скриншот работы</h4>
                <img src="Program.png" />
                <br />
                <br />
                <h4>Код задачи</h4>
                <a href="ProductController.cs">Полный код создаваемого модуля</a>
                <br />
                <br />
                <h4>Результат проведения тестирования</h4>
                <div style="display:flex;justify-content:center;">
                    <img src="Testing.png" style="width:50%" />
                </div>
            </div>
        </div>
    </div>
</body>
</html>
