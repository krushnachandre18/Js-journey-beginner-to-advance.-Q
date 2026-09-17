<!DOCTYPE html>
<html>
<head>
    <title>Shopping Cart</title>
</head>
<body>

    <h2>Shopping Cart</h2>

    <button onclick="addItem()">Add Item</button>
    <button onclick="removeItem()">Remove Last Item</button>

    <h3>Cart Items:</h3>
    <ul id="cart"></ul>

    <script>
        let cart = [];

        function addItem() {
            let item = prompt("Enter item name:");

            if (item !== null && item !== "") {
                cart.push(item);
                displayCart();
            }
        }

        function removeItem() {
            if (cart.length > 0) {
                cart.pop();
                displayCart();
            } else {
                alert("Cart is empty!");
            }
        }

        function displayCart() {
            let list = document.getElementById("cart");

            list.innerHTML = "";

            for (let i = 0; i < cart.length; i++) {
                let li = document.createElement("li");
                li.innerText = cart[i];
                list.appendChild(li);
            }
        }
    </script>

</body>
</html>
