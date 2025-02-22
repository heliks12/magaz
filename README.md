<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин товаров</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            font-size: 24px;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            background: white;
            width: 30%;
            padding: 15px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            text-align: center;
            border-radius: 10px;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product button {
            background: #ff5722;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background: #e64a19;
        }
    </style>
</head>
<body>
    <header>Интернет-магазин</header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Товар 1">
            <h3>Товар 1</h3>
            <p>Описание товара 1</p>
            <button>Купить</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Товар 2">
            <h3>Товар 2</h3>
            <p>Описание товара 2</p>
            <button>Купить</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Товар 3">
            <h3>Товар 3</h3>
            <p>Описание товара 3</p>
            <button>Купить</button>
        </div>
    </div>
</body>
</html>


