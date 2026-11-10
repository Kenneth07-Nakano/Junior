<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>website</title>
<body>
    <style>
        .container {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 15px;
    flex-wrap: nowrap;
    width: 100%;
    padding: 20px;
}

.product-card {
    width: 200px;
    flex: 0 0 200px;
    padding: 15px;
    background-color: #fff9df;
    border: 1px solid #e0d5b5;
    border-radius: 8px;
    box-sizing: border-box;
}

.product-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    display: block;
}

.product-desc {
    margin-top: 10px;
}

.product-card h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

.product-card p {
    margin-bottom: 15px;
}

.product-card button {
    width: 100%;
    padding: 10px;
    background-color: #1764bd;
    color: white;
    border: none;
    cursor: pointer;
}
    </style>
</head>
</body>
<div class="container">
    <div class="product-card">
        <img src="image/Ian1.jpg" alt="rent a grilfriend">
        <div class="product-desc">
            <h3>Name; Ian</h3>
            <p>Price; $1000</p>
         </div>
         <button>Payment</button>
    </div>
    <div class="product-card">
        <img src="image/p (3).jpg" alt="rent a grilfriend">
        <div class="product-desc">
            <h3>Name; Winter</h3>
            <p>Price; $100</p>
         </div>
         <button>Payment</button>
    </div>
    <div class="product-card">
        <img src="image/p (13).jpg" alt="rent a grilfriend">
        <div class="product-desc">
            <h3>Name; Wonyoung</h3>
            <p>Price; $1000</p>
         </div>
         <button>Payment</button>
    </div>
    <div class="product-card">
        <img src="image/p (31).jpg" alt="rent a grilfriend">
        <div class="product-desc">
            <h3>Name; Karina</h3>
            <p>Price; $1000</p>
         </div>
         <button>Payment</button>
    </div>
    <div class="product-card">
        <img src="image/p (16).jpg" alt="rent a grilfriend">
        <div class="product-desc">
            <h3>Name; Yeji</h3>
            <p>Price; $1000</p>
         </div>
         <button>Payment</button>
    </div><div class="product-card">
        <img src="image/a (3).jpg" alt="rent a grilfriend">
        <div class="product-desc">
            <h3>Name; Karina</h3>
            <p>Price; $1000</p>
         </div>
         <button>Payment</button>
    </div>
</div>
</html>
