# Test cases

#### Preconditions:

- [Website](https://www.alexandermcqueen.com/en-us)

## Test case 1: Checking the availability of sizes

1. `Open "Kitwear" category`
2. `Click on the “Filter and Sort”`
3. `Select "44" and "46" in "Filter by size" group`
4. `Check whether the size of the products matches the filter condition`

**Expected result:** On the page only items with size 44-46 in stock.

## Test case 2: Adding item to the bag.

1. `Open item with id 27 (Men's Stack Chelsea Boot in Black)`
2. `Select "44" size`
3. `Click "Add to bag"`
4. `Click symbol of bag`

**Expected result:** The chosen item (id 27) size 44 is in the bag.

5. `Click "Checkout" at the pop-up menu`

**Expected result:** The chosen item (id 27) size 44 is in the bag.

## Test case 3: Adding item to the bag but with other size.

1. `Open item with id 27 (Men's Stack Chelsea Boot in Black)`
2. `Select "44" size`
3. `Click "Add to bag"`
4. `Select a "46" size`
5. `Click "Add to bag"`
6. `Click symbol of bag`

**Expected result:** Two selected items with id 27 are separately added to the bag with sizes "44" and "46".

## Test case 4: Removing item from the bag

1. `Open item with id 27 (Men's Stack Chelsea Boot in Black)`
2. `Select "44" size`
3. `Click "Add to bag"`
4. `Click symbol of bag`
5. `Click "Remove"`
6. `Click "Yes"`

**Expected result:** The chosen item is removed from the bag.

## Test case 5: Select size

1. `Open item with id 27 (Men's Stack Chelsea Boot in Black)`
2. `Select "44" size`

**Expected result:** If size 44 is available it is displayed under the price or if selected size is not available button "notify me when available" is displayed under the price.

## Test case 6: Find in store

1. `Open item with id 30 (Men's Leather Long Belt in Black)`
2. `Select a "Thailand" region`
3. `Select a "Bangkok" city `
4. `Select "95" size`
5. `Click "Check Availability"`

**Expected result:** The site will show whether product with id 30 (Men's Leather Long Belt in Black) is in stock (if so, in which store) or not in Bangkok.

## Test case 7:Adding item to the bag without selected size.

1. `Open item with id 30 (Men's Leather Long Belt in Black)`
2. `Try to click "Add to bag"`

**Expected result:** Instead of button "Add to bag" the "Please select the size" button is displayed.

## Test case 8: Viewing empty bag

1. `Click bag icon`

**Expected result:** The message "YOUR SHOPPING BAG IS EMPTY" is displayed.

## Test case 9: Searching for an item

1. `Click search icon`
2. `Type "Long Belt" in search bar`

**Expected result:** Possible variants of products with "Long Belt" keyword are displayed.

## Test case 10: Changing the number of item in the bag

1. `Open item with id 30 (Men's Leather Long Belt in Black)`
2. `Select "95"" size`
3. `Click "Add to bag"`
4. `Click symbol of bag`
5. `Click symbol + under the item`

**Expected result:** The number of items with id 30 (Men's Leather Long Belt in Black) and size "95" in the bag is 2.

## Test case 11: Price change after adding a second of the same item 

1. `Open item with id 30 (Men's Leather Long Belt in Black)`
2. `Select "95"" size`
3. `Click "Add to bag"`
4. `Click symbol of bag`
5. `Check the price opposite the item with id 30 (Men's Leather Long Belt in Black)`
5. `Click symbol + under the item`

**Expected result:** The price of items with id 30 (Men's Leather Long Belt in Black) size "95" in the bag is doubled.