<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário Fepi</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Teko&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
</head>
<body>
    <header>
        <div class="container">
            <h1 class="titulo1">Cadastro Pessoal</h1>
            <br>
            <p class="paragrafohead">Preencha as Lacunas abaixo para prosseguir:</p>
            <p style="margin-left: 50px;">Nome: Andralyssa Rodrigues Pereira. RA: 00021666</p>         
            <div class="imagem-head">
                <img src="Images/cadastro.png" alt="cadastro" class="image">
            </div>      
        </div>
    </header>

    <main>
       <div class="box">
        <form action="">
            <fieldset class="fieldsetcss">
                <legend class="legendcss"><b> Dados Pessoais</b></legend>
                
                <div class="inputbox">
                    <h4><color="black">Nome:</color>
                    <input type="text" name="Nome" id="Nome" class="inputUser" placeholder="Informe Seu Nome" required="required"></h4>
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="email">Email:</label></color>
                    <input type="email" name="email" id="email" class="inputUser" placeholder="Exemplo:abc@gmail.com" required >
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="datanasc">Nascimento:</label></color>
                    <input type="date" name="datanasc" id="datanasc" class="inputUser" placeholder="dd/mm/aaaa" required >
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="rg">RG:</label></color>
                    <input type="text" name="rg" id="rg" class="inputUser" placeholder="Exemplo:MG-00.000.000" required>
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="CPF">CPF:</label></color>
                    <input type="text" name="CPF" id="CPF" class="inputUser" placeholder="Exemplo:000.000.000-00" required>
                </div>
                <br>
            </fieldset>

        </form>            
       </div>

       <div class="box">
        <form action="">
            <fieldset class="fieldsetcss">
                <h4><color="black"><legend class="legendcss"><b>Endereço</b></legend></color>
                
                <div class="inputbox">
                    <h4><color="black"><label for="Rua">Rua:</label></color>
                    <input type="text" name="Rua" id="Rua" class="inputUser" required >
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="numero">Número:</label></color>
                    <input type="number" name="numero" id="numero" class="inputUser" required>
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="Bairro">Bairro:</label></color>
                    <input type="datetime" name="Bairro" id="Bairro" class="inputUser" required >
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="Estado">Estado:</label></color>
                    <select name="Estado" class="inputUser">
                        <option value="Escolha">Escolha seu estado:</option> 
                        <option value="Norte">Norte</option> 
                        <option value="Nordeste">Nordeste</option> 
                        <option value="Sul">Sul</option> 
                        <option value="Sudeste">Sudeste</option> 
                        <option value="Centro-Oeste">Centro-Oeste</option> 
                    </select>
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="Cidade">Cidade:</label></color>
                    <input type="text" name="Cidade" id="Cidade" class="inputUser" required>
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="CEP">CEP:</label></color>
                    <input type="text" name="CEP" id="CEP" class="inputUser" placeholder="Exemplo:00000-000" required>
                </div>
                <br>
            </fieldset>

        </form>            
       </div>

       <div class="box">
        <form action="">
            <fieldset class="fieldsetcss">
                <h4><color="black"><legend class="legendcss"><b>Login</b></legend></color>
               
                <div class="inputbox">
                    <h4><color="black"><label for="images">Imagem de perfil:</label></color>
                    <input type="file" name="images" id="images" class="inputUser" required >
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="login">Login de usuário:</label></color>
                    <input type="email" name="login" id="login" class="inputUser" required placeholder="Exemplo:abc@gmail.com">
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="senha">Senha:</label></color>
                    <input type="password" name="senha" id="senha" class="inputUser" required placeholder="Informe sua senha">
                </div>
                <br>
                <div class="inputbox">
                    <h4><color="black"><label for="confirmsenha">Confirmar senha:</label></color>
                    <input type="password" name="confirmsenha" id="confirmsenha" class="inputUser" required placeholder="Confirme sua senha">
                </div>
                <br>
                
            </fieldset>
            <div class="inputsend">
                <input type="submit" name="submit" id="submit">
                <input type="reset" name="Resetar" id="resetar">
                <a href="#" target="_blank" rel="external" class="termosuso">termos de uso</a>
                <a href="https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm" target="_blank" rel="external" class="termos">LGPD para saber mais</a>
                
                <br><br><br><br><br><br>
            </div>
        </form>            
       </div>
    </main>
</body>
</html>
