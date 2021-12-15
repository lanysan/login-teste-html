<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login-Helper</title>
    <link rel="stylesheet" href="./css/styles.css">
    <script src="./js/index.js" defer></script>

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/d987aa355c.js" crossorigin="anonymous" defer></script>
</head>

<body>
    <header>
        <h1>Login-Helper</h1>
    </header>

    <main>
        <form>
            <section class="inputs-container">
                <input type="email" placeholder="example@gmail.com">

                <div class="password-container">
                    <input type="password" id="field-password" class="field-password" placeholder="*******">
                    <i class="fas fa-eye" id="eye" onclick="showPassword()"></i>
                    <i class="fas fa-eye-slash" id="eye-slash" onclick="showPassword()"></i>
                </div>
            </section>

            <section class="password-infos">
                <div>
                    <input type="checkbox">
                    <span>Lembrar senha?</span>
                </div>

                <a href="#">Esqueceu sua senha?</a>
            </section>

            <button id="btn-login">Login</button>

            <section class="links-container">
                <span>Ou entre com:</span>

                <aside>
                    <a href="#"><i class="fab fa-google-plus-square google"></i></a>
                    <a href="#"><i class="fab fa-linkedin linkedin"></i></a>
                    <a href="#"><i class="fab fa-facebook-square facebook"></i></a>
                </aside>
            </section>

            <footer>
                <hr>
                <span>Ainda não tem uma conta? <a href="#">Cadastra-se</a></span>
            </footer>
        </form>
    </main>

</body>

</html>
