# 🎯 Futures Trade Checklist

This is a dynamic and interactive Futures Trade Checklist designed to help traders systematically evaluate their trade setups, manage risk, and document their observations. It's a single-page HTML application that runs entirely in your browser, leveraging local storage for persistence and offering robust features for customization, layout management, and sharing.

**Website**: [https://jmsykes83.github.io/Futures-Trading-Checklist/](https://jmsykes83.github.io/Futures-Trading-Checklist/)

---

## 🧾 Futures Trade Checklist UI

> *Note: UI screenshots below might not reflect all the latest button additions. Please refer to the live application for the most up-to-date interface.*

---

## 📊 Risk Management Panel  
## ✍️ Trade Setup Notes Panel

---

## ✨ Features

### Comprehensive Customization

- **Criteria Management**: Add, edit, and delete your own trade criteria.
- **Category Management**: Create, edit, delete, and reorder (drag & drop) custom categories for your criteria.
- **Strategy Management**: Define and manage custom trading strategies, each with its own default risk/reward profiles, stop-loss, and target descriptions.

### Layout Management

- **Save & Load Layouts**: Save multiple complete checklist configurations (including custom strategies, criteria, category order, checked items, and P&L settings) and load them as needed.
- **Delete Layouts**: Remove saved layouts.
- **Default Layout**: Easily revert to the original default checklist layout.
- **Layout Sharing**: Export your entire current layout (settings, criteria, strategies, category order) as a compact code and import layouts shared by others.

### Dynamic Evaluation

- **Strategy Filtering**: Filter the checklist items to display only those relevant to a specific trading strategy.
- **Real-time Risk/Reward Calculation**: Automatically calculates and displays a sum of risk and reward values based on your checked criteria.
- **Dominant Strategy Identification**: Identifies the most prevalent strategy based on your checked criteria and suggests corresponding stop-loss and target approaches.

### User Experience

- **Draggable Category Organization**: Easily reorder categories by dragging and dropping them.
- **Trade Notes Section**: A dedicated area to document your trade setup.
- **Dark/Light Mode**: Toggle between dark and light themes.

### Reset Options

- **Reset Checks**: Clear only the checked criteria, leaving notes and P&L inputs intact.
- **Load Default Layout**: Completely reset the checklist to its original state (this will overwrite customizations).

### Persistence & Sharing

- **Local Storage**: All your settings, custom criteria, strategies, layouts, and category order are saved in your browser's local storage.
- **Shareable Layout Codes**: Use LZ-String compression to generate compact codes for sharing entire layouts.

---

## 🚀 How to Use

1. **Open the Application**: Open `index.html` in your browser.

2. **Check Criteria**: Go through the checklist and mark what applies to your trade.

3. **Observe Results**:  
   - Watch the setup score and Risk:Reward ratio update live.

4. **Manage Strategies**:  
   - Click ⚙️ **Manage Strategies** to add/edit/delete strategies.

5. **Manage Categories**:  
   - Click 🗄️ **Manage Categories** to add/edit/delete categories.  
   - Drag and drop category blocks directly in the main checklist view to reorder them.

6. **Manage Criteria**:  
   - Click the ➕ next to category headings to add new criteria to that category.  
   - Use ✏️ (edit) and ❌ (delete) buttons on each criteria item.

7. **Manage Layouts**:  
   - Click 🗂️ **Manage Layouts**.  
   - **Saved Layouts Tab**: Save your current setup with a name, load previously saved layouts, or delete them.  
   - **Share/Import Tab**: Generate a code to export your current layout or paste a code to import a layout from someone else.  
   - **Default Layout Tab**: Revert the entire checklist (strategies, criteria, categories, order) to its original state.

8. **Filter by Strategy**:  
   - Use the filter buttons under the "Filter Strategies" dropdown.

9. **Add Notes**:  
   - Use the "Trade Setup Notes" area.

10. **P&L Calculation**:  
    - Input your trade size, tick value, futures tick size, and entry price in the **Risk Management** section to see potential P&L.

11. **Toggle Dark Mode**:  
    - Click ☀️ Light Mode / 🌙 Dark Mode.

12. **Reset Checks**:  
    - Click 🔄 **Reset Checks** to uncheck all criteria items without affecting notes or P&L inputs.

---

## 🔗 Layout Sharing & Import/Export

The **Manage Layouts** modal provides a comprehensive way to share and backup your entire checklist configuration.

### Export Current Layout

1. Click 🗂️ **Manage Layouts**.
2. Navigate to the **Share/Import** tab.
3. Ensure the **Export** sub-tab is active.
4. Click **Generate Share Code**.
   - This code includes your custom strategies, custom criteria, category definitions, category order, and currently checked items.
5. Click **Copy Code** to copy the generated code.
6. Share this code with others or save it as a backup.

### Import Layout

1. Click 🗂️ **Manage Layouts**.
2. Navigate to the **Share/Import** tab.
3. Switch to the **Import** sub-tab.
4. Paste a previously generated share code into the textarea.
5. Click **Import Settings**.

> ⚠️ Importing a layout will overwrite your current custom strategies, custom criteria, category order, and checked items.  
> Your trade notes and P&L input fields will remain unchanged.  
> Saved layouts in your browser are distinct and will not be overwritten unless you explicitly save over an existing layout name.

---

## 💻 Technologies Used

- **HTML5** – Structure  
- **CSS3** – Styling and responsive design  
- **JavaScript (ES6+)** – Logic, calculations, local storage, drag & drop  
- **LZ-String** – Compression of shareable layout codes

---

## 📦 Deployment (GitHub Pages)

1. **Create a Repository**  
   - Go to GitHub and create a public repository (e.g., `futures-trade-checklist`).

2. **Upload Files**  
   - Upload your `index.html` (and any CSS/JS files if applicable) to the root.

3. **Enable GitHub Pages**  
   - Go to **Settings > Pages**  
   - Select **Deploy from a branch**  
   - Choose `main` (or `master`) and root (`/`)  
   - Click **Save**

4. **Access Your Checklist**  
   - GitHub will give you a URL like:  
     `https://yourusername.github.io/your-repository-name/`  
   - (Deployment may take a few minutes.)

---

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