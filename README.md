```markdown
# Amazon Review Sorter 🚀🛒

🎯 **Amazon Review Sorter** is a lightweight Chrome extension that automatically adds `&sort=review-count-rank` to your Amazon search URLs, ensuring you always see the most reviewed products first! 

## ⚡ Features
- 📊 **Auto-Sort**: Automatically sorts search results by review count!
- 🚀 **Fast and Efficient**: Built with Manifest V3 for a seamless experience.
- 🔒 **Persistent**: Ensures the sort parameter stays, even if other extensions interfere.
- 💡 **Easy to Use**: Just install and shop—no extra clicks required!

## 🔧 Installation
1. **Clone this repo**:
   ```bash
   git clone https://github.com/yourusername/amazon-review-sorter.git
   ```
2. **Load in Chrome**:
   - Go to `chrome://extensions/`
   - Enable **Developer Mode**
   - Click **Load unpacked** and select the `amazon-review-sorter` folder

## 🎮 How It Works
- Waits for the Amazon page to **fully load** before checking the URL.
- Appends `&sort=review-count-rank` if it’s missing.
- Uses `location.replace()` to **reload the page once** without affecting browser history.

## 🤝 Contributing
- Found a bug? 🐛 Have an idea? 💡 Fork the repo, make changes, and submit a pull request!
- All contributions are welcome!

## 📄 License
This project is licensed under the **MIT License**. Feel free to use, modify, and share!

---

🎉 Happy shopping! May your Amazon searches always be perfectly sorted! 🛍️
```
