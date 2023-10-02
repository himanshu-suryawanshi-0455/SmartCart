<?php

include 'config.php';

session_start();

$user_id = $_SESSION['user_id'];

if(!isset($user_id)){
   header('location:login.php');
}

?>

<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>orders</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="style1.css">

</head>
<body>
   
<?php include 'header.php'; ?>



<section class="placed-orders">
<h1>  Your Order</h1>
   <h1 class="title" style="text-align: center;" >placed orders</h1><br>

   <div class="box-container"  > 

      <?php
         $order_query = mysqli_query($conn, "SELECT * FROM `orders` WHERE user_id = '$user_id'") or die('query failed');
         if(mysqli_num_rows($order_query) > 0){
            while($fetch_orders = mysqli_fetch_assoc($order_query)){
      ?>
      <div class="box" style="width: 35%; border: 1px solid grey; border-radius:10px; margin-left: 32%; padding: 20px; " >
         <p> <b>placed on :</b> <span><?php echo $fetch_orders['placed_on']; ?></span> </p>
         <p> <b>name :</b> <span><?php echo $fetch_orders['name']; ?></span> </p>
         <p> <b>number :</b> <span><?php echo $fetch_orders['number']; ?></span> </p>
         <p> <b>email :</b> <span><?php echo $fetch_orders['email']; ?></span> </p>
         <p> <b>address :</b> <span><?php echo $fetch_orders['address']; ?></span> </p>
         <p> <b>payment method :</b> <span><?php echo $fetch_orders['method']; ?></span> </p>
         <p> <b>your orders :</b> <span><?php echo $fetch_orders['total_products']; ?></span> </p>
         <p> <b>total price :</b> <span>$<?php echo $fetch_orders['total_price']; ?>/-</span> </p>
         <p> <b>payment status :</b> <span style="color:<?php if($fetch_orders['payment_status'] == 'pending'){ echo 'red'; }else{ echo 'green'; } ?>;"><?php echo $fetch_orders['payment_status']; ?></span> </p>
         </div><br><br>
      <?php
       }
      }else{
         echo '<p class="empty">no orders placed yet!</p>';
      }
      ?>
   </div>

</section>








<?php include 'footer.php'; ?>

<!-- custom js file link  -->
<script src="js/script.js"></script>

</body>
</html>