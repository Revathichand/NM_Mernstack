To build this complete MERN eCommerce app, you’ll need to follow a few key setup steps for both the frontend and backend environments. Here’s a guide based on the information you've shared:

Backend Setup
1.Install Dependencies: Ensure you have Node.js and npm installed.

2.Clone the Project: If you haven’t already, clone the repository.

3.Environment Variables: In your backend .env file, define the following:
MONGODB_URL : ""
STRIPE_SECRET_KEY : "",
FRONTEND_URL : "",

4.Start the Server: Use the command:
npm run dev

5.Deploy: As you've deployed your backend on Render, the URL is available at https://backend-mern-kowt.onrender.com.MY Backend URL : https://backend-mern-kowt.onrender.com

Frontend Setup
1.Install Dependencies: Make sure you have React installed.

2.Environment Variables: In your frontend .env file, define:start : 
REACT_APP_SERVER_DOMIN = <backend url>
REACT_APP_ADMIN_EMAIL = <admin email id >
REACT_APP_STRIPE_PUBLIC_KEY  = <stripe public key>

3.Start the Frontend: To run the frontend, use:start : 
npm start
