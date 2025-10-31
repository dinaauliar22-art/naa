<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halaman Login Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form action="/login" method="POST">
            <div class="input-group">
                <label for="username">Nama Pengguna:</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="input-group">
                <label for="password">Kata Sandi:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="submit">Masuk</button>
        </form>
    </div>
</body>
</html>
