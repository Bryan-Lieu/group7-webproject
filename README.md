# **Flow Foods: A Smart Inventory & Waste Reduction System**

This repository will contain all the shared code work for team 7's smart inventory and waste reduction web project/web page that is designed for small restaurants and grocery stores to track as well as manage their inventory stock, as well as have a way to sell or donate near-expiry and overstocked food products/goods, as a means to reduce food waste and insecurity.

The web page was developed using HTML, CSS, Bootstrap, and JavaScript as the front-end, while having Google Firebase Firestore Database as the backend. All of which contribute to the web page's aesthetics, responsiveness, and interactiveness. 

## **Current Iteration:**

The **'Home Page'** features a carousel that highlights the purpose of the web page, as well as a section dedicated to various food banks that users can refer to if they wish to donate. 

The **'Discounts Page'** features a table of available discounts based on the entries on the inventory tracker page or 'inventory' page, displaying the quantity, expiration date, discount percentage, specific store or restaurant, and availability of the item being offered at a discount.

The **'Inventory Page'** is meant for the inventory managers/restaurant owners who put in various entries ranging from near-expiry, normal, to overstocked food items that could potentially be discounted and updated on the discounts page aftet the entry is entered in and registered into the Firestore database until it is removed or deleted. Additionally, all entries are capable of being edited.

Lastly, the **'About Us'** is, of course, where the web page further discusses our brand, purpose, and future goals. 

## **Work(s) in Progress**

Throughout all pages, there is a login authentication system that is functional with credentials that are saved directly into our Firebase backend as users with the **'Login'** and **'Register'** pages. However, we currently plan on making the system more secure overall, as the security of our users is crucial to the integrity of our platform. Moreover, we are continuing to research and develop a way to have the inventory page be accessible to restaurant owners/inventory managers. Hence, we believe that a step to achieving that could be implementing a way to specify during the sign-up/registration process, as well as a method of submitting proof for higher security. 

Additionally, we are looking into implementing an alert system for when a new item is added to the discounts table on the 'discounts page', which requires more research and practical testing in scripting (JavaScript) through Firebase. Ultimately, in the future, we also hope to be able to have the resources and capabilities to freely host the web page with a valid domain so that users can visit the web page through their browsers at any time. 

## **Deployment Instructions**

Download the latest zip file, extract it, and open up the **'index.html'** file to get started.
