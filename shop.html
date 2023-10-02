<?php

include 'config.php';

session_start();

$user_id = $_SESSION['user_id'];

if(!isset($user_id)){
   header('location:login.php');
}

if(isset($_POST['add_to_cart'])){

   $product_name = $_POST['product_name'];
   $product_discription=$_POST['product_discription'];
   $product_price = $_POST['product_price'];
   $product_image = $_POST['product_image'];
   $product_quantity = $_POST['product_quantity'];

   $check_cart_numbers = mysqli_query($conn, "SELECT * FROM `cart` WHERE name = '$product_name' AND user_id = '$user_id'") or die('query failed');

   if(mysqli_num_rows($check_cart_numbers) > 0){
      $message[] = 'already added to cart!';
   }else{
      mysqli_query($conn, "INSERT INTO `cart`(user_id, name, price, quantity, image) VALUES('$user_id', '$product_name', '$product_price', '$product_quantity', '$product_image')") or die('query failed');
      $message[] = 'product added to cart!';
   }

}
?>

<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>shop</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="styles12.css">

</head>
<body id="shopbody">
   
<?php include 'header.php'; ?>

<section id="banner" class="section-m1">
    <h2>New Collections</h2>
    <h2>Up To <span>70% Off</span> - All T-Shirts & Jackets </h2>
    <button class="normal">Explore More</button>
  </section>

<section class="products">

   <h1 style="text-align: center;" class="title">latest products</h1>
   
   <div class="pro-container">

      
<div class="box-container2" >

<?php  
   $select_products = mysqli_query($conn, "SELECT * FROM `products`") or die('query failed');
   if(mysqli_num_rows($select_products) > 0){
      while($fetch_products = mysqli_fetch_assoc($select_products)){
?>
<form action="" method="post" class="box4">
<img class="image1" style="height: 70%;" src="uploaded_img/<?php echo $fetch_products['image']; ?>" alt="">
<div class="name"><?php echo $fetch_products['name']; ?></div>
<div class="discription"><?php echo $fetch_products['discription']; ?></div>
<div class="price">$<?php echo $fetch_products['price']; ?>/-</div>
<input type="number" min="1" name="product_quantity" value="1" class="qty">
<input type="hidden" name="product_name" value="<?php echo $fetch_products['name']; ?>">
<input type="hidden" name="product_discription" value="<?php echo $fetch_products['discription']; ?>">
<input type="hidden" name="product_price" value="<?php echo $fetch_products['price']; ?>">
<input type="hidden" name="product_image" value="<?php echo $fetch_products['image']; ?>">
<input type="submit" value="add to cart" name="add_to_cart" class="btn">
</form>
<?php
   }
}else{
   echo '<p class="empty">no products added yet!</p>';
}
?>
</div>
</section>
<section id="product1" class="section-p1">
    

    <div class="pro-container">

      <div class="pro">
        <img class="clothes" src="images\f8.webp" alt="hoodie">
        <div class="desc">
          <span>REPLAY</span>
          <h5>Checked Zip-Front Shacket</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$205</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\Round neck t-shirt .webp" alt="hoodie">
        <div class="desc">
          <span>REPLAY</span>
          <h5>Camo Print Zip-Front Shacket with Flap Pockets</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$210</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\gucci men t-shirt.webp" alt="hoodie">
        <div class="desc">
          <span>REPLAY</span>
          <h5>Quilted Checked Shirt with Flap Pockets</h5>
          <h5>⭐⭐⭐⭐</h5>
          <h3>$185</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\f22.webp" alt="hoodie">
        <div class="desc">
          <span>REPLAY</span>
          <h5>Crust Zip-Front Jacket</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$540</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\f23.webp" alt="hoodie">
        <div class="desc">
          <span>NIDHI YASHA</span>
          <h5>Embellished Jacket</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$545</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\f24.webp" alt="hoodie">
        <div class="desc">
          <span>ALL SAINTS</span>
          <h5>Dalby Suede Tailored Fit Biker Jacket</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$52</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\f25.webp" alt="hoodie">
        <div class="desc">
          <span>RIO</span>
          <h5>Quilted Hooded Jacket with Insert Pockets</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$87</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>


      <div class="pro">
        <img class="clothes" src="images\f26.webp" alt="hoodie">
        <div class="desc">
          <span>KETCH</span>
          <h5>Denim Jacket with Flap Pockets</h5>
          <h5>⭐⭐⭐⭐⭐</h5>
          <h3>$99</h3>
        </div>
        <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
      </div>

    </div>

  </section>
<?php include 'footer.php'; ?>
<!-- custom js file link  -->
<script src="js/script.js"></script>
</body>
</html>