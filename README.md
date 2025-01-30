<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <h1>renewzone</h1>
    <br>
    <p>hello! welcome to login page. Enter your username and password to login to your account.</p>
    <br>
    <input type="text" placeholder="enter username">
    <div class="password-container">
        <input type="password" id="password" placeholder="enter password">
        <button type="button" id="togglePassword" class="eye-button"><i class="fas fa-eye"></i></button>
    </div>
    <br>
    <a href="https://myaccount.google.com/intro/signinoptions/password">forget password</a>
    <button>submit</button>
    <br>
    <u>create account</u>
    <hr>
    <img src="https://rb.gy/xdt6pk" height="300px" width="300px" alt="password">
    <label for="id1">Phone</label>
    <input type="radio" value="phone" name="device" id="id1">
    <label for="id2">Samsung</label>
    <input type="radio" value="phone2" name="device" id="id2">
    <textarea name="feedback" id="id2" placeholder="please give your valuable feedback"></textarea>
    <br>
    <button>submit feedback</button> <br>
    <select name="city" id="city">
        <option value="delhi">delhi</option>
        <option value="kanpur">kanpur</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
        <option value="ghaziabad">ghaziabad</option>
    </select>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/X8BYu3dMKf0?si=xjf6bw0K10VQe4iM" title="YouTube video player" frameborder="5" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen aria-controls="autoplay"></iframe>
    <p>h<sub>3</sub>o</p>
    <p>c<sup>o</sup>2</p>
    <b>renewzone</b> <br>
    <i>login</i><br>
    <u>biggest company in the world</u>

    <script>
        const togglePassword = document.querySelector('#togglePassword');
        const password = document.querySelector('#password');

        togglePassword.addEventListener('click', function () {
            // Toggle the type attribute
            const type = password.getAttribute('type') === 'password' ? 'text' : 'password';
            password.setAttribute('type', type);

            // Toggle the icon
            this.querySelector('i').classList.toggle('fa-eye');
            this.querySelector('i').classList.toggle('fa-eye-slash');
        });
    </script>
</body>
</html>
