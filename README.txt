<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulado</title>
    <link rel="stylesheet" href="index.css">
</head>

<body>
    <header>
        <h1 id="cabeçalho">Website name</h1>
    </header>

    <div>
        <img id="imagem"
            src="https://static.vecteezy.com/ti/vetor-gratis/p1/9169455-ceu-dourado-por-do-sol-na-costa-natureza-paisagem-vetor.jpg"
            alt="Montanha">
    </div>

    <div>
        <button id="botao">Call to action</button>
    </div>

    <div class="content">
        <p id="texto">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Autem aliquam ut quos dolorum nobis
            doloremque repudiandae unde assumenda a omnis qui rerum tenetur, error accusamus consectetur quod,
            perspiciatis mollitia recusandae!Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto sunt
            repellendus alias nihil expedita nulla exercitationem voluptatum animi fuga doloremque, repellat enim
            obcaecati incidunt nesciunt beatae voluptas perferendis libero in!Lorem ipsum dolor, sit amet consectetur
            adipisicing elit. Voluptatibus adipisci possimus minus reprehenderit ut eligendi illo harum magnam porro?
            Distinctio quaerat eius cumque. Architecto doloribus magnam in doloremque odio saepe!</p>

        <source><iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/uu_B4ywAhOM"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe></iframe>
    </div>

    <footer class="rodape">
        <h2>About Us</h2>
        <h2>Contact</h2>
        <h2>Authorized Dealers</h2>
    </footer>
</body>

</html>

#cabeçalho {
    height: 40px;
    width: 90%;
    margin: auto;
    margin-top: 10px;
    margin-bottom: 30px;
    text-align: center;
    color: white;
    background-color: black;
    border-radius: 10px;
}

img {
    margin: auto;
    margin-bottom: 20px;
    display: flex;
    height: 70%;
    width: 70%;
}

button {
    margin: auto;
    margin-bottom: 20px;
    display: flex;
    background-color: black;
    color: white;
    padding: 10px 40px;
    border: solid 1px green;
    border-radius: 10px;
}

.content {
    margin: auto;
    display: flex;
}

#texto {
    height: 100%;
    width: 300px;
    display: block;
    margin: 0 auto;
    margin-right: 0px;
}

#video {
    display: block;
    margin: 0 auto;
    margin-left: 0px;
}

.rodape {
    height: 40px;
    width: 90%;
    margin: auto;
    display: flex;
    border-radius: 10px;
    background-color: black;
    color: white;
    justify-content: center;
}
