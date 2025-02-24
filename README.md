# 🍽️ Forkify - Recipe Search App

## 📌 Overview
Forkify is a modern web application that enables users to search for recipes, view detailed cooking instructions, bookmark favorite recipes, and add their own custom recipes.
This project is a practical implementation of advanced JavaScript concepts, following the MVC (Model-View-Controller) architecture, and emphasizes responsive design and user-friendly interactions.

🔗 **Live Demo:** [Forkify App](https://forkify-asaad.netlify.app/)  
📂 **GitHub Repository:** [Forkify Repo](https://github.com/asaadmansour/forkify)

---

## 🚀 Features
- 🔍 **Search Recipes:** Fetch recipes from the Forkify API based on ingredients or dish names.
- 📖 **Detailed Recipe View:** Displays ingredients, preparation time, and cooking steps.
- 🔢 **Adjust Servings:** Dynamically update ingredient quantities based on desired servings.
- ❤️ **Bookmark Recipes:** Save favorite recipes to local storage for later use.
- ➕ **Add Custom Recipes:** Submit your own recipes, which are stored in the API.
- 🔄 **State Management:** Uses the Publisher-Subscriber pattern for seamless UI updates.
- 🎨 **Responsive UI:** Optimized for desktop and mobile viewing.

---

## 🛠️ Technologies Used
- **Frontend:** JavaScript (ES6+), HTML, CSS
- **Architecture:** MVC (Model-View-Controller)
- **API:** Forkify API (for fetching recipes)
- **State Management:** Publisher-Subscriber Pattern
- **Asynchronous JS:** Fetch API, Promises, Async/Await
- **Build Tools:** Parcel.js (for bundling)
- **Version Control:** Git & GitHub
- **Hosting:** Netlify

---

## 📁 Folder Structure
```
forkify/
├── src/
│   ├── css/
│   │   └── styles.scss       # Main SCSS stylesheet
│   ├── img/                  # Image assets
│   ├── js/
│   │   ├── helpers.js        # Helper functions
│   │   ├── model.js          # Application state and business logic
│   │   ├── views/            # View classes for UI components
│   │   ├── controller.js     # Application controller
│   │   └── config.js         # Configuration constants
│   └── index.html            # HTML template
├── .gitignore                # Git ignore file
├── package.json              # Project metadata and dependencies
└── README.md                 # Project documentation
```
## 🔓 How To Run Project Locally
1. Clone the repository: ```git clone https://github.com/asaadmansour/forkify.git```
2. Navigate to the project directory: ``` cd forkify ```
3. Install dependencies: ``` npm install ```
4. Start the development server: ``` npm start ```

## How To Use The Application

### 🔍 Search for Recipes:
- Enter a keyword (e.g., "pasta") into the search bar and press **Enter**.
- Browse through the search results displayed on the **left panel**.

### 📖 View Recipe Details:
- Click on a recipe from the search results to view its details on the **right panel**.
- Adjust the number of servings to automatically update ingredient quantities.

### ❤️ Bookmark Recipes:
- Click the **bookmark icon** on a recipe to save it.
- Access bookmarked recipes by clicking the **bookmark icon in the header**.

### ➕ Add a New Recipe:
- Click the **"Add Recipe"** button in the header.
- Fill out the form with your recipe details and submit.
- The new recipe will be uploaded and saved in your bookmarks.

---

## ✅ Best Practices Followed:

- **MVC Architecture**: Separates concerns by dividing the application into **Model, View, and Controller**.
- **Asynchronous Programming**: Utilizes **async/await** for handling API requests.
- **Error Handling**: Implements **try/catch** blocks to manage errors gracefully.
- **Responsive Design**: Ensures compatibility across various devices using **SCSS**.
- **Module Bundling**: Uses **Parcel** for efficient asset bundling and dependency management.
