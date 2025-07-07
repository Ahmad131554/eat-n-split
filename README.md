# eat-n-split

**Eat-n-Split** is a React-based bill splitting application that helps friends track shared expenses and settle balances. It provides a simple interface to manage who owes whom after dining out or shared activities.

---

## 🧭 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [License](#license)

---

## 📌 About

**Eat-n-Split** allows users to:

- Add friends to a shared expense tracker
- Record bills and specify who paid
- Automatically calculate balances between friends
- Visualize who owes whom with color-coded indicators

---

## 🌟 Features

- **Friend Management**: Add and manage friends with avatars
- **Balance Tracking**: Automatically tracks debts between friends
- **Bill Splitting**: Split bills with customizable payment options
- **Visual Indicators**: Color-coded balances (green/red)
- **Responsive UI**: Clean interface for easy expense management

---

## ⚙️ Tech Stack

- **Frontend**: React (Hooks, State Management)
- **Styling**: CSS (No external libraries)
- **Avatar Generation**: Pravatar.cc service
- **Unique IDs**: Crypto Web API for UUID generation

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

````bash
git clone https://github.com/Ahmad131554/eat-n-split.git
cd eat-n-split
npm install

### Running the Development Server

```bash
npm run start
````

---

## 🖥️ Usage

### Add Friends

1. Click the **"Add Friend"** button
2. Enter your friend's name
3. (Optional) Add an avatar URL (defaults to random avatar from [pravatar.cc](https://pravatar.cc/))

### Split Bills

1. **Select a friend** from your friends list
2. Fill in the bill details:
   - Total bill amount
   - Your expense (what you paid)
   - Who is paying (you or your friend)
3. The app **automatically calculates** and updates balances

### View Balances

- 🟢 **Green**: Your friend owes you money
- 🔴 **Red**: You owe your friend money
- ⚪ **No color**: You're all settled up

---

## 📄 License

This project is licensed under the [MIT LICENSE](./LICENSE).
