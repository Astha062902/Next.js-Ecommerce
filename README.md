# **E-Commerce Platform**

## **Project Overview**

This project is a full-featured e-commerce web application designed to provide secure user authentication and personalized shopping experiences. Developed with a focus on performance and scalability, the platform allows users to manage their shopping cart in real-time, even across sessions, and provides an admin interface for streamlined product management.

## **Key Features**

- **User Authentication:** Secure user login and registration using NextAuth with persistent sessions across logins.
- **Dynamic Cart Updates:** Real-time updates to the shopping cart, ensuring a seamless user experience.
- **Product Management:** An intuitive admin interface built with Next.js and Prisma for easy product additions and management.
- **Persistent Data:** Shopping cart data remains intact across sessions, ensuring that users find their items in the cart even after logging out and logging back in.

## **Technology Stack**

- **Next.js:** A React framework for building server-rendered web applications.
- **MongoDB:** A NoSQL database used for storing user data, products, and cart information.
- **Prisma:** An ORM for managing database interactions, ensuring efficient and type-safe access to data.
- **NextAuth:** A library for handling user authentication in Next.js applications.

## **Deployment**

This application is deployed on Vercel, offering seamless deployment with Next.js optimizations.

**[Live Demo](https://next-js-ecommerce-r59rrcrit-asthapanda02-gmailcoms-projects.vercel.app/)**

## **Screenshots**
## **Home Page**
The homepage serves as the primary entry point for users, showcasing all available products in a clean and organized layout. At the top, there is a featured product section highlighting a key item that might be on sale or new in the store. Below, all products are displayed with essential details like name, price, and a brief description. The design is responsive, ensuring a seamless experience across devices. This page is optimized for quick navigation, allowing users to easily browse through categories or jump straight to a product of interest.

![Home Page](images/home.png)

## **Products Page**
The single product page offers an in-depth view of an individual product. It displays high-quality images, detailed descriptions, pricing information, and availability status. Users can see product specifications, customer reviews, and related products. The page also includes a prominent "Add to Cart" button. When a product is added to the cart, a confirmation message appears, enhancing the shopping experience by providing immediate feedback. This page is crucial for converting browsing into purchasing by offering all necessary information to make an informed decision.

![Product Page](images/add-to-cart.png)

## **Search Results Page**
The search results page is designed to help users find specific products quickly. When a user enters a search term, the page dynamically displays all matching products. For example, searching for "camera" will filter the product listings to show only those that contain the term "camera" in their name, description, or tags. Each result is presented with a thumbnail image, product name, price, and a brief snippet of the description. This feature enhances user experience by making it easier to locate desired items, especially in large catalogs.

![Search Results Page](images/search-function.png)

## **Cart Page**
The cart page is where users can review the products they intend to purchase. It lists each item added to the cart, along with the quantity, price, and subtotal. Users can adjust quantities, remove items, or proceed to checkout from this page. At the bottom, the total cost, including any applicable taxes and shipping fees, is clearly displayed. This page ensures that users have a complete overview of their order before finalizing the purchase, making it a critical step in the shopping process.

![Cart Page](images/cart.png)

## **Add Products Page**
The add products page is an admin-only interface where administrators can manage the store's inventory. It provides a simple form where admins can input product details such as name, price, description, category, and upload images. Once submitted, the product is immediately added to the website and the database, making it available for purchase. This page is essential for maintaining an up-to-date product catalog and ensuring that new items can be quickly and efficiently added to the store. The intuitive layout makes it easy for admins to keep the product offerings fresh and relevant.

![Add Products Page](images/add-product.png)



## **Demo Video**

Check out the application in action with our [Demo Video](https://drive.google.com/file/d/17dDXJXKbLOcgE1kEQLHTH_56I9DFuqQQ/view?usp=drive_link).

## **Use Cases**

1. **Personalized Shopping Experience:** Users enjoy a customized experience with persistent cart data and secure authentication.
2. **Efficient Product Management:** Admins can easily add and manage products, optimizing operations.
3. **Real-Time Updates:** The dynamic cart updates in real-time, ensuring a smooth shopping experience.
