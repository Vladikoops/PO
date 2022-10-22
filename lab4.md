# Test cases

#### Preconditions:

- [Website](https://www.alexandermcqueen.com/en-us)

## Test case 1: Checking the availability of sizes

1. `Open link on the category`
2. `Click on the “Filter and Sort”`
3. `Select “44-46” in "Filter by size" group`
4. `Check whether the size of the products matches the filter condition`

**Expected result:** On the page only items with size 44-46 in stock.

## Test case 2: Adding item to the bag.

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to bag"`
4. `Click symbol of bag`

**Expected result:** The chosen item with all selected atributes is in the bag.

## Test case 3: Adding item to the bag but with other size.

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to bag"`
4. `Select a different size`
5. `Click "Add to bag"`
6. `Click symbol of bag`

**Expected result:** Two selected items are separately added to the bag with different sizes.

4. `Click "Checkout" at the pop-up menu`

**Expected result:** The chosen item with all selected atributes is in the bag.

## Test case 4: Removing item from the bag

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to bag"`
4. `Click symbol of bag`
5. `Click "Remove"`
6. `Click "Yes"`

**Expected result:** The chosen item is removed from the bag.

## Test case 5: Select size

1. `Open link on the item`
2. `Select the size`

**Expected result:** If selected size is available it is displayed under the price or if selected size is not available button "notify me when available" is displayed under the price.

## Test case 6: Find in store

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to bag"`
4. `Select a country/region`
5. `Choose city`
6. `Click "Check Availability"`

**Expected result:** The site will show whether the selected product is in stock (if so, in which store) or not.

## Test case 7:Adding item to the bag without selected size.

1. `Open link on the item`
2. `Try to click "Add to bag"`

**Expected result:** Instead of button "Add to bag" the "Please select the size" button is displayed.

## Test case 8: Viewing empty bag

1. `Click bag icon`

**Expected result:** The message "YOUR SHOPPING BAG IS EMPTY" is displayed.

## Test case 9: Searching for an item

1. `Click search icon`
2. `Type your keyword in search bar`

**Expected result:** Possible variants of products with this keyword are displayed.

## Test case 10: Changing the number of item in the bag

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to bag"`
4. `Click symbol of bag`
5. `Click symbol + under the item`

**Expected result:** The number of items in the bag is 2.

## Test case 11: Price change after adding a second of the same item 

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to bag"`
4. `Click symbol of bag`
5. `Check the price opposite the item`
5. `Click symbol + under the item`

**Expected result:** The price of items in the bag is doubled.