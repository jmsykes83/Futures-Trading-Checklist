# 🎯 Futures Trade Checklist

This is a dynamic and interactive Futures Trade Checklist designed to help traders systematically evaluate their trade setups, manage risk, and document their observations. It's a single-page HTML application that runs entirely in your browser, leveraging local storage for persistence and offering robust features for customization, layout management, and sharing.

🔗 **Website**: [https://jmsykes83.github.io/Futures-Trading-Checklist/](https://jmsykes83.github.io/Futures-Trading-Checklist/)

---

## 🧾 Futures Trade Checklist UI

> **Note**: UI screenshots might not reflect the latest features. Refer to the [live application](https://jmsykes83.github.io/Futures-Trading-Checklist/) for the current interface.

### 📊 Risk Management Panel  
### ✍️ Trade Setup Notes Panel  

---

## ✨ Features

### 🔧 Comprehensive Customization

- **Criteria Management**: Add, edit, and delete trade criteria.
- **Category Management**: Create, reorder (drag & drop), edit, and delete custom categories.
- **Strategy Management**: Define and manage strategies with default R/R, stop-loss, and targets.

### 🧩 Layout Management

- Save & load entire checklist configurations
- Delete layouts
- Revert to the default layout
- Share layouts via compact codes

### ⚙️ Dynamic Evaluation

- **Strategy Filtering**
- **Live Risk/Reward Calculation**
- **Dominant Strategy Identification**
- **Preparation Bonus**: Completing "Morning Checklist" and "Pre-Market Research" gives a 10% reward bonus.

### 👤 User Experience

- **Draggable Categories**
- **Trade Notes Section**
- **Dark/Light Mode Toggle**
- **Separate Daily Prep Checklist**

### 🔄 Reset Options

- **Reset Checks**: Clears checked criteria only
- **Clear All Daily Prep Checks**
- **Load Default Layout**

### 💾 Persistence & Sharing

- All custom data saved to **Local Storage**
- Layouts shareable via compressed codes

---

## 🚀 How to Use

1. **Open the Application**: Open `index.html` in your browser.
2. **Navigate Pages**: Switch between "Trade Setup" and "Daily Prep".
3. **Check Criteria**: Mark what applies to your trade.
4. **Observe Results**: See live setup score and R:R ratio.
5. **Complete Daily Prep**: Get 10% bonus on trade reward.

### Manage Strategies  
- Click ⚙️ **Manage Strategies** to customize.

### Manage Categories  
- Click 🗄️ **Manage Categories**  
- Reorder with drag-and-drop

### Manage Criteria  
- ➕ to add, ✏️ to edit, ❌ to delete

### Manage Layouts  
- 🗂️ **Manage Layouts**
- Save/load/delete layouts
- Export/import via compact code
- Revert to default

### Filter by Strategy  
- Use the dropdown filters

### Add Notes  
- Use the **Trade Setup Notes** area

### P&L Calculation  
- Enter trade size, tick size/value, and entry price

### Dark Mode  
- Toggle ☀️ / 🌙

### Reset  
- 🔄 **Reset Checks** (Trade Setup only)  
- 🔄 **Clear All Docs Checks** (Daily Prep only)

---

## 🔗 Layout Sharing & Import/Export

### Export Layout

1. 🗂️ **Manage Layouts** > Share/Import > **Export**
2. Click **Generate Share Code**
3. Click **Copy Code**

### Import Layout

1. 🗂️ **Manage Layouts** > Share/Import > **Import**
2. Paste code > Click **Import Settings**

> ⚠️ Importing will overwrite your current custom strategies, criteria, and category order. Trade notes and P&L are preserved.

---

## 💻 Technologies Used

- **HTML5** – Structure  
- **CSS3** – Styling and responsive design  
- **JavaScript (ES6+)** – Logic, local storage, drag & drop  
- **LZ-String** – Compression for shareable codes

---

## 📦 Deployment (GitHub Pages)

1. **Create Repository**: e.g., `futures-trade-checklist`
2. **Upload Files**: `index.html`, CSS/JS files
3. **Enable GitHub Pages**:
   - Settings > Pages
   - Deploy from branch: `main` and root (`/`)
4. **Access Checklist**:

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo  
2. Create a new branch:  
   `git checkout -b feature/your-feature-name`  
3. Make your changes  
4. Commit:  
   `git commit -m 'Add new feature'`  
5. Push:  
   `git push origin feature/your-feature-name`  
6. Open a Pull Request

---

## 📄 License

This project is open-source and available under the **Apache-2.0 license**.