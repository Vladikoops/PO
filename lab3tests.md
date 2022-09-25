# Test cases

#### Preconditions:

- [Website](https://www.alexandermcqueen.com/en-us)

## Test case 1: Checking valid email address.

1. `Scroll page till the end.`
2. `Enter "qwerty" in the text field "Email Address" in the block "Subscribe".`
3. `Press "Send".`

**Expected result:** The message "Invalid email format. Please try again, example "john.smith@email.com".".

## Test case 2: Adding item to the cart.

1. `Choose "Mens" in the upper-menu.`
2. `Choose "Knit Wear"`
3. `Select the item.`
4. `Select the size.`
5. `Press "Add to cart".`
6. `Press "Checkout" at the pop-up menu.`

**Expected result:** The chosen item is in the cart.

## Test case 3: Find in store

1. `Choose "Mens" in the upper-menu.`
2. `Choose "Knit Wear"`
3. `Select the item.`
4. `Select the size.`
5. `Press "Add to cart".`
6. `Select a country/region`
7. `Choose city`
8. `Press "Check Availability"`

**Expected result:** The site will show whether the selected product is in stock (if so, in which store) or not.

## Test case 4: Checking the availability of sizes

1. `Choose "Mens" in the upper-menu.`
2. `Choose "Sneakers"`
3. `Press on the “Filter and Sort”`
4. `Select “44-46” in "Filter by size" group`
5. `Check whether the size of the products matches the filter condition.`

**Expected result:** On the page only items with size 44-46 in stock.