# MERN-App-Ebay

Mern App hosted on GCP - https://homework3571.uc.r.appspot.com/

Video Link - https://www.youtube.com/watch?v=7UDws7lmIe8&ab_channel=RishiNareddy

**Project Overview:**
The project involves creating a responsive web application that allows users to search for products using the eBay API. The application includes features such as product search, detailed product information dislay, wish list management, and integration with external APIs like Ipinfo, Google Customized Search, etc. The technology stack includes AJAX and JSON for data handling, HTML5, Bootstrap, and React for the frontend, and Node.js with Express for the backend. MongoDB is used as a NoSQL database for storing product wish lists, and the entire application is deployed on Google Cloud Platform (GCP).

**Key Technologies and Practices:**
1. **Frontend:**
   - React: Used for building the responsive user interface, including the search form, result table, and detail views.
   - Bootstrap: Employed for responsive design, enhancing the user experience across different devices.
   - AJAX and JSON: Utilized for handling asynchronous requests and data interchange.

2. **Backend:**
   - Node.js with Express: Implemented on the server side for handling backend logic, routing, and API requests.
   - Axios Library: Used for making requests from the Node.js backend to eBay servers and interacting with external APIs.

3. **Database:**
   - MongoDB: Chosen as the NoSQL database for storing product wish lists, providing flexibility in handling unstructured data.

4. **Cloud Platform:**
   - Google Cloud Platform (GCP): Deployed both the backend and frontend to GCP, ensuring scalability and accessibility.

5. **External APIs:**
   - eBay API: Integrated for product search and retrieval of detailed product information.
   - IpInfo API: Used to obtain the current user location using geolocation APIs.
   - Geonames API: Used for autocomplete for zip code by using the suggestion service provided by Geonames.
   - Google Customized Search API: Used to retrieve photos related to the searched product.

6. **User Experience:**
   - Responsive Design: Bootstrap used to create a responsive and mobile-friendly website.
   - Validation and Error Handling: Implemented validation for search form inputs and appropriate error messages.
   - Progress Bars: Dynamic progress bars displayed during data fetching to provide feedback to the user.

7. **Additional Features:**
   - Wish List Management: Users can add or remove products to/from their wish list, stored in MongoDB.
   - Facebook Integration: Option to share product information on Facebook.
   - Pagination: Implemented for navigating through search results.

**Note:** React is used instead of Angular, and the entire application is hosted on GCP, following best practices for cloud deployment. The project emphasizes a comprehensive tech stack to create a functional and user-friendly e-commerce web application.


_In accordance with class policy, code shared only on demand from prospective employers._
