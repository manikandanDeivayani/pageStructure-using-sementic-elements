# pageStructure-using-sementic-elements

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    #header{
        background-color: lightblue;
        padding: 24px;
    }
    #navbar{
        background-color: lightcoral;
        padding: 8px;
    }
    #main-section{
        background-color: lightgray;
        padding: 24px;
    }
    #section{
        background-color: lightgreen;
        padding: 16px;
    }

    .article{
        background-color: lightseagreen;
        padding: 16px;
        margin-top: 16px;
        margin-bottom: 16px;
    }
    #footer{
        background-color: lightskyblue;
        padding: 24px;
    }
</style>
</head>
<body style="margin: 0%;">
    <header id="header">
        <nav id="navbar">
            <span>menu 1</span>
            <span>menu 2</span>
            <span>menu 3</span>
        </nav>
    </header>

    <main id="main-section">
        <section id="section">
            <article class="article">
                <header>
                    <h3>Article Title one</h3>
                    <a href="/">Author one</a>
                </header>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repudiandae, id nisi! Quibusdam soluta tempore provident libero quam quae aut nulla nobis. Nemo, suscipit molestiae facere fuga voluptas nihil assumenda cumque.</p>
            </article>
            <article class="article">
                <header>
                    <h3>Article Title two</h3>
                    <a href="/">Author two</a>
                </header>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repudiandae, id nisi! Quibusdam soluta tempore provident libero quam quae aut nulla nobis. Nemo, suscipit molestiae facere fuga voluptas nihil assumenda cumque.</p>
            </article>
        </section>
    </main>
    <footer id="footer">
        <p>copyright 2023</p>
    </footer>
    
</body>
</html>
