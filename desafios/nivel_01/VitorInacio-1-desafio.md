## exercício 1

* HTML

~~~ php
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ex1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <a href="https://google.com" title="logo">
            <img src="https://logodownload.org/wp-content/uploads/2014/09/google-logo-1.png" alt="logo" max>
        </a>
        <nav>
            <ul>
                <li>
                    <a href="https://globo.com">Globo</a>
                </li>
                <li>
                    <a href="https://magazineluiza.com">magazine Luiza</a>
                </li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="https://image.api.playstation.com/vulcan/ap/rnd/202011/0921/B7jV8ThPs8eqDz8NRRllf7g6.jpg" alt="imagem">
        <p>Imagem do jogo</p>
        <a href="https://store.steampowered.com/app/1259420/Days_Gone/">Link steam</a>
        <section>
            <h1>section</h1>
            <p>texto section</p>
        </section>
    </main>
</body>
</html>

~~~

* CSS

~~~ php

header li {
    display: inline-block;
}
header img {
    width: 100px;
}
main img {
    width: 200px;
}

~~~