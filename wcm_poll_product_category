<?php
    $all_ids = get_posts( array(
      'post_type' => 'product',
      'numberposts' => -1,
      'post_status' => 'publish',
      'fields' => 'ids',
      'tax_query' => array(
          array(
           'taxonomy' => 'product_cat',
           'field' => 'slug',
           'terms' => 'accessories',
           'operator' => 'IN',
           )
        ),
       ));


       foreach ( $all_ids as $productId ) {

        /*
        $product = wc_get_product( $productId );
        echo $product->get_title();
        echo $product->get_price_html();
        */

       }
?>
