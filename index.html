<?php

include 'config.php';

session_start();

$user_id = $_SESSION['user_id'];

if(!isset($user_id)){
   header('location:login.php');
}

if(isset($_POST['add_to_cart'])){

   $product_name = $_POST['product_name'];
   $product_discription = $_POST['product_discription'];
   $product_price = $_POST['product_price'];
   $product_image = $_POST['product_image'];
   $product_quantity = $_POST['product_quantity'];

   $check_cart_numbers = mysqli_query($conn, "SELECT * FROM `cart` WHERE name = '$product_name' AND user_id = '$user_id'") or die('query failed');

   if(mysqli_num_rows($check_cart_numbers) > 0){
      $message[] = 'already added to cart!';
   }else{
      mysqli_query($conn, "INSERT INTO `cart`(user_id, name,  price, quantity, image) VALUES('$user_id', '$product_name', '$product_price', '$product_quantity', '$product_image')") or die('query failed');
      $message[] = 'product added to cart!';
   }

}
?>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Acme&family=Bruno+Ace+SC&family=Caveat&family=Foldit&family=League+Spartan&display=swap"
    rel="stylesheet">
    
  <link rel="stylesheet" href="styles12.css">
</head>

<body>
<?php include 'header.php'; ?>
  

  

  <section id="hero">
    <h4>Trade-in-offer</h4>
    <h2>Super value deals</h2>
    <h1>On all products</h1>
    <p>Save more with coupons & up to 70% off!</p>
    <button style="width: 150px;"><a href="shop.php">Shop Now</a></button>

  </section>


  <section id="feature" class="section-p1">

    <div class="fe-box">
      <img id="shipping-img" src="images\free-shipping.png" alt="shiping-img">
      <h6>Free Shipping</h6>
    </div>

    <div class="fe-box">
      <img id="order-img" src="images\Online-order.png" alt="Order-img">
      <h6>Online Order</h6>
    </div>

    <div class="fe-box">
      <img id="money-img" src="images\save-money.png" alt="money-img">
      <h6>Save Money</h6>
    </div>

    <div class="fe-box">
      <img id="promotions-img" src="images\Promotion.png" alt="promotions-img">
      <h6>Promotions</h6>
    </div>

    <div class="fe-box">
      <img id="support-img" src="images\technical-support.png" alt="support-img">
      <h6>Support</h6>
    </div>

  </section>

  <section id="product1" class="section-p1">
    <h2>Featured Products For Men</h2>
    <p>Summer Collection New Modern Design </p>

    
      </div>

      <div class="pro-container">

      
      <div class="box-container1" >
      
      <?php  
         $select_products = mysqli_query($conn, "SELECT * FROM `products`") or die('query failed');
         if(mysqli_num_rows($select_products) > 0){
            while($fetch_products = mysqli_fetch_assoc($select_products)){
      ?>
     <form action="" method="post" class="box1">
      <img class="image" src="uploaded_img/<?php echo $fetch_products['image']; ?>" alt="">
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

      </div>

  </section>


  <section id="product1" class="section-p1">
    <h2>Featured Products For Women</h2>
    <p>Summer Collection New Modern Design </p>

    <div class="pro-container">
       
    <div class="box-container1" >
      
      <?php  
         $select_products = mysqli_query($conn, "SELECT * FROM `product2`") or die('query failed');
         if(mysqli_num_rows($select_products) > 0){
            while($fetch_products = mysqli_fetch_assoc($select_products)){
      ?>
     <form action="" method="post" class="box1">
      <img class="image" src="uploaded_img/<?php echo $fetch_products['image']; ?>" alt="">
      <div class="name"><?php echo $fetch_products['name']; ?></div>
      <div class="price">$<?php echo $fetch_products['price']; ?>/-</div>
      <input type="number" min="1" name="product_quantity" value="1" class="qty">
      <input type="hidden" name="product_name" value="<?php echo $fetch_products['name']; ?>">
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
      


      


      


      

    </div>

  </section>


  <section id="banner" class="section-m1">
    <h4>Repair Services</h4>
    <h2>Up To <span>70% Off</span> - All T-Shirts & Jackets </h2>
    <button class="normal">Explore More</button>
  </section>


  <section id="product1" class="section-p1">
    <h2>New Arrivals</h2>
    <p>Summer Collection New Modern Design </p>

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


  <section id="sm-banner" class="section-m1">
    <div class="banner-box">
      <h4>Crazy Deals</h4>
      <h2>buy 1 get 1 free</h2>
      <span>The Best Jackets & Shirts Is On Sale At SmartCart </span>
      <button class="white">Learn More</button>
    </div>

    <div class="banner-box banner-box2">
      <h4>Spring / Summer</h4>
      <h2>Upcoming Season</h2>
      <span>The Best Classic Dress Is On Sale At SmartCart </span>
      <button class="white">Collections</button>
    </div>

  </section>

  <section id="banner3">

    <div class="banner-box box1">
      <h2>SEASON SALE</h2>
      <h3>Winter Collection - 50% OFF</h3>
    </div>

    <div class="banner-box box2">
      <h2>NEW FOOTWARE COLLECTION</h2>
      <h3>Spring / Summer 2023</h3>
    </div>

    <div class="banner-box box3">
      <h2>T-SHIRTS</h2>
      <h3>New Trendy Prints</h3>
    </div>

  </section>


  <section id="newsletter" class="section-p1 section-m1">
    <div class="newstext">
      <h4>Sign Up For Newsletters</h4>
      <p>Get E-mail updates about our latest shop and <span>Special offer.</span> </p>
    </div>
    <div class="form">
      <input type="text" placeholder="Your E-mail Adress">
      <button class="normal">Sign Up</button>
    </div>
  </section>


  <footer class="section-p1">
    <div class="col">
      <img class="footer" src="images\DIY Logo Packages _ Logo Maker - Google Chrome 27-05-2023 20_21_15.png"
        alt="logo"><br><br>
      <h4>Contact</h4>
      <p><strong>Address:</strong> 562 Wellington Road , Street 32, San Farancisco </p>
      <p><strong>Phone:</strong> +01 2222 365 / (+91) 01 2345 6789</p>
      <p><strong>Hours:</strong> 10:00 - 18:00, Mon - Sat</p>
      <div class="follow">
        <h4>Follow Us:</h4><br>
        <img class="btn2" src="images\facebook.png" alt="facebook">
        <img class="btn2" src="images\instagram.png" alt="insta">
        <img class="btn2" src="images\twitter.png" alt="twitter">
        <img class="btn2" src="images\youtube.png" alt="youtube">
      </div>
    </div>

    <div class="col">
      <h4>About</h4>
      <a href="#">About us</a>
      <a href="#">Delivary Information</a>
      <a href="#">Privacy Policy</a>
      <a href="#">Terms & Conditions</a>
      <a href="#">Contact us</a>
    </div>

    <div class="col">
      <h4>My Account</h4>
      <a href="#">Sign in</a>
      <a href="#">View Cart</a>
      <a href="#">My Wishlist</a>
      <a href="#">Track My Order</a>
      <a href="#">Help</a>
    </div>


    <div class="col install">
      <h4>Install App</h4>
      <p>Form App Store or Google play</p>
      <div class="row">
        <p><img class="btn2" src="images\apple-logo.png" alt="">Apple Store</p>
        <p><img class="btn2" src="images\google-play.png" alt="">Google play</p>
      </div>
      <p>Secured Payment Gateways</p>
      <div class="row">
        <a href="#"><img class="btn2" src="images\google-pay.png" alt=""></a>
        <a href="#"><img class="btn2" src="images\visa.png" alt=""></a>
        <a href="#"><img class="btn2" src="images\credit-card.png" alt=""></a>
      </div>
    </div>
    <div class="copyright">
      <p>©️ 2023, SmartCart - Ecommerce platform</p>

    </div>


  </footer>

  
  <script src="index.js"></script>
</body>

</html