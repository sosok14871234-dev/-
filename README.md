[index.html](https://github.com/user-attachments/files/24260353/index.html)
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сайт-визитка Хасанов Богдан П-11</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <header>

            <h2 id="student">Студент 1 курса группы П-11 <br>
            Хасанов Богдан</h2>

            <div class="hat">
                <a id="hat1" href="#myworks">Мои работы</a>
                <a id="hat2" href="#contacts">Контакты</a>
                <a id="hat3" href="#socseti">Соц. Сети</a>
            </div>
        </header>

        <main>
            <div class="content">
                <div class="aboutme">
                    <p id="aboutme">О себе</p>
                    <p id="aboutme1">Я — разработчик мультимедиа, специализирующийся на создании  захватывающего, высокопроизводительного и интерактивного контента для  веба. Используя WebGL, Canvas и современные фреймворки, я преобразую  статические страницы в динамичные 3D-визуализации и плавные анимационные решения. Моя ключевая задача — обеспечить безупречный цифровой опыт,  который вовлекает пользователей и работает быстро на любом устройстве.</p>
                </div>

                <p id="myworks">Мои работы в Figma</p>

                <div class="figma">
                    <img src="img/Rectangle1.png" alt="Работа Figma 1">
                    <img src="img/Rectangle2.png" alt="Работа Figma 2">
                    <img src="img/Rectangle3.png" alt="Работа Figma 3">
                </div>

                <div class="ssilka">
                    <a href="https://www.figma.com/design/EJUDcs3rmInONWpD0gR6cl/%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-3-%D0%A5%D0%B0%D1%81%D0%B0%D0%BD%D0%BE%D0%B2-%D0%91%D0%BE%D0%B3%D0%B4%D0%B0%D0%BD-%D0%BF-11?node-id=0-1&t=2bIP0QoYHZ1xEOOe-1">Ссылка на эту работу</a>
                    <a href="https://www.figma.com/design/wZYmdfGpycOZpItsAyEBsw/Mobile-App-Screen?node-id=0-1&t=LEhe9cztkHjsgSzE-1">Ссылка на эту работу</a>
                    <a href="https://www.figma.com/design/xxOaKxRHH2nw8JomRSmbJD/Untitled?node-id=0-1&t=1oz96hX6lv0JpYpv-1">Ссылка на эту работу</a>
                </div>

                <p id="html">Мои работы в HTML и CSS</p>

                <div class="html">
                    <img src="img/Rectangle5.png" alt="Работа HTML и CSS">
                    <img src="img/Rectangle6.png" alt="Работа HTML и CSS">
                    <img src="img/Rectangle7.png" alt="Работа HTML и CSS">
                </div>

                <div class="ssilka2">
                    <a href="github.com/TheLeaflet22/pchelki">Ссылка на эту работу</a>
                    <a href="#">Ссылка на эту работу</a>
                    <a href="https://github.com/TheLeaflet22/mysite">Ссылка на эту работу</a>
                </div>
            </div>

            <p id="contacts">Контакты</p>

            <div class="main-contacts">
                <div class="contact-info">
                    <div class="info-block">
                        <span class="label">Номер телефона:</span>
                        <p class="value"> +7 (xxx) xxx-xx-xx</p>
                    </div>

                    <div class="info-block">
                        <span class="label">Электронная почта:</span>
                        <a href="mailto:nov.leaflet@gmail.com" class="value">nov.leaflet@gmail.com</a>
                    </div>
                </div>

                <div class="contact-form">
                    <div class="form-title">Ваша заявка:</div>
                    <form action="#" method="POST">
                        <input type="text" placeholder="Ваше имя" required>
                        <input type="tel" placeholder="Ваш телефон" required>
                        <input type="email" placeholder="Ваша почта" required>
                        <button type="submit">Отправить</button>
                    </form>
                </div>
            </div>
        </main>

        
    </div>

    <footer>
        <p id="copy">&copy; 2025 все права защещены</p>
        <div class="socseti">
            <img id="socseti" src="img/тг.png" alt="Картинка тг">
            <img id="vk" src="img/вк.png" alt="Картинка вк">
        </div>

    </footer>
     </html>
</body>[style.css](https://github.com/user-attachments/files/24260365/style.css)
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

header {
    background-color: rgb(0, 0, 61);
    border-bottom: 3px solid white;
    height: 132px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
}

#student {
   margin-top: 30px;
   margin-bottom: 30px;
   margin-left: 107px;
   margin-right: 107px; 
   font-size: 30px;
   color: white;
   text-align: center;
}

a {
    color: white;
}

a:hover {
    color: orangered;
    text-decoration: none;
}

.hat {
    text-align: center;
    font-size: 18px;
    padding-top: 55px;
    padding-bottom: 55px;
}

#hat1 {
    padding-right: 80px;
}

#hat2 {
    padding-right: 80px;
}

#hat3 {
    padding-right: 80px;
}

main {
    background-color: rgb(0, 0, 61);
    padding-left: 100px;
    padding-right: 100px;
}

#aboutme {
    font-size: 30px;
    color: orangered;
    padding-top: 120px;
}

#aboutme1 {
    color: white;
    padding-top: 60px;
    font-size: 30px;
}

.figma {
    display: flex;
    justify-content: space-around;
    padding-top: 60px;
}

#myworks {
    color: orangered;
    padding-top: 120px;
    text-align: center;
    font-size: 30px;
}

.ssilka {
    display: flex;
    justify-content: space-around;
    padding-top: 30px;
    font-size: 20px;
}

#html {
    color: orangered;
    padding-top: 120px;
    text-align: center;
    font-size: 30px;
}

.html {
    display: flex;
    justify-content: space-around;
    padding-top: 60px;
}

.ssilka2 {
    display: flex;
    justify-content: space-around;
    padding-top: 30px;
    font-size: 20px;
}

#contacts {
    font-size: 30px;
    color: orangered;
    text-align: center;
    padding-top: 120px;
    padding-bottom: 64px;
}

.main-contacts {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 50px;
    padding-bottom: 120px;
}

.contact-info {
    flex: 1;
    padding-left: 20px;
}

.info-block {
    margin-bottom: 40px;
}

.label {
    color: orangered;
    font-size: 30px;
    margin-bottom: 15px;
    display: block;
}

.value {
    color: white;
    font-size: 30px;
    text-decoration: none;
}

.contact-form {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-end; 
}

.form-title {
    color: orangered;
    font-size: 30px;
    margin-bottom: 20px;
    width: 300px; 
    text-align: left;
}

form {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 300px;
}
</html>
input {
    width: 100%;
    padding: 12px;
    background-color: white;
    border: none;
    box-sizing: border-box;
    font-size: 15px;
    color: black;
}
        
input::placeholder {
    color: black;
}

button {
    width: 100%;
    padding: 12px;
    background-color: #ff3333;
    color: black;
    border: none;
    font-size: 17px;
}

footer {
    background-color: rgb(0, 0, 61);
    border-top: 3px solid white;
    height: 132px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
}

#copy {
    font-size: 20px;
    color: white;
    padding-left: 100px;
}

#vk {
    padding-right: 120px;
    padding-left: 29px;
}

