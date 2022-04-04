<!-- <!DOCTYPE html> -->
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="manifest" href="/site.webmanifest" />
    <title>Akhmat CV1-by-HTML-CSS</title>
    <link href="styles.css" rel="stylesheet" />
  </head>
  <body>
    <div class="container">
      <div class="info">
        <img src="img131.jpg" alt="Тут моя фотка" class="avatar" />

        <div class="info-text">
          <h1>Ахмат Биджиев</h1>
          <p>Я - основатель одноименного <strong> YouTube канала</strong></p>
          <p>
            Я люблю путешествовать, заниматься спортом, читать, сочинять стихи, строить, увлекаюсь IT-технологиями и интересуюсь древней и средневековой историей
          </p>

          <h4>Мои социальные сети</h4>

          <a target="_blank" href="https://t.me/js_by_akhmat">Telegram</a>
          |
          <a href="https://instagram.com/akhmat.bidzhiev" target="_blank"
            >Instagram</a
          >
          <!-- | -->
          <!-- <a target="_blank" href="https://github.com/AkhmatBidzhiev59/Hello">GitHub</a> -->
        </div>
      </div>

      <div class="card bg-yellow">
        <h2>Мои хобби</h2>
        <ol class="list">
          <li>блоггер</li>
          <li>ездa на машинах</li>
          <li>спорт: футбол, плавание</li>
          <li>путешествия</li>
          <li>восхождения на вершины гор</li>
        </ol>
      </div>

      <div class="card bg-green">
        <h2>Опыт работы</h2>
        <table class="table">
          <tr>
            <td>Autocolumn</td>
            <td>Locksmith, Shauffeur</td>
            <td>1976-1981</td>
          </tr>
          <tr>
            <td>Mobile Mechanizable Column</td>
            <td>Engineer</td>
            <td>1981-1983</td>
          </tr>
          <tr>
            <td>Autotravelling Sector</td>
            <td>Foreman</td>
            <td>1983-1984</td>
          </tr>
          <tr>
            <td>Electron Factory</td>
            <td>Locksmith, Foreman, Engineer </td>
            <td>1983-1998</td>
          </tr>
          <tr>
            <td>Private business</td>
            <td>Locksmith, Shauffeur, Tractorist, Shopman</td>
            <td>1998-2022</td>
          </tr>
          <tr>
            <td>YouTube</td>
            <td>Blogger</td>
            <td>2022 - as soon as</td>
          </tr>
        </table>
      </div>

      <div class="card bg-red">
        <h2>YouTube Курсы</h2>
        <ul class="link-list">
          <li>
            <!-- This is not my! My YouTube courses are not published yet! -->
<!--             <a href="https://www.akhmatyoutube.com/watch?v=bluxbh9CaQ0" 
              >JavaScript Основы для начинающих - Полный Курс за 6 часов
              [2022]</a>  -->
          </li>
          <li>
            <!-- This is not my! My YouTube courses are not published yet! -->
<!--             <a href="https://www.akhmatyoutube.com/watch?ven9uCgUzfeRQ" 
              >Docker для начинающих - Полный Курс за 6 часов [2022]</a> -->
          </li>
        </ul>
      </div>

      <div class="contact">
        <h2>Связаться со мной</h2>

        <form action="/">
          <div class="row">
            <div class="form-group">
              <label for="name">Ваше имя:</label>
              <input type="text" id="name" placeholder="Введите ваше имя..." />
            </div>

            <div class="form-group">
              <label for="email">Ваш email:</label>
              <input type="email" id="email" placeholder="Введите email..." />
            </div>
          </div>

          <div class="form-group">
            <label for="text">Ваше сообщение:</label>

            <textarea id="text" rows="2" cols="15"></textarea>
          </div>

          <input class="btn" type="submit" value="Связаться!" />
        </form>
      </div>

      <div class="position">
        <div class="box"></div>
      </div>
    </div>

    <div style="margin-bottom: 500px"></div>
  </body>
