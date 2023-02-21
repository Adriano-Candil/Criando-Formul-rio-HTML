# Criando-Formul-rio-HTML
Criando formulário em HTML CRU

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <script>function confereSenha() {
        const senha = document.querySelector("input[name=senha]");
        const confirma = document.querySelector("input[name=confirma]");
        
        if (confirma.value === senha.value) {
            confirma.setCustomValidity('');
        } else {
            confirma.setCustomValidity("As senhas não conferem");
        }
    }

    function senhaOK()  {
        alert("Cadastro Confirmado!")

    }
        </script>
    <meta charset="utf-8">
          <title>Criando Formulários EVFB</title>
    </head>
<body background="outerspace-6.gif">
<h1 style="color:#FFF">Formulario para Cadastro</h1>
    <form action="mailto:adriano.candil@hotmail.com" method="get" name="cadastro" action="" onsubmit="senhaOK();" accept-charset>
    <p style="color:#fff">Nome: <input type="text" name="Nome" required placeholder="Digite seu Nome Completo"></p>
<p style="color:#FFF">E-mail: <input type="text" name="email" maxlength="30" required placeholder="email@exemplo.com"></p>
<p style="color:#FFF">Sexo: <input type="radio" name="sexo" CHECKED>Feminino
<input type="radio" name="sexo" CHECKED>Masculino
        <input type="radio" name="sexo" CHECKED required>Prefiro Não Informar</p>
<p style="color:white">RG: <input type="text" name="RG" maxlength="9" required placeholder="Apenas numeros"></p>
<p style="color:#FFF">CPF: <input type="text" name="CPF" maxlength="11" required placeholder="Apenas numeros" CHECKED></p>
<p style="color:#FFF">Login: <input type="text" name="Login" maxlength="15" required placeholder="Login" required placeholder="Login"></p>
<p style="color:#FFF">Senha: <input type="password" name="senha" maxlength="10" required placeholder="**********" onchange="confereSenha();"></p>
        <p style="color:#FFF">Repita sua Senha: <input type="password" name="senha" maxlength="10" required placeholder="**********" onchange="confereSenha();"></p>
<input type="submit" value="Enviar"> <input type="reset" value="Limpar">
            
            
            
            
    </form>








    </body>
</html>
