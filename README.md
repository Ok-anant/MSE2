# MSE2
📋 Project Summary & Features Project Name: ShopEasy Type: React-based E-commerce Shopping Application

✨ Key Features Implemented:

Product Catalog Display of multiple products with images, names, prices, ratings, and descriptions Products loaded from products.json with diverse categories Real product images from Unsplash
Search Functionality Real-time search across product names, descriptions, and categories Search input field in the header with clear button Instant filtering as user types
Category Filtering 8 product categories available: All, Electronics, Footwear, Clothing, Kitchen, Sports, Accessories, Home Click-based category selection with active state indicators Reset to "All" to view all products
Price Range Filtering 6 price range options: All Prices | Under ₹500 | ₹500–₹1,000 | ₹1,000–₹2,000 | ₹2,000–₹4,000 | ₹4,000+ Real-time price filtering with active state display
Sorting Options Default - Original order Price (Low to High) - Ascending price sort Price (High to Low) - Descending price sort Rating - Sort by customer ratings A-Z - Alphabetical name sorting
Shopping Cart System Add products to cart with one click Cart sidebar panel that slides in from the right Cart automatically opens when item is added Cart Features: Display all cart items with images and prices Quantity controls (+ / −) for each item Remove items with delete button Real-time total price calculation Item count badge on cart button Empty cart message with shopping bag icon Close cart button and overlay
User Interface Components Header Component:
ShopEasy logo with shopping bag icon Search bar with placeholder and clear functionality Cart button with item count badge Filters Component:

Category filter panel Price range selection Sort options dropdown Results count display Product Card Component:

Product image Name and rating display Price in Indian Rupees (₹) format Description preview "Add to Cart" button Cart Panel:

Overlay to close cart Header with "Your Cart" title Product list with images and quantity controls Total price calculation Empty state message 8. Technical Implementation Built with React 19.2.5 Uses React Hooks (useState, useMemo) for state management Efficient filtering and sorting with useMemo for performance Responsive CSS styling with modern design 9. Data & Formatting Products stored in products.json Indian Rupee (₹) currency formatting Rating system (1-5 stars) Multiple product attributes (id, name, category, price, rating, image, description).

🔄 State Management The app manages the following states:

searchQuery - Current search text priceRange - Selected price filter (min/max) category - Selected product category sortBy - Current sorting method cartItems - Products in shopping cart with quantities cartOpen - Cart panel visibility toggle ✅ Workflow User enters search query → Real-time filtering User selects category → Filters products by category User selects price range → Filters by price User selects sort option → Reorders results User clicks "Add to Cart" → Item added/quantity increased, cart opens User modifies quantity or removes items → Cart updates Total price displays in real-time
