# eserisson.github.io
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudFlare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css"
        integrity="sha512-1PKOgIY59xJ8Co8+NE6FZ+LOAZKjy+KY8iq0G4B3CyeY6wYHN3yt9PW0XpSriVlkMXe40PTKnXrLnZ9+fkDaog=="
        crossorigin="anonymous" />
    <link href="./style.css" rel="stylesheet">
    <title>Meu Portifólio</title>
</head>

<body>
    <nav id="navbar" class="navbar"><a href="#"></a></nav>
    <div class="container">
        <!--=============== menu ===============-->
        <div class="menu">
            <a href="#welcome-section" class="menu-icon fas fa-home"></a>
            <a href="#about" class="menu-icon fas fa-user"></a>
            <a href="#projects" class="menu-icon fas fa-code"></a>
            <a href="#experience" class="menu-icon fas fa-briefcase"></a>
            <a href="#contact" class="menu-icon fas fa-envelope"></a>
        </div>
        <div class="portfolio">
            <!--=============== topo ===============-->
            <section class="header">
                <img class="header-img" src="/img/eu.jpeg" alt="" />
                <h1>Erisson Silva</h1>
                <h2>FRONT-END Developer</h2>
                <div class="socials">
                    <a href="https://www.linkedin.com/in/erisson-silva-26606526b/" target="_blank" class="fab fa-linkedin-in" id="profile-link"></a>
                    <a href="https://www.instagram.com/es_erisson/" target="_blank" class="fab fa-instagram"></a>
                    <a href="https://web.telegram.org/k/" target="_blank" class="fab fa-telegram"></a>
                </div>
                <a href="" class="cta">Baixar CV</a>
                <footer class="rodape">Todos os direitos reservados. &copy;copyright 2023</footer>
            </section>
            <div class="content">
                <!--=============== texto inicio ===============-->
                <section class="content-card home" id="welcome-section">
                    <h1>Olá, Sou Erisson Silva</h1>
                </section>
                <section class="content-card about" id="about">
                    <h1>Sobre mim</h1>
                    <div class="about-item about-me">
                        <p>
                           EM
                        </p>
                        <p>
                            BREVE!...
                        </p>
                    </div>
                    <div class="col-2">
                        <div class="about-item skills">
                            <h1>Habilidades</h1>
                            <span class="skill">HTML</span>
                            <span class="skill">CSS</span>
                            <span class="skill">JavaScript</span>
                            <span class="skill">React</span>
                        </div>
                        <section class="content-card contact" id="contact">
                            <h1>Contato</h1>
                            <form class="form" id="form" action="#">
                                <div class="input-box">
                                    <input type="text" class="text-input" name="name" placeholder="Name" />
                                </div>
                                <div class="input-box">
                                    <input type="email" class="text-input" name="email" id="email"
                                        placeholder="Email" />
                                </div>
                                <div class="input-box">
                                    <input type="subject" class="text-input" name="subject" id="subject"
                                        placeholder="Subject" />
                                </div>
                                <div class="input-box">
                                    <textarea name="text" class="message" placeholder="Message..."></textarea>
                                </div>
                                <div class="input-box">
                                    <input type="submit" class="submit-btn" id="submit" value="submit" />
                                </div>
                            </form>
                        </section>
                        
                        <script src="script.js"></script>
</body>
    
</html>
