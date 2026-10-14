# ReThread 👕♻️
### Give Clothes a Second Life

ReThread is a full-stack clothing and fashion platform designed to make shopping, selling, and reusing clothes easier. It combines online shopping with clothing exchange concepts to encourage sustainable fashion and reduce clothing waste.

## 🚀 Features

- **User Authentication** – Login and user access management.
- **Online Shopping** – Browse and explore available clothing products.
- **Product Selling** – List clothing items for sale.
- **Checkout System** – Manage the checkout process.
- **Admin Dashboard** – Manage platform activities and products.
- **Backend API Integration** – Connect frontend pages with backend services.
- **Database Management** – Store and manage application data using MongoDB.
- **Organized Architecture** – Separate routes, models, configuration, and middleware.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Frontend structure |
| CSS3 | Styling and layout |
| JavaScript | Frontend functionality |
| Node.js | Backend runtime |
| Express.js | Backend framework and APIs |
| MongoDB | Database |
| Git & GitHub | Version control |

## 📂 Project Structure

```text
ReThread/
├── public/
├── server/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── seed.js
│   └── server.js
├── admin.html
├── checkout.html
├── index.html
├── login.html
├── sell.html
├── shop.html
├── script.js
├── styles.css
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- MongoDB or a MongoDB Atlas connection

### 1. Clone the Repository

```bash
git clone https://github.com/aryashinde2811-pixel/ReThread.git
```

### 2. Navigate to the Project Directory

```bash
cd ReThread
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root or in the location expected by your backend configuration. Add the environment variables required by your application, such as your MongoDB connection string and authentication secret.

**Important:** Never upload database credentials, API keys, or authentication secrets to GitHub.

### 5. Start the Backend Server

```bash
node server/server.js
```

Make sure your MongoDB connection is configured correctly before starting the server.

### 6. Open the Frontend

Open `index.html` in your browser or use the local development server appropriate for your project setup.

## 📖 How to Use

1. Open the ReThread website.
2. Log in to access the available features.
3. Browse clothing products in the shop.
4. Explore the selling and checkout pages.
5. Use the admin dashboard for administrative operations.

*Available functionality depends on the features implemented and configured in the current version.*

## 🔮 Future Enhancements

- AI-powered outfit recommendations.
- Personalized clothing suggestions.
- Improved clothing exchange functionality.
- Advanced product search and filters.
- Order tracking and purchase history.
- Enhanced mobile responsiveness.
- Sustainability insights and clothing reuse statistics.

## 👩‍💻 Developed By

**Arya Shinde**

GitHub: [aryashinde2811-pixel](https://github.com/aryashinde2811-pixel)

## 📄 License

This project is developed for educational purposes. Add a specific open-source license if you intend to distribute it under particular reuse and modification terms.
