TECH STACK:
Frontend Framework: React.js (with Vite for fast development)
Styling: Tailwind CSS
Routing: React Router DOM
Icons: React Icons
Development Environment: Visual Studio Code (VS Code)

Project Structure Overview:
src/
├── components/
│   ├── CompanyLogo.jsx
│   ├── DashboardLayout.jsx
│   ├── Footer.jsx
│   ├── Hero.jsx
│   ├── Login.jsx
│   ├── Navbar.jsx
│   ├── Newsletter.jsx
│   ├── ProductSection.jsx
│   ├── PurposeSection.jsx
├── App.jsx
├── App.css
├── index.css
├── main.jsx
vite.config.js

 Installation & Setup:
 # Step 1: Create a Vite project
npm create vite@latest

# Step 2: Install dependencies
npm install

# Step 3: Install Tailwind CSS with Vite support
npm install tailwindcss @tailwindcss/vite

# Step 4: Configure Vite for Tailwind in vite.config.js
# Add this:
import tailwindcss from '@tailwindcss/vite'
...
plugins: [tailwindcss()]

# Step 5: Add Tailwind directives to index.css
@import "tailwindcss";

# Step 6: Install additional packages
npm install react-icons --save
npm install react-router-dom

# Step 7: Run the development server
npm run dev


📌 Features Implemented
🔹 Homepage
Navbar: Includes company name, logo, and navigation links to About, Services, Dashboard, and Login.

Hero Section: Provides a brief introduction to the company.

Customer Interaction Form: Enables users to send messages to the company.

Products Section: Highlights the generator products offered.

Client Showcase: Displays existing clients.

Newsletter Subscription: Allows users to subscribe to updates.

Footer: Contains additional company details and useful links.

🔹 Authentication
Login Page: Secure login for users.

Registration Page: New user account creation.

🔹 Dashboard
Organized with multiple analytics and reporting sections:

Production & Manufacturing

Inventory Management

Quality Control & Testing

Order Fulfillment

Service & Maintenance

Employee & Resource Management




🧩 Key Files Explained
App.jsx: Main React component where routes and structure are defined.

App.css: Custom styles (if any) used globally.

index.css: Includes Tailwind CSS directives for utility-first styling.

main.jsx: Entry point that renders the <App /> component into the root DOM node.


✅ Contribution
This project was built as part of a group assignment. My specific role included:

Designing and building the homepage.

Implementing authentication pages.

Structuring and integrating the dashboard layout and analytics views.

Live Demo:https://68191386473e6a92fa844579--stellar-kringle-7334ff.netlify.app/
