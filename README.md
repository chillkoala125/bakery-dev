# Development

### Link to Deployed Website
https://chillkoala125.github.io/bakery-dev/

### Goal and Value of the Application
The user can view pastries in the bakery and add them to cart. When browsing the pastries, they can filter by what is the best time to eat them (morning, afternoon, evening), or the size of the pastry (small, medium, large). They can sort the pastries by price, either from low to high or high to low.

### Usability Principles Considered

### Organization of Components
I have a BakeryItem component which contains all of the information related to displaying one item. Then, the FilteredList contains all of the functions related to filtering, sorting, and aggregating the items. The filtered list is displayed from the main App file. The state of the cart and which items are added to the cart is a state that is updated throughout the program. The list of items is a prop passed to the filtered list from the App file.

### How Data is Passed Down Through Components
Each item is passed to the list to be displayed, without having all of the information relating to the display of one item be in the main list file.

### How the User Triggers State Changes
The user triggers state changes by selecting different filters in the dropdown menu, or by selecting different sorting options. Then this state change changes the list of items that are displayed.


