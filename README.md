**🛒 QuickCart — Blinkit-Style E-Commerce App**  
A full-stack e-commerce web application inspired by Blinkit, built with **React**,  **Node.js**,  **Express**,  **MongoDB**, and  **Tailwind CSS**. Features a responsive storefront, secure authentication, admin panel, Stripe payments, and Cloudinary image management.  
🔗 **Live Demo:** [quick-cart-e-commerce-k4fg.vercel.app](https://quick-cart-e-commerce-k4fg.vercel.app/ "https://quick-cart-e-commerce-k4fg.vercel.app/")  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANUlEQVR4nO3OQQmAABRAsSdYxZ4/mJjEsxE8W8GbCFuCLTOzVXsAAPzFuVZ3dXw9AQDgtesBxPEF3bv7x0IAAAAASUVORK5CYII=)  
**✨ Features**  
- **Responsive UI** — Mobile-friendly design that works seamlessly across all screen sizes  
- **User Authentication** — Signup, login, password reset, OTP verification via Resend, and email confirmation  
- **Product Management** — Browse, search, and filter products with Cloudinary-powered image uploads  
- **Shopping Cart & Checkout** — Dynamic cart with real-time updates and smooth checkout flow  
- **Stripe Payments** — Secure, PCI-compliant payment processing  
- **Admin Panel** — Manage products, users, and orders from a dedicated dashboard  
- **Optimized APIs** — RESTful backend with an average response time of ~120ms  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANElEQVR4nO3OQQmAABRAsSdYxKY/jMFMIZ7ECt5E2BJsmZmt2gMA4C+Otbqr8+sJAACvXQ85QgYXd/O+eQAAAABJRU5ErkJggg==)  
**🧰 Tech Stack**  
| | |  
|-|-|  
| **Layer** | **Technology** |   
| Frontend | React, Vite, Tailwind CSS |   
| Backend | Node.js, Express |   
| Database | MongoDB |   
| Payments | Stripe |   
| Image Storage | Cloudinary |   
| Email / OTP | Resend |   
| Auth | JWT, bcrypt |   
   
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANElEQVR4nO3OUQmAABBAsSeIWMICprwEpjSIFfwTYUuwZWaO6goAgL+412qrzq8nAAC8tj8tdQNNdXaCdAAAAABJRU5ErkJggg==)  
**📁 Project Structure**  
QuickcartBlinkit/  
 ├── client/          # React frontend (Vite)  
 │   ├── src/  
 │   │   ├── components/  
 │   │   ├── pages/  
 │   │   └── ...  
 │   └── package.json  
 ├── server/          # Node.js backend  
 │   ├── routes/  
 │   ├── controllers/  
 │   ├── models/  
 │   └── package.json  
 └── README.md  
   
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANklEQVR4nO3OQQmAABRAsSfYxZo/kSGMYQLPJrCCNxG2BFtmZquOAAD4i3Ot7mr/egIAwGvXA4qrBdGuSdJuAAAAAElFTkSuQmCC)  
**🚀 Getting Started**  
**Prerequisites**  
Make sure you have the following installed:  
- [Node.js (v18+)](https://nodejs.org/ "https://nodejs.org/")  
- [MongoDB (local or Atlas)](https://www.mongodb.com/ "https://www.mongodb.com/")  
- A [Stripe account](https://stripe.com/ "https://stripe.com/")  
- A [Cloudinary account](https://cloudinary.com/ "https://cloudinary.com/")  
- A [Resend account (for OTP/email)](https://resend.com/ "https://resend.com/")  
**1. Setup the Server**  
cd server  
 npm install  
   
Create a .env file in the server/ directory:  
Start the server:  
npm run dev  
   
**2. Setup the Client**  
cd ../client  
 npm install  
   
Create a .env file in the client/ directory:  
Start the frontend:  
npm run dev  
   
The app will be available at http://localhost:5173.  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANklEQVR4nO3OQQmAABRAsScYxpg/h5VMYARvRrCCNxG2BFtmZquOAAD4i3Ot7mr/egIAwGvXA224BcUMk6pDAAAAAElFTkSuQmCC)  
**🛠️ Scripts**  
**Client**  
| | |  
|-|-|  
| **Command** | **Description** |   
| npm run dev | Start development server |   
| npm run build | Build for production |   
| npm run preview | Preview production build |   
   
**Server**  
| | |  
|-|-|  
| **Command** | **Description** |   
| npm run dev | Start server with nodemon |   
| npm start | Start server in production |   
   
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANUlEQVR4nO3OMQ2AABAAsSNBCUpfD6ZYGZDAgAU2QtIq6DIzW7UHAMBfHGt1V+fXEwAAXrseHCoGAe/SKtAAAAAASUVORK5CYII=)  
**🤝 Contributing**  
Contributions are welcome! Feel free to fork this repo and submit a pull request.  
1. Fork the repository  
2. Create your feature branch (git checkout -b feature/your-feature)  
3. Commit your changes (git commit -m 'Add some feature')  
4. Push to the branch (git push origin feature/your-feature)  
5. Open a Pull Request  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANElEQVR4nO3OQQmAUBBAwSf8GGLWDWFDY3ixgjcRZhLMNjNHdQYAwF9cq1rV/vUEAIDX7gcRXAQ2s/16gwAAAABJRU5ErkJggg==)  
