# E-Commerce - MERN
Full-Stack E-Commerce web application with Admin Dashboard & Paytm Payment Gateway.


## 🖥️ Tech Stack
**Frontend:**

![reactjs](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)&nbsp;
![react-router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)&nbsp;
![redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)&nbsp;
![tailwindcss](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)&nbsp;
![mui](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)&nbsp;
![chart-js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)&nbsp;

**Backend:**

![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)&nbsp;
![expressjs](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)&nbsp;
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![jwt](	https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)&nbsp;

**Payment Gateway:**

![paytm](https://img.shields.io/badge/paytm-white?logo=paytm&logoColor=blue&labelColor=white
)

**Cloud Storage:** [Cloudinary](https://cloudinary.com/)

**Mail Service:** [Sendgrid](https://sendgrid.com/)


## 🛠️ Setup Instructions
**Prerequisites**

- Node.js

- MongoDB

- Paytm account for Payment Gateway

- Sendgrid account for Email Service

- Cloudinary account for Cloud Storage

**Installation**

**1. Clone the repository:**

git clone https://github.com/your-username/e-commerce-mern.git
- cd e-commerce-mern


**2. Backend Setup:**

1. Navigate to the backend directory:
- cd backend

2. Install dependencies:
- npm install

- Create a .env file in the backend directory and add the following environment variables:

**Copy code:**

PORT=5000

MONGO_URI=your_mongo_uri

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret

SENDGRID_API_KEY=your_sendgrid_api_key

PAYTM_MID=your_paytm_mid

PAYTM_KEY=your_paytm_key

PAYTM_WEBSITE=WEBSTAGING

PAYTM_CHANNEL_ID=WEB

PAYTM_INDUSTRY_TYPE_ID=Retail

PAYTM_CALLBACK_URL=http://localhost:5000/api/payment/callback

3. Start the backend server:
   
npm start

**3. Frontend Setup:**

1. Navigate to the frontend directory:
   
cd ../frontend

2. Install dependencies

npm install

3. Create a .env file in the frontend directory and add the following environment variables:


REACT_APP_API_URL=http://localhost:5000/api

REACT_APP_PAYTM_MID=your_paytm_mid

4. Start the frontend development server:

npm start

**Running the Application**

1. Ensure MongoDB is running.

2. Start the backend server (from the backend directory):

npm start

3. Start the frontend server (from the frontend directory):

npm start

Open your browser and navigate to http://localhost:3000 to see the application in action.



## 🚀 Features

**User Account Management**
- Login/Signup: 🚪 Users can create an account or log in to an existing one.
- Update Profile/Password: 🔐 Users can update their profile information and change their passwords.
  
**Password Management**
- Reset Password Mail: 📧 Utilizing Sendgrid, users can reset their passwords via email.
  
**Shopping Cart**
- Add/Remove Items: 🛒 Users can add items to their shopping cart or remove them as needed.
- Update Quantities: 🔢 Quantities of items in the cart can be adjusted.
  
**Saved Items**
- Save For Later: 💾 Users can move items from the cart to a "Saved For Later" list or remove them from it.
  
**Wishlist**
- Add/Remove Items: ❤️ Users can add items to their wishlist or remove them from it.
  
**Product Browsing**
- Pagination: 📚 Products are paginated, with 12 products displayed per page by default.
- Search: 🔍 Users can search for products.
- Filters: 🎛️ Products can be filtered based on categories, ratings, and price range.
  
**Checkout Process**
- Shipping Info: 🚚 Shipping information is stored in session storage for ease of checkout.
- Payment Options: 💳 Users can pay through Paytm payment gateway for checkout.
  
**Order Management**
- My Orders: 📦 Users can view their order history with various filters.
- Order Details: ℹ️ Details of all ordered items are accessible.
- Order Confirmation: ✉️ Users receive email notifications with comprehensive order details upon placing an order.
  
**Product Interaction**
- Review Products: 🌟 Users can review products.
  
**Admin Features**
- Dashboard: 🖥️ Admins have access to a dedicated dashboard.
- Order Management: 📊 Admins can update order statuses and delete orders.
- Product Management: 📝 Admins can add/update products.
- User Management: 👥 Admins can update user data and delete users.
- Review Management: 📜 Admins can view and delete product reviews.
- Stock Management: 📉 Product stock is automatically decreased upon shipment.


**📸 Screenshots**
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/64949957/153996560-bd631f30-46f0-4248-83b3-d8ce44a8f9e4.PNG" alt="mockup" /></td>
    <td><img src="https://user-images.githubusercontent.com/64949957/153996577-57b1a82d-064a-49dc-9055-e2bceb854ab2.PNG" alt="mockups" /></td>
  </tr>
</table>

<h2>📬 Contact</h2>

Feel free to reach me through the below handles if you'd like to contact me.

[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashk6645/)

