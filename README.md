# Amazon-Apparel-Recommendations

Recommending similar products (apparel) to the given product (apparel) in any e-commerce websites.

## Statement

Product recommendations are the alternative way of navigating through the online shop. Showing similar products to the user which user is searching for.

## Objective:

The recommendation engine, uses information about 1,80,000 products and each product will have multiple features named.
We will try multiple techniques using text/title and image to recommend similar products/items
Each product/item has 19 features in the raw dataset out of these 19 features, we will be using only 6 features

1. asin ( Amazon standard identification number)
2. brand ( brand to which the product belongs to )
3. color ( Color information of apparel, it can contain many colors as a value ex: red and black stripes )
4. product_type_name (type of the apperal, ex: SHIRT/TSHIRT )
5. medium_image_url ( url of the image )



## Approach to Solution

Using idf_w2v, brand, color, image features for finding the similar images using weighted average method.
