## **Test-cases**

*Web-site:* [Lyle & Scott ](https://row.lyleandscott.com/)

------

#### 1. Add a Hat to the Basket

**Preconditions:**

- *Caps & Hats* page is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click on **[Racked Rib Beanie](https://row.lyleandscott.com/products/racked-rib-beanie-true-black)** |                                                              |
|    2    | Click on the **1SZ** size                                    |                                                              |
|    3    | Click on the **Add to bag** button                           | Pop-up with *Item added to bag* text and **View bag** button is opened |

------

#### 2. Making the checkout from the bag

**Preconditions:**

- Website [Lyle & Scott ](https://row.lyleandscott.com/) is opened;
- **Racked Rib Beanie** is in the bag.

**Test steps:**

| Step ID | Action                                                    | Expected result           |
| :-----: | --------------------------------------------------------- | ------------------------- |
|    1    | Click **[BAG](https://row.lyleandscott.com/cart)** button |                           |
|    2    | Click **Go to checkout** button                           | *Checkout* page is opened |

------

#### 3. Delete item from the bag

**Preconditions:**

- Website [Lyle & Scott](https://row.lyleandscott.com/) is opened;
- **Racked Rib Beanie** is in the bag.

**Test steps:**

| Step ID | Action                                                    | Expected result                                              |
| :-----: | :-------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click **[BAG](https://row.lyleandscott.com/cart)** button |                                                              |
|    2    | Click **Remove** button near **Racked Rib Beanie**        | Page is refreshed. *Your bag is currently empty!Check out our recommendations below* text is showed. |

------

#### 4. Adding item to the Wishlist

**Preconditions:**

- *Bags* page is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                       |
| :-----: | :----------------------------------------------------------- | ------------------------------------- |
|    1    | Click on **[Reporter Bag](https://row.lyleandscott.com/products/reporter-bag-true-black)** |                                       |
|    2    | Click **heart icon** (add to the Wishlist) near the price    | *Saved* text near the icon is showed. |

------

#### 5. Deleting item from the Wishlist

**Preconditions:**

- **Reporter Bag** is in the Wishlist;
- Website [Lyle & Scott](https://row.lyleandscott.com/) is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click on **[heart icon](https://row.lyleandscott.com/pages/wishlist)** on the main page |                                                              |
|    2    | Hover over the **Reporter bag** picture                      | *Remove* and *Add to bag* buttons are displayed on the picture |
|    3    | Click **Remove** button on the **Reporter bag** picture      | Wishlist is empty. *You’ve got 0 items saved in your wishlist* text is showed. |

------

#### 6. Search Reporter Bag

**Preconditions:**

- Website [Lyle & Scott](https://row.lyleandscott.com/) is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click on **search icon** on the main page                    |                                                              |
|    2    | Type *Reporter Bag* in the search text field and click **search** or **Enter** button | Page with searching results is opened. *2 results for Reporter bag* text is showed. Pictures with Reporter Bags are showed. |

------

#### 7. Changing selected color of the item

**Preconditions:**

- *Scarves & Gloves* page is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click on the **[Tartan Lambswool Scarf](https://row.lyleandscott.com/products/tartan-lambswool-scarf-victory-orange-olive-jet-black)** |                                                              |
|    2    | In the *color selection* section click on the *black color*  | The text near *Colour* changed to *Jet Black/Olive/Light Grey Marl*. Pictures are changed according to the chosen color. URL is changed to *https://row.lyleandscott.com/products/tartan-lambswool-scarf-jet-black-olive-light-grey-marl* |

------

#### 8. Changing quantity of items from the bag

**Preconditions:**

- **[Tartan Lambswool Scarf](https://row.lyleandscott.com/products/tartan-lambswool-scarf-jet-black-olive-light-grey-marl?variant=40853897085028)** is in the bag (quantity is *1*);
- Website [Lyle & Scott](https://row.lyleandscott.com/) is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click **[BAG](https://row.lyleandscott.com/cart)** button    |                                                              |
|    2    | Near the quantity of the **Tartan Lambswool Scarf** click on the **plus icon** | Quantity is changed to *2*. Price near **Tartan Lambswool Scarf**, near *2 ITEMS* title and near *SUBTOTAL* is changed to **$110.00**. |

------

#### 9. Enter invalid Discount Code

**Preconditions:**

- **[Tartan Lambswool Scarf](https://row.lyleandscott.com/products/tartan-lambswool-scarf-jet-black-olive-light-grey-marl?variant=40853897085028)** is in the bag (quantity is *2*);
- Website [Lyle & Scott](https://row.lyleandscott.com/) is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click **[BAG](https://row.lyleandscott.com/cart)** button    |                                                              |
|    2    | Click **Go to checkout** button                              |                                                              |
|    3    | Type *LyleAndScott* into field *Discount Code* and click **Apply** button | Border color of the *Discount Code* text field is changed to red. Red message with *Enter a valid discount code* is showed. |

------

#### 10. Enter valid Customer information for Checkout

**Preconditions:**

- **[Tartan Lambswool Scarf](https://row.lyleandscott.com/products/tartan-lambswool-scarf-jet-black-olive-light-grey-marl?variant=40853897085028)** is in the bag (quantity is *2*);
- **[BAG](https://row.lyleandscott.com/cart)** is opened;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Click **Go to checkout** button                              | *Checkout* page is opened                                    |
|    2    | Fill in all required text fields with valid information: <br />Email: *vladshabusov66@gmail.com*<br />Country/Region: *United States*<br />Last name: *Shabusov*<br />Address: *915 South Jackson Street*<br />City: *Montgomery*<br />State: choose *Alabama* from the drop list<br />Zip code: *36104*<br />And click **Continue to Shipping Information** button | *Shipping* page is opened. *Contact* and *Ship to* information are showed. |

------

#### 11. Trying to pay with PayPal

**Preconditions:**

- Shipping page is opened (after the previous test case).

**Test steps:**

| Step ID | Action                                            | Expected result                                              |
| :-----: | :------------------------------------------------ | ------------------------------------------------------------ |
|    1    | Choose **Standard International** shipping method | Shipping price near *Shipping* text is displayed (*$25.00*). Total price is *$135.00*. |
|    2    | Click **Continue to payment** button              | *Payment method* page is opened                              |
|    3    | In the *Payment* section choose **PayPal**        |                                                              |
|    4    | Click **Complete order** button                   | Page *Log in to your PayPal account* is opened               |