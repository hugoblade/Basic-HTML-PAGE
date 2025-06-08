AI Program
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
       <title>Welcome To AI pact </title>
<style>
        body{
                font-family: Arial, sans-serif;
                background:#f0f2f5;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;

        }

        .login-container{
                background: white;
                padding: 2rem;
                border-radius: 10px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
                width: 300px;
        }

        .login-container h2 {
               margin-bottom: 1rem;
               text-align: center;
        }

        .login-container
input, .login-container
select .login-container button {
        width: 100%;
        padding: 0,75rem;
        margin-bottom: 1rem;
        border-radius: 5px;
        border: 1px solid #ccc;

}

        .login-container button {
                background: #45CAF5;
                color: white;
                border: none;
                cursor: pointer;
        }

        .login-container button:hover {
                background: #45a049;
        }
</style>
</head>
<body>

         <div class="login-container">
                <h2>Enter your details</h2>
                <select id="Language-select">
                        <option value="en">English( United Kingdom )</option>
                        <option value="en">English( Australia )</option>
                        <option value="en">English( Canada )</option>
                        <option value="en">English( Caribbean )</option>
                        <option value="en">English( New Zealand )</option>
                        <option value="fr">Francais</option>
                        <option value="es">Espanol</option>
                        <option value="de">Deutsch</option>
                        <option value="afn">Afrikaan</option>
                        <option value="alino"> Alsatiano</option>
                        <option value="arm">Armenian</option>
                        <option value="bos">Bosnian</option>
                        <option value="ben">Bengali</option>
                        <option value="bang">Bangladesh</option>
                        <option value="en">Chinese</option>
                        <option value="en">Danish</option>
                        <option value="isl">Iselenska</option>
                        <option value="isx">Isixhosa</option>
                        <option value="isz">IsiZulu</option>
                        <option value="jap">Japanese</option>
                        <option value="ita">Italian</option>
                        <option value="gr">Greek</option>
                        <option value="kor">Korean</option>
                </select>


    <input type="email" placeholder="Email" id="email">
    <input type="password" placeholder="Password" id="password">
    <button onclick="handleLogin()"> Login</button>
    </div>

    <script>
        function handleLogin() {
                const email = document.getElementById('email').value;
        

        const language = document.getElementById('language-select').value;
        alert('Logging in as ${email} using language: ${language}');
         // Here you can redirect or send data to your backend
         }
    </script>

 </body>
</html>
