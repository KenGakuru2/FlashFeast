# ⚡🍔 FlashFeast – Speedy Food Delivery App

FlashFeast is a modern, fast, and clean food delivery app built using React Native, styled with NativeWind, managed with Redux Toolkit, and powered by Sanity CMS for dynamic content updates.
From tasty bites to full-course meals, FlashFeast gets your food delivered at lightning speed.

---

## ✨ Features

- 🍽️ Browse nearby restaurants and explore full menus
- 🛵 Real-time order status and delivery tracking
- 🌓 Light/Dark mode support
- 🧠 Global state management with Redux Toolkit
- 🧾 Dynamic content handled via Sanity CMS
- 💅 Tailwind-style utility classes with NativeWind

---

## 🛠️ Tech Stack

| Tech            | Description                                 |
|-----------------|---------------------------------------------|
| React Native    | Cross-platform mobile development           |
| NativeWind      | Tailwind-style styling in React Native      |
| Redux Toolkit   | Centralized and scalable state management   |
| Sanity CMS      | Real-time content management                |
| Expo            | Development workflow and build system       |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/KenGakuru2/flashfeast.git
cd flashfeast
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Run the App

```bash
npx expo start
```

---

## 🌐 Sanity CMS Setup

FlashFeast uses [Sanity.io](https://www.sanity.io/) for managing:

- Restaurants
- Dishes
- Featured categories

### To Set Up Sanity:

1. Create a new project on [Sanity.io](https://www.sanity.io/).
2. Add datasets and schemas for:
   - `restaurant`
   - `dish`
   - `featured`
3. In your React Native project, create a `.env` file and include:

```env
SANITY_PROJECT_ID=your_project_id
SANITY_DATASET=production
SANITY_API_VERSION=2023-01-01
```

---

## 🧠 State Management with Redux

All app-wide state is managed using Redux Toolkit.

- Slices are located in `/redux/slices`
- Example usage:

```tsx
import { useDispatch } from 'react-redux';
import { setRestaurant } from '../redux/slices/restaurantSlice';

const dispatch = useDispatch();
dispatch(setRestaurant(restaurant));
```

---

## 💅 Styling with NativeWind

FlashFeast uses **NativeWind** to style components just like Tailwind CSS:

```tsx
<Text className="text-xl font-bold text-green-700">Welcome to FlashFeast</Text>
```

No inline styles or complex stylesheet files — just fast, clean, and readable UI code.

---

## 📁 Project Structure

```
flashfeast/
├── assets/
├── components/
├── redux/
│   └── slices/
├── screens/
├── sanity/
├── App.js
└── ...
```

---

## 🤝 Contributing

Contributions are always welcome! Feel free to open issues or submit pull requests to improve the app.

---

## 📃 License

Licensed under the [MIT License](./LICENSE).

---

## 💬 Contact

Made with 💚 by [Ken](https://github.com/yourusername)

> “Shop Fast. Eat Fresh. FlashFeast.”

---
```

---


