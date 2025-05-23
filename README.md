# 🎯 Futures Trade Checklist

This is a dynamic and interactive **Futures Trade Checklist** designed to help traders systematically evaluate their trade setups, manage risk, and document their observations. It's a single-page HTML application that runs entirely in your browser, leveraging local storage for persistence and offering a unique feature to share custom settings via a generated code. 

Website: https://splendorous-griffin-851bcc.netlify.app/

---

## ✨ Features

- **Customizable Criteria**: Add, edit, and delete your own trade criteria within different categories.
- **Dynamic Strategy Management**: Define and manage custom trading strategies, each with its own default risk/reward profiles, stop-loss, and target descriptions.
- **Strategy Filtering**: Filter the checklist items to display only those relevant to a specific trading strategy (e.g., Reversal, Momentum, Scalping).
- **Real-time Risk/Reward Calculation**: Automatically calculates and displays a sum of risk and reward values based on your checked criteria, providing an instant overview of your setup's potential.
- **Dominant Strategy Identification**: Identifies the most prevalent strategy based on your checked criteria and suggests corresponding stop-loss and target approaches.
- **Trade Notes Section**: A dedicated area to document your trade setup, key levels, and personal observations.
- **Dark/Light Mode**: Toggle between a comfortable dark mode and a bright light mode.
- **Shareable Settings**: Generate a compact, shareable code that encapsulates your custom strategies, custom criteria, and even the currently checked items.
- **Local Persistence**: All your settings are saved directly in your browser's local storage.

---

## 🚀 How to Use

1. **Open the Application**: Open `index.html` in your browser.
2. **Check Criteria**: Go through the checklist and mark what applies to your trade.
3. **Observe Results**: Watch the setup score and Risk:Reward ratio update live.
4. **Manage Strategies**: Click `⚙️ Manage Strategies` to add/edit/delete strategies.
5. **Add Custom Criteria**: Click the `➕` next to category headings.
6. **Edit/Delete Criteria**: Use `✏️` and `x` buttons on each item.
7. **Filter by Strategy**: Use the filter buttons above the checklist.
8. **Add Notes**: Use the "Trade Setup Notes" area.
9. **Toggle Dark Mode**: Click `☀️ Light Mode` / `🌙 Dark Mode`.
10. **Reset Checklist**: Click `🔄 Reset Checklist` to start fresh.

---

## 🔗 Sharing Settings

### Export Settings:

- Click `🔗 Share/Import Settings`.
- Go to the **Export Settings** tab.
- Click **Generate Share Code**.
- Click **Copy Code** to copy and share.

### Import Settings:

- Click `🔗 Share/Import Settings`.
- Go to the **Import Settings** tab.
- Paste a share code and click **Import Settings**.

⚠️ *Importing will overwrite existing strategies, criteria, and checked items. Notes are preserved.*

---

## 💻 Technologies Used

- **HTML5** – Structure
- **CSS3** – Styling and responsive design
- **JavaScript (ES6+)** – Logic, calculations, local storage
- **LZ-String** – Compression of shareable settings

---

## 📦 Deployment (GitHub Pages)

1. **Create a Repository**  
   Go to GitHub and create a public repository (e.g., `futures-trade-checklist`).

2. **Upload Files**  
   Upload your `index.html` (and any CSS/JS files if applicable) to the root.

3. **Enable GitHub Pages**  
   - Go to **Settings > Pages**  
   - Select **Deploy from a branch**
   - Choose `main` (or `master`) and root (`/`)
   - Click **Save**

4. **Access Your Checklist**  
   GitHub will give you a URL like:  
   `https://yourusername.github.io/your-repository-name/`  
   *(Deployment may take a few minutes.)*

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
