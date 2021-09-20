# Woocommerce-Style-Reset
**A scss boilerplate for customizing woocommerce styles**

Add this to your theme's function.php file to deque the woo default styles

 ```php 
 function your_handler_function () {
    wp_enqueue_style('woo.css' ,get_stylesheet_directory_uri() . '/woo.css',[], null);
}
add_action( 'wp_enqueue_scripts', 'your_handler_function' );
```

Use the scss files to customize you woo theme.