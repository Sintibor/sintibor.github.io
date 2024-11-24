# sintibor.github.io
Сайт
<html>
    <head>
        <title>BitMarket</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <img src="/uploads/2021/02/logo_0_1613588860.svg">
            <a class="button" href="">Скидки</a>
        </header>
        <nav>
            <a class="nav-link" href="">Каталог</a>
            <a class="nav-link" href="">Оптом</a>
            <a class="nav-link" href="">Доставка</a>
            <a class="nav-link" href="">Возврат товара</a>
        </nav>
        <main>
            <h1>Профессионалы советуют</h1>
            <section class="info">
                <article>
                    <h2>Лэптоп для отдыха</h2>
                    <img src="/uploads/2021/02/notebook-405755_1920_0_1613586011.jpg" width="400px" height="300px"/>
                    <p>Samsung V145-S</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
                <article>
                    <h2>Как выбрать наушники</h2>
                    <img src="/uploads/2021/02/music-1813100_1280_0_1613586010.png" width="330px" height="300px"/>
                    <p>Поговорим о новинках</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
                <article>
                    <h2>Телефон мечты</h2>
                    <img src="/uploads/2021/02/mobile-phone-1875813_1920_0_1613586011.jpg" width="400px" height="300px"/>
                    <p>Apple iphone 13</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
                <article>
                    <h2>Техника для всего</h2>
                    <img src="/uploads/2021/02/laptop-1483974_1920_0_1613586010.jpg" width="400px" height="300px"/>
                    <p>И целого мира мало...</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
            </section>
            <img src="/uploads/2021/02/mobile-phone-1419275_1920_0_1613586010.jpg" width="960" height="270"/>
        </main>
        <footer>
            <a href=""><img src="/uploads/2021/02/Group%201_0_1613586391.png" width="80px" height="80px"></a>
            <p><b>Напиши — получи<br/> промокод!</b></p> 
        </footer>
    </body>
</html>

body {
    font-family: sans-serif;
    background-color: rgb(0, 0, 0);
}

header {
    justify-content: space-between;
    padding: 35px 20px 35px 20px;
    margin-bottom: 20px;
    display: flex;
}

.button {
    background-color: #FFAE40;
    color: #000000;
    text-decoration: none;
    padding: 15px;
    font-size: 24px;
    border-radius: 10px;
}

nav {
    border-top: 5px solid white;
    border-bottom: 5px solid white;
    padding: 25px 100px 25px 95px;
    justify-content: space-between;
    display: flex;
}

.nav-link {
    font-size: 24px;
    color: #FFEF40;
    text-decoration: none;
}

h1 {
    text-align: center;
    color: black;
    font-size: 36px;
    margin-top: 50px;
    margin-bottom: 0px;
}

p {
    font-size: 24px;
}

.info {
    flex-wrap: wrap;
    width: 1100px;
    margin: 0px;
    display: flex;
}

article {
    background-color: white;
    padding: 20px 45px 20px 45px;
    width: 400px;
    margin: 40px 20px 40px 20px;
    justify-content: space-around
}

.article-but {
    text-decoration: none;
    background-color: #FFAE40;
    color: black;
    font-size: 24px;
    text-align: center;
    padding: 10px 75px 10px 75px;
}

footer {
    background-color: #514ED9;
    padding: 60px 0px 60px 278px;
    display: flex
}

footer a {
    margin-right: 42px;
}

footer p {
    font-size: 24px;
}
