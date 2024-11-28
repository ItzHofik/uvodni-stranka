<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moje úvodní stránka</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #a4f6d2;
        }
        h1 {
            color: #c0f9d8;
        }
        a {
            text-decoration: none;
            color: #007BFF;
            margin: 10px 0;
        }
        a:hover {
            text-decoration: underline;
        }
        form {
            margin-top: 20px;
        }
        input {
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 10px 15px;
            font-size: 16px;
            color: white;
            background-color: #123823;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
        <h1>Vítejte na mé úvodní stránce!</h1>
	<form action="https://www.duckduckgo.com" method="get">
        <input type="text" name="q" placeholder="Type">
        <button type="submit">Find</button>
    </form>
</body>
</html>
