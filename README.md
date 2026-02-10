# Cryptanalysis Toolkit

A comprehensive web-based collection of cryptographic analysis tools for CTF competitions and cipher breaking.

## 🛠️ Tools Included

1. **Cipher Tool** - Multi-cipher decoder (Caesar, Base64, Morse, Mirror, Letter-to-Number)
2. **Vigenère Cracker** - Dictionary and brute force attacks on Vigenère cipher
3. **Beaufort Cracker** - Dictionary attack on Beaufort cipher
4. **Hexahue Decoder** - Decode Hexahue color cipher
5. **IoC Analyzer** - Index of Coincidence analysis for key length detection
6. **Word Finder** - Find valid words from letter combinations using bracket notation
7. **Keyboard Heatmap** - Visualize letter frequency on different keyboard layouts
8. **Punycode Decoder** - Decode internationalized domain names

## 🚀 Deployment to GitHub Pages

### Method 1: Quick Deploy

1. Create a new repository on GitHub
2. Upload `index.html` and `script.js` to the repository
3. Go to Settings → Pages
4. Under "Source", select "main" branch
5. Click Save
6. Your site will be available at `https://yourusername.github.io/repository-name/`

### Method 2: Using Git

```bash
# Initialize git repository
git init

# Add files
git add index.html script.js README.md

# Commit
git commit -m "Initial commit - Cryptanalysis Toolkit"

# Add remote (replace with your repository URL)
git remote add origin https://github.com/yourusername/repository-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## 📋 Usage

All tools are client-side JavaScript, requiring no backend. Simply open the page and:

1. Select the tool you want to use from the navigation bar
2. Enter your input data
3. Click the corresponding button to process
4. View results in the output section

## 🔧 Features

- **No installation required** - runs entirely in the browser
- **No backend needed** - all processing is client-side
- **Privacy-focused** - your data never leaves your browser
- **Mobile-friendly** - responsive design works on all devices
- **Dictionary attacks** - uses online English word lists for cracking
- **Progress indicators** - visual feedback for long-running operations

## 📝 Notes

- The Vigenère and Beaufort crackers require an internet connection to load the dictionary (only once)
- Brute force attacks with key length > 4 may take significant time
- All tools process data locally in your browser for privacy

## 🤝 Contributing

Feel free to fork this repository and add more tools or improve existing ones!

## 📜 License

Free to use for educational and CTF purposes.

## 🎯 Perfect For

- CTF competitions
- Cryptography learning
- Cipher breaking practice
- Security research
- Educational purposes
