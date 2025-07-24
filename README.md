# 👗 Virtual Closet – Enhancing Engagement and Retention

A full-stack web application that allows users to digitize their wardrobe, create outfits, get recommendations, and engage in social fashion activities — all with the goal of enhancing user interaction, loyalty, and retention.

---

## 💡 About

Users on platforms like Myntra tend to engage in short, transactional sessions. Our goal is to enhance personalization, increase session duration, and foster long-term user loyalty by introducing a virtual closet management feature that:

- Allows wardrobe organization
- Provides personalized outfit recommendations
- Encourages social sharing and engagement
- Offers loyalty-based rewards

---

## 🚀 Features

- 👤 **User Account Creation & Login**
- 🧥 **Upload Clothing Items**: Add images with associated attributes like color, size, and fabric.
- 🔍 **Search Wardrobe**: Filter and search your digital closet.
- 🧩 **Create & Save Outfits**: Build looks using uploaded items.
- 💡 **AI-Generated Outfit Suggestions**: Based on occasion, weather, or trending styles.
- 📲 **Share Outfits**: Social integration to share with friends or participate in challenges.
- 🎁 **Reward System**: Earn points for activity, redeemable for exclusive content or discounts.
- 📊 **User Analytics**: Insight-driven personalization and wardrobe gap detection.

---

## 🧠 Technologies Used

### Frontend
- HTML/CSS
- JavaScript
- EJS templating

### Backend
- Node.js
- Express
- MongoDB
- Passport.js (Authentication)

---

## 🗂 Folder Structure
```
Virtual-Closet/
│
├── public/
│ ├── app/ # Client-side JS for signup, login, outfits
│ └── css/ # Component-specific stylesheets
│
├── images/ # Uploaded user images
│
├── src/student/
│ ├── controller.js # Handles request logic
│ ├── queries.js # MongoDB operations
│ └── routes.js # API route definitions
│
├── views/ # EJS templates for rendering UI
│ ├── login.ejs
│ ├── signup.ejs
│ ├── outfits.ejs
│ ├── index.ejs
│ └── contactUs.ejs
│
├── app.js # Main Express configuration
├── server.js # App entry point
├── passport-config.js # Authentication strategy setup
├── package.json
└── README.md
```

---

## 🌐 Example User Experience: Sarah's Journey

- Uploads and organizes wardrobe in categories (tops, bottoms, accessories)
- Uses outfit suggestions for daily styling
- Purchases complementary pieces based on wardrobe insights
- Shares looks on social media and engages in challenges
- Earns rewards and redeems them for discounts and early access

---

## 🎯 Benefits

### 🧷 Personalization
- Recommendations based on user wardrobe and preferences
- Intelligent outfit combinations using existing items

### 💬 Interaction
- Increased user engagement via organization and outfit creation
- More frequent, meaningful sessions on the platform

### 🛍 Enhanced Shopping
- Detect wardrobe gaps and recommend purchases
- Virtual try-on (AR integration possible)

### 👥 Social & Community
- Share outfits and participate in fashion challenges

### 🏅 Retention & Loyalty
- Points for uploads, outfit creation, and engagement
- Unlock exclusive styling tips and early access to collections

---

## 🔐 Authentication

- Passport.js used for secure login & session handling
- Protected routes for accessing user closets and profiles

---

## 📈 Future Enhancements

- Integrate AR-based virtual try-on
- Machine learning for smarter recommendations
- Mobile app version
- Integration with real e-commerce APIs

---

## 🔧 Setup Instructions

Follow the steps below to run the Virtual Closet app locally:

### 📦 Prerequisites
- Node.js and npm installed
- MongoDB installed and running locally (or use MongoDB Atlas)

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/Virtual_Closet.git
cd Virtual_Closet
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables
- Create a `.env` file at the root (if not already present) and add:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET=your_secure_session_secret
```
> Replace your_mongodb_connection_string with your actual MongoDB URI.

> Replace SESSION_SECRET with a secure random string.

### 4. Run the Server

```bash
node server.js
```

### 5. Access the App
- Open your browser and navigate to: http://localhost:5000.
- You should see the Virtual Closet homepage.

---

## For Contributing
If you want to contribute to this project, please follow these steps:
- `Fork` the repository.
- Create a new branch `(git checkout -b feature/your-feature-name)`.
- Make your changes and commit them `(git commit -m 'Add some feature')`.
- Push to the branch `(git push origin feature/your-feature-name)`.
- Open a pull request.

---

## Project Maintainer
**Github:** [Swedeshna Mishra](https://github.com/SwedeshnaMishra)
