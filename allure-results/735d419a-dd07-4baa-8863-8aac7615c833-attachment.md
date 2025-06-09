# Test info

- Name: execute end-to-end test flow @end-to-end
- Location: D:\playwright\self_framework\opencart\tests\EndToEndTest.spec.ts:30:5

# Error details

```
Error: locator.click: Test timeout of 30000ms exceeded.
Call log:
  - waiting for locator('strong:has-text("View Cart")')

    at ProductPage.clickViewCart (D:\playwright\self_framework\opencart\pages\ProductPage.ts:72:32)
    at verifyShoppingCart (D:\playwright\self_framework\opencart\tests\EndToEndTest.spec.ts:160:66)
    at D:\playwright\self_framework\opencart\tests\EndToEndTest.spec.ts:53:5
```

# Page snapshot

```yaml
- navigation:
  - button "$ Currency ":
    - strong: $
    - text: Currency 
  - list:
    - listitem:
      - link "":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/contact
      - text: "123456789"
    - listitem:
      - link " My Account":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/account
    - listitem:
      - link " Wish List (0)":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/wishlist
    - listitem:
      - link " Shopping Cart":
        - /url: https://tutorialsninja.com/demo/index.php?route=checkout/cart
    - listitem:
      - link " Checkout":
        - /url: https://tutorialsninja.com/demo/index.php?route=checkout/checkout
- banner:
  - heading "Qafox.com" [level=1]:
    - link "Qafox.com":
      - /url: https://tutorialsninja.com/demo/index.php?route=common/home
  - textbox "Search": MacBook
  - button ""
  - button " 0 item(s) - $0.00" [expanded]
  - list:
    - listitem:
      - paragraph: Your shopping cart is empty!
- navigation:
  - list:
    - listitem:
      - link "Desktops":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=20
    - listitem:
      - link "Laptops & Notebooks":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=18
    - listitem:
      - link "Components":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=25
    - listitem:
      - link "Tablets":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=57
    - listitem:
      - link "Software":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=17
    - listitem:
      - link "Phones & PDAs":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=24
    - listitem:
      - link "Cameras":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=33
    - listitem:
      - link "MP3 Players":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/category&path=34
- list:
  - listitem:
    - link "":
      - /url: https://tutorialsninja.com/demo/index.php?route=common/home
  - listitem:
    - link "Search":
      - /url: https://tutorialsninja.com/demo/index.php?route=product/search&search=MacBook
  - listitem:
    - link "MacBook":
      - /url: https://tutorialsninja.com/demo/index.php?route=product/product&search=MacBook&product_id=43
- list:
  - listitem:
    - link "MacBook":
      - /url: https://tutorialsninja.com/demo/image/cache/catalog/demo/macbook_1-500x500.jpg
      - img "MacBook"
  - listitem:
    - link "MacBook":
      - /url: https://tutorialsninja.com/demo/image/cache/catalog/demo/macbook_5-500x500.jpg
      - img "MacBook"
  - listitem:
    - link "MacBook":
      - /url: https://tutorialsninja.com/demo/image/cache/catalog/demo/macbook_4-500x500.jpg
      - img "MacBook"
  - listitem:
    - link "MacBook":
      - /url: https://tutorialsninja.com/demo/image/cache/catalog/demo/macbook_2-500x500.jpg
      - img "MacBook"
  - listitem:
    - link "MacBook":
      - /url: https://tutorialsninja.com/demo/image/cache/catalog/demo/macbook_3-500x500.jpg
      - img "MacBook"
- list:
  - listitem:
    - link "Description":
      - /url: "#tab-description"
  - listitem:
    - link "Specification":
      - /url: "#tab-specification"
  - listitem:
    - link "Reviews (0)":
      - /url: "#tab-review"
- paragraph: Intel Core 2 Duo processor
- paragraph: Powered by an Intel Core 2 Duo processor at speeds up to 2.16GHz, the new MacBook is the fastest ever.
- paragraph: 1GB memory, larger hard drives
- paragraph: The new MacBook now comes with 1GB of memory standard and larger hard drives for the entire line perfect for running more of your favorite applications and storing growing media collections.
- paragraph: Sleek, 1.08-inch-thin design
- paragraph: MacBook makes it easy to hit the road thanks to its tough polycarbonate case, built-in wireless technologies, and innovative MagSafe Power Adapter that releases automatically if someone accidentally trips on the cord.
- paragraph: Built-in iSight camera
- paragraph: Right out of the box, you can have a video chat with friends or family,2 record a video at your desk, or take fun pictures with Photo Booth
- button ""
- button ""
- heading "MacBook" [level=1]
- list:
  - listitem:
    - text: "Brand:"
    - link "Apple":
      - /url: https://tutorialsninja.com/demo/index.php?route=product/manufacturer/info&manufacturer_id=8
  - listitem: Product Code:Product 16
  - listitem: Reward Points:600
  - listitem: Availability:Out Of Stock
- list:
  - listitem:
    - heading "$602.00" [level=2]
  - listitem: Ex Tax:$500.00
- text: Qty
- textbox "Qty": "2"
- button "Add to Cart"
- paragraph:
  - text:     
  - link "0 reviews":
    - /url: ""
  - text: /
  - link "Write a review":
    - /url: ""
- separator
- contentinfo:
  - heading "Information" [level=5]
  - list:
    - listitem:
      - link "About Us":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/information&information_id=4
    - listitem:
      - link "Delivery Information":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/information&information_id=6
    - listitem:
      - link "Privacy Policy":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/information&information_id=3
    - listitem:
      - link "Terms & Conditions":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/information&information_id=5
  - heading "Customer Service" [level=5]
  - list:
    - listitem:
      - link "Contact Us":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/contact
    - listitem:
      - link "Returns":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/return/add
    - listitem:
      - link "Site Map":
        - /url: https://tutorialsninja.com/demo/index.php?route=information/sitemap
  - heading "Extras" [level=5]
  - list:
    - listitem:
      - link "Brands":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/manufacturer
    - listitem:
      - link "Gift Certificates":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/voucher
    - listitem:
      - link "Affiliate":
        - /url: https://tutorialsninja.com/demo/index.php?route=affiliate/login
    - listitem:
      - link "Specials":
        - /url: https://tutorialsninja.com/demo/index.php?route=product/special
  - heading "My Account" [level=5]
  - list:
    - listitem:
      - link "My Account":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/account
    - listitem:
      - link "Order History":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/order
    - listitem:
      - link "Wish List":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/wishlist
    - listitem:
      - link "Newsletter":
        - /url: https://tutorialsninja.com/demo/index.php?route=account/newsletter
  - separator
  - paragraph:
    - text: Powered By
    - link "OpenCart":
      - /url: http://www.opencart.com
    - text: Qafox.com © 2025
```