</html>
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

/* * {
  padding: 0;
  margin: 0;
} */

body {
  background-color: #f1f1f1;
  color: #0f141e;

  font-size: 16px;
  font-weight: normal;
  font-family: "Roboto", sans-serif;

  /* font: normal 16px 'Roboto', sans-serif; */

  /* font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; */
}

a {
  color: black;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

a:active {
  color: blue;
}

a:visited {
  color: grey;
}

.avatar {
  width: 200px;
  border-radius: 28px;
  box-shadow: 4px 4px 14px rgba(0, 0, 0, 0.25);
}

.info {
  display: flex;
  margin-bottom: 20px;
}

@media (max-width: 700px) {
  .info {
    text-align: center;
    display: block;
  }
}

.info-text {
  margin-left: 40px;
}

.info-text h4 {
  margin-bottom: 10px;
}

.info p {
  color: #86898f;
  margin: 0;
  font-style: italic;
  font-weight: bold;
  text-decoration: none;
  /* text-transform: uppercase; */
  /* letter-spacing: 5px; */
  /* word-spacing: 42px; */
}

/* Box model */
.container {
  max-width: 750px;
  margin: auto;
  padding-top: 30px;
}

/* .social {
  background: green;
  /* padding: 15px; */
/* padding: 15px 40px; */
/* padding: 15px 20px 25px 30px; */
/* padding-top: 15px;
  padding-right: 20px;
  padding-bottom: 25px;
  padding-left: 30px;
  margin: 5px;

  border: 5px solid red;
  border-bottom-style: dotted;
  border-top-width: 15px;
  border-right-color: blue;
/* } */

/* .box-model > div {
  float: left;
  background: #000;
  height: 200px;
  border: 4px solid red;
  width: 25%;
  box-sizing: border-box;
} */

.bg-yellow {
  background: #fff9dc;
}

.bg-green {
  background: #e5ffe7;
}

.bg-red {
  background: #ffe5e5;
}

.card {
  padding: 15px 20px;
  margin-bottom: 20px;
  border-radius: 20px;
}

.card h2 {
  margin-bottom: 10px;
}

.list {
  padding: 0 20px;
}

.list li {
  color: #86898f;
  margin-bottom: 10px;
}

.table {
  width: 100%;
}

.table td {
  padding-bottom: 10px;
}

.table .temp td {
  color: #86898f;
}

.table td:nth-child(2),
.table td:nth-child(3) {
  color: #86898f;
}

/* .table tr:nth-child(odd) {
    background: red;
} */

.link-list {
  list-style: none;
  padding: 0;
}

.link-list li {
  margin-bottom: 10px;
  padding-bottom: 5px;
  border-bottom: 1px solid #ccc;
}

.contact h2 {
  text-align: center;
}

.form-group label {
  display: block;
  font-size: 14px;
  color: #86898f;
}

.form-group input,
.form-group textarea {
  width: 100%;
  box-sizing: border-box;
  border: none;
  background: transparent;
  border-bottom: 1px solid #ccc;
  color: #000;
  padding: 15px 0 10px;
  outline: none;
  font-family: inherit;
}

.row {
  display: flex;
  margin-bottom: 20px;
}

.row > .form-group {
  width: 50%;
  margin-right: 20px;
}

.row > .form-group: :last-child {
  margin-right: 0;
}

.btn {
  background: #111;
  padding: 15px 20px;
  color: #fff;
  border: none;
  font-family: inherit;
  cursor: pointer;
}

.btn:hover {
  opacity: 0.9;
}

/* Position */

/* .position {
  position: relative;
  border: 4px solid black;
  margin-top: 40px;
  padding: 20px;
  height: 300px;
}

.box {
  position: fixed;
  top: 0px;
  left: 0px; 
  width: 100%;
  height: 50px;
  background: lightcoral; 
} */
