<?php

include 'config.php';

session_start();

$user_id = $_SESSION['user_id'];

if(!isset($user_id)){
   header('location:login.php');
}

if(isset($_POST['order_btn'])){

   $name = mysqli_real_escape_string($conn, $_POST['name']);
   $number = $_POST['number'];
   $email = mysqli_real_escape_string($conn, $_POST['email']);
   $method = mysqli_real_escape_string($conn, $_POST['method']);
   $address = mysqli_real_escape_string($conn, 'flat no. '. $_POST['flat'].', '. $_POST['street'].', '. $_POST['city'].', '. $_POST['country'].' - '. $_POST['pin_code']);
   $placed_on = date('d-M-Y');

   $cart_total = 0;
   $cart_products[] = '';

   $cart_query = mysqli_query($conn, "SELECT * FROM `cart` WHERE user_id = '$user_id'") or die('query failed');
   if(mysqli_num_rows($cart_query) > 0){
      while($cart_item = mysqli_fetch_assoc($cart_query)){
         $cart_products[] = $cart_item['name'].' ('.$cart_item['quantity'].') ';
         $sub_total = ($cart_item['price'] * $cart_item['quantity']);
         $cart_total += $sub_total;
      }
   }

   $total_products = implode(', ',$cart_products);

   $order_query = mysqli_query($conn, "SELECT * FROM `orders` WHERE name = '$name' AND number = '$number' AND email = '$email' AND method = '$method' AND address = '$address' AND total_products = '$total_products' AND total_price = '$cart_total'") or die('query failed');

   if($cart_total == 0){
      $message[] = 'your cart is empty';
   }else{
      if(mysqli_num_rows($order_query) > 0){
         $message[] = 'order already placed!'; 
      }else{
         mysqli_query($conn, "INSERT INTO `orders`(user_id, name, number, email, method, address, total_products, total_price, placed_on) VALUES('$user_id', '$name', '$number', '$email', '$method', '$address', '$total_products', '$cart_total', '$placed_on')") or die('query failed');
         $message[] = 'order placed successfully!';
         mysqli_query($conn, "DELETE FROM `cart` WHERE user_id = '$user_id'") or die('query failed');
      }
   }
   
}

?>

<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>checkout</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="styles12.css">

</head>
<body>
   
<?php include 'header.php'; ?>

<div class="heading" style="text-align:center; margin: 100px; height: 150px;" >
   <h3 style="color:white;">checkout</h3>
   <p style="text-align:center;"> <h1 style="color:white;" >home / checkout</h1> </p>
</div>


<section class="checkout" style=" padding-bottom: 50px; ">

   <form action="" method="post" style="border: 2px solid grey; border-radius:20px; width:30%; text-align: left; margin-left: 35%; padding: 20px 50px 40px 50px; ">
      <h3 style="text-align: center; ">Place Your Order</h3><hr>
      <div class="flex">
         <div class="inputBox" style="padding: 4px; ">
            <span>your name :</span>
            <input type="text" style="margin-left:45px;" name="name" required placeholder="enter your name">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>your number :</span>
            <input type="number" style="margin-left:30px;" name="number" required placeholder="enter your number">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>your email :</span>
            <input type="email" style="margin-left:47px;" name="email" required placeholder="enter your email">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>payment method :</span>
            <select name="method" style="margin-left:30px; width: 140px ; ">
               <option value="cash on delivery">cash on delivery</option>
               <option value="credit card">credit card</option>
               <option value="paypal">paypal</option>
               <option value="paytm">paytm</option>
            </select>
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>address line 01 :</span>
            <input type="number" style="margin-left:10px;" min="0" name="flat" required placeholder="e.g. Flat no.">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>address line 01 :</span>
            <input type="text" style="margin-left:10px;" name="street" required placeholder="e.g. Street name">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>city :</span>
            <input type="text" style="margin-left:95px;" name="city" required placeholder="e.g. Jalna ">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>state :</span>
            <input type="text" style="margin-left:85px;" name="state" required placeholder="e.g. Maharashtra">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>country :</span>
            <input type="text" style="margin-left:67px;" name="country" required placeholder="e.g. India">
         </div>
         <div class="inputBox" style="padding: 4px; ">
            <span>pin code :</span>
            <input type="number" style="margin-left:60px;" min="0" name="pin_code" required placeholder="e.g. 123456">
         </div>
      </div  >
      <div style="text-align: center;" ><br>
      <input type="submit" style="border:1px solid grey; margin: 10px; " value="Order now" class="btn" name="order_btn">
      </div>
   </form>

</section>

<section class="display-order" style="text-align: center; padding-bottom: 50px;">

   <?php  
      $grand_total = 0;
      $select_cart = mysqli_query($conn, "SELECT * FROM `cart` WHERE user_id = '$user_id'") or die('query failed');
      if(mysqli_num_rows($select_cart) > 0){
         while($fetch_cart = mysqli_fetch_assoc($select_cart)){
            $total_price = ($fetch_cart['price'] * $fetch_cart['quantity']);
            $grand_total += $total_price;
   ?>
   <p> <?php echo $fetch_cart['name']; ?> <span>(<?php echo '$'.$fetch_cart['price'].'/-'.' x '. $fetch_cart['quantity']; ?>)</span> </p>
   <?php
      }
   }else{
      echo '<p class="empty">your cart is empty</p>';
   }
   ?>
   <div class="grand-total"> grand total : <span>$<?php echo $grand_total; ?>/-</span> </div>

</section>









<?php include 'footer.php'; ?>

<!-- custom js file link  -->
<script src="js/script.js"></script>

</body>
</html>