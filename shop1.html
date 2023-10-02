
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
      mysqli_query($conn, "INSERT INTO `cart`(user_id, name,discription, price, quantity, image) VALUES('$user_id', '$product_name', $product_discription,'$product_price', '$product_quantity', '$product_image')") or die('query failed');
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
    <link rel="stylesheet" href="style1.css">
</head>

<body>

    <section id="header">

        <a href="#"><img id="logo-img"
                src="images\DIY Logo Packages _ Logo Maker - Google Chrome 27-05-2023 20_21_15.png" alt="com-logo"></a>
        <div>
            <ul id="navbar">
                <li><a href="index.php">Home</a></li>
                <li><a class="active" href="shop.php">shop</a></li>
                <li><a href="about.php">About</a></li>
                <li><a href="contact.php">Contact</a></li>
                <li><a href="cart.php"><img class="cart-img" src="images\shopping-cart (1).png" alt="cart-img"></a>
                </li>

            </ul>
        </div>

    </section>


    <section id="page-header">
        <h2>#Stayhome</h2>
        <p>Save more with coupons & up to 70% off!</p>
    </section>


     <section id="product1" class="section-p1">
    <h2>Featured Products For Men</h2>
    <p>Summer Collection New Modern Design </p>

  </section>
    
  <div class="pro-container">
    <div class="box-container1">
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
      }?></div>
   <section id="banner" class="section-m1">
    <h4>Repair Services</h4>
    <h2>Up To <span>70% Off</span> - All T-Shirts & Jackets </h2>
    <button class="normal">Explore More</button>
  </section>
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

            <div class="pro">
                <img class="clothes" src="images\f12.webp" alt="hoodie">
                <div class="desc">
                    <span>COTTINFAB</span>
                    <h5>Checked Front-Open Jacket with Puff Sleeves</h5>
                    <h5>⭐⭐⭐⭐⭐</h5>
                    <h3>$60</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro">
                <img class="clothes" src="images\f13.jpg" alt="hoodie">
                <div class="desc">
                    <span>SHAYE</span>
                    <h5>Floral Print Open Front Shrug</h5>
                    <h5>⭐⭐⭐⭐</h5>
                    <h3>$68</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro">
                <img class="clothes" src="images\f15.webp" alt="hoodie">
                <div class="desc">
                    <span>KETCH</span>
                    <h5>Denim Jacket with Flap Pockets</h5>
                    <h5>⭐⭐⭐⭐⭐</h5>
                    <h3>$63</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro">
                <img class="clothes" src="images\f14.webp" alt="hoodie">
                <div class="desc">
                    <span>SHAYE</span>
                    <h5>Floral Print Shrug with Kimono Sleeves</h5>
                    <h5>⭐⭐⭐⭐⭐</h5>
                    <h3>$120</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro">
                <img class="clothes" src="images\f16.webp" alt="hoodie">
                <div class="desc">
                    <span>LE ESPRESSO</span>
                    <h5>Lace Shrug</h5>
                    <h5>⭐⭐⭐⭐⭐</h5>
                    <h3>$52</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro">
                <img class="clothes" src="images\f17.webp" alt="hoodie">
                <div class="desc">
                    <span>AZIRA</span>
                    <h5>Floral Print Front-Open Shrug</h5>
                    <h5>⭐⭐⭐⭐⭐</h5>
                    <h3>$87</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro">
                <img class="clothes" src="images\f18.webp" alt="hoodie">
                <div class="desc">
                    <span>LEE COOPER</span>
                    <h5>Button-Front Jacket with Back Placement Applique</h5>
                    <h5>⭐⭐⭐⭐⭐</h5>
                    <h3>$109</h3>
                </div>
                <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
            </div>


            <div class="pro-container">

                <div class="pro">
                    <img class="clothes" src="images\f19.webp" alt="hoodie">
                    <div class="desc">
                        <span>REPLAY</span>
                        <h5>Checked Zip-Front Shacket</h5>
                        <h5>⭐⭐⭐⭐⭐</h5>
                        <h3>$205</h3>
                    </div>
                    <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
                </div>


                <div class="pro">
                    <img class="clothes" src="images\f20.webp" alt="hoodie">
                    <div class="desc">
                        <span>REPLAY</span>
                        <h5>Camo Print Zip-Front Shacket with Flap Pockets</h5>
                        <h5>⭐⭐⭐⭐⭐</h5>
                        <h3>$210</h3>
                    </div>
                    <a href="#"><img class="cart" src="images\shopping-cart (1).png" alt="cart"></a>
                </div>


                <div class="pro">
                    <img class="clothes" src="images\f21.webp" alt="hoodie">
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


    <section id="next-page" class="section-p1">
        <a href="#">1</a>
        <a href="#">2</a>
        <a href="#"><img id="btn" src="images\right-arrow.png" alt="Arrow"></a>
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
                <img class="btn" src="images\facebook.png" alt="facebook">
                <img class="btn" src="images\instagram.png" alt="insta">
                <img class="btn" src="images\twitter.png" alt="twitter">
                <img class="btn" src="images\youtube.png" alt="youtube">
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
                <p><img class="btn" src="images\apple-logo.png" alt="">Apple Store</p>
                <p><img class="btn" src="images\google-play.png" alt="">Google play</p>
            </div>
            <p>Secured Payment Gateways</p>
            <div class="row">
                <a href="#"><img class="btn" src="images\google-pay.png" alt=""></a>
                <a href="#"><img class="btn" src="images\visa.png" alt=""></a>
                <a href="#"><img class="btn" src="images\credit-card.png" alt=""></a>
            </div>
        </div>
        <div class="copyright">
            <p>©️ 2023, SmartCart - Ecommerce platform</p>

        </div>


    </footer>


    <script src="index.js"></script>
</body>

</html