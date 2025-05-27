# Meal-suggestion-app
# 📱 Meal Suggestion App

A simple Android app that suggests a meal based on the time of day. Users input a time like **"Morning"**, **"Afternoon"**, or **"Dinner"**, and receive a random meal suggestion. The app includes a reset feature and is integrated with **GitHub Actions** for automated testing and builds.

---

## ✨ Features

- ⏰ Input time of day: Morning, Mid-morning, Afternoon, Mid-afternoon, Dinner
- 🍽️ Get random meal suggestions
- 🔁 Reset button to clear input and output
- 🛠️ Built in **Kotlin** using **Android Studio**
- ✅ CI/CD pipeline with **GitHub Actions**

---

## 📸 Screenshots
*(Include app screenshots here, optional)*

---

## 🚀 Getting Started

### 📦 Requirements

- Android Studio Hedgehog or newer
- Android SDK 33+
- JDK 17

### 🛠️ How to Build

```bash
git clone https://github.com/your-username/MealSuggestionApp.git
cd MealSuggestionApp
```

Then open the project in **Android Studio**, let Gradle sync, and click **Run ▶️**.

---

## 🧪 GitHub Actions (CI)

This project uses **GitHub Actions** to automatically build and test the app on every push. You can find the workflow in:

```bash
.github/workflows/android.yml
```

To trigger it manually:

```bash
git add .
git commit -m "Trigger CI"
git push
```

---

## ✏️ How It Works

The app maps user input like:

- `"morning"` → ["Eggs", "Pancakes", "Oatmeal"]
- `"mid-morning"` → ["Fruit", "Granola Bar", "Yogurt"]
- `"afternoon"` → ["Sandwich", "Salad", "Soup"]
- `"mid-afternoon"` → ["Nuts", "Smoothie", "Crackers"]
- `"dinner"` → ["Pasta", "Grilled Chicken", "Stir-fried Veggies"]

The app randomly chooses one of the appropriate meals.

---

## 🧑‍💻 Contributing

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add cool feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