# Test source

```ts
   1 | import { Page, Locator, expect } from '@playwright/test';
   2 | import { ShoppingCartPage } from './ShoppingCartPage'; // Import ShoppingCartPage if needed
   3 |
   4 | export class ProductPage {
   5 |     private readonly page: Page;
   6 |     
   7 |     // Locators using CSS selectors
   8 |     private readonly txtQuantity: Locator;
   9 |     private readonly btnAddToCart: Locator;
  10 |     private readonly cnfMsg: Locator;
  11 |     private readonly btnItems: Locator;
  12 |     private readonly lnkViewCart: Locator;
  13 |
  14 |     constructor(page: Page) {
  15 |         this.page = page;
  16 |         
  17 |         // Initialize locators with CSS selectors
  18 |         this.txtQuantity = page.locator('input[name="quantity"]');
  19 |         this.btnAddToCart = page.locator('#button-cart');
  20 |         this.cnfMsg = page.locator('.alert.alert-success.alert-dismissible');
  21 |         this.btnItems = page.locator('#cart');
  22 |         this.lnkViewCart = page.locator('strong:has-text("View Cart")');
  23 |     }
  24 |
  25 |     /**
  26 |      * Sets the product quantity
  27 |      * @param qty - Quantity to set
  28 |      */
  29 |     async setQuantity(qty: string): Promise<void> {
  30 |         await this.txtQuantity.fill('');
  31 |         await this.txtQuantity.fill(qty);
  32 |     }
  33 |
  34 |     /**
  35 |      * Adds product to cart
  36 |      */
  37 |     async addToCart(): Promise<void> {
  38 |         await this.btnAddToCart.click();
  39 |     }
  40 |
  41 |     /**
  42 |      * Checks if confirmation message is visible
  43 |      * @returns Promise<boolean> - Returns true if message is visible
  44 |      */
  45 |     async isConfirmationMessageVisible(): Promise<boolean> {
  46 |         try {
  47 |             if(this.cnfMsg!=null){
  48 |                  return true;
  49 |             }
  50 |             else{
  51 |                 return false;
  52 |             }//await expect(this.cnfMsg).toBeVisible();
  53 |            
  54 |         } catch (error) {
  55 |             console.log(`Confirmation message not found: ${error}`);
  56 |             return false;
  57 |         }
  58 |     }
  59 |
  60 |     /**
  61 |      * Clicks on Items button to navigate to cart
  62 |      */
  63 |     async clickItemsToNavigateToCart(): Promise<void> {
  64 |         await this.btnItems.click();
  65 |     }
  66 |
  67 |     /**
  68 |      * Clicks on View Cart link
  69 |      * @returns Promise<ShoppingCartPage> - Returns ShoppingCartPage instance
  70 |      */
  71 |     async clickViewCart(): Promise<ShoppingCartPage> {
> 72 |         await this.lnkViewCart.click();
     |                                ^ Error: locator.click: Test timeout of 30000ms exceeded.
  73 |         return new ShoppingCartPage(this.page);
  74 |     }
  75 |
  76 |     /**
  77 |      * Complete workflow to add product to cart
  78 |      * @param quantity - Quantity of product to add
  79 |      */
  80 |     async addProductToCart(quantity: string): Promise<void> {
  81 |         await this.setQuantity(quantity);
  82 |         await this.addToCart();
  83 |         await this.isConfirmationMessageVisible();
  84 |     }
  85 | }
```