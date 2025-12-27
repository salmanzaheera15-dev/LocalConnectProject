# LocalConnectProject
Name: Salman Zaheer 
Reg#   B24F1476CS119
FINAL LAB PROJECT 
LocalConnect ‒ Local Marketplace Web Application
"This project was developed for the Data Structures and Algorithms (DSA) course under the supervision of Lab Engineer Obaidullah Miakhil."
1.	INTRODUCTION
LocalConnect is a full-stack web marketplace created as a semester project. It allows buyers to browse 
local products and vendors to manage orders. The project demonstrates HTML, CSS, JavaScript,
 Node.js, Express, MySQL, and Data Structures & Algorithms like Hash Map and Quick Sort.

2.	MAIN FEATURES
•	User registration and login (email & password)
•	Buyer and Vendor roles
•	Vendors can list products
•	Buyers can browse, sort, and order products
•	Cart functionality with dynamic totals
•	Quick Sort used for sorting products
•	Hash Map used for fast product lookup
•	MySQL database used for authentication, products, and orders
•	Clean UI with tabs for Buyer and Vendor views
3.	SYSTEM ARCHITECTURE
Frontend:
•	HTML builds the page structure
•	CSS handles the layout and colors
•	JavaScript handles user interaction, sorting, cart, and API calls
Backend:
•	Node.js + Express API server
•	Routes for auth, products, orders
•	MySQL database connection
 
Database Tables:
•	users(id, name, email, password, role)
•	products(id, vendor_id, name, price, distance_km)
•	orders(id, buyer_id, total_price)
•	order_items(id, order_id, product_id, quantity)
4.	DATA STRUCTURES & ALGORITHMS USED
Hash Map:
Used in the frontend to store and fetch products quickly by ID.
Quick Sort:
Implemented for sorting:
•	Nearest products first
•	Price low-to-high
•	Price high-to-low
This demonstrates algorithm efficiency.
5.	WORKFLOW SUMMARY
Buyer Flow:
1.	Register → Login
2.	Browse products
3.	Sort products
4.	Add products to cart
5.	Place order
Vendor Flow:
1.	Login
2.	View customer orders for their products
 
6.	UI THEME & CUSTOMIZATION
All colors, layout, and spacing come from styles.css.
Changing primary colors like #2563eb updates buttons, header, tabs, etc.
7.	LEARNING OUTCOMES
This project demonstrates:
•	Frontend + Backend integration
•	REST API development
•	Database connectivity
•	Authentication system
•	DSA implementation in real-world UI
•	Clean UI/UX structure
•	Full-stack deployment readiness
8.	CONCLUSION
LocalConnect is a complete, polished semester project demonstrating practical
full-stack development, problem-solving, and algorithmic thinking. It can be extended with features like 
images, payments, OTP login, and notifications.



