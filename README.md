# Fake News Detection Tool with Source Verification

This project is a **Fake News Detection Tool** designed to identify potential misinformation in news articles. It analyzes news content by performing three main checks:

1. **Source Credibility**: It verifies whether the source of the news article is reliable by comparing the input URL with a list of trusted sources.

2.**Source Reliability**:Source reliability is a critical factor in determining the trustworthiness of information. By assessing source reliability, we can make informed decisions about what information to believe and share.

3. **Language Pattern Analysis**: The tool checks for common misleading words or phrases often associated with fake news, such as "exclusive", "shocking", or "unbelievable".


### **Features:**
- Simple interface for entering news text and source URL.
- Basic source verification using trusted news outlets like BBC, CNN, and Reuters.
- Language pattern analysis to identify sensationalist or misleading language.
- Provides a result indicating whether the news is likely to be true, false, or unverifiable.

### **How It Works:**
- Input News Article's source URL.
- The tool checks the source for credibility and analyzes the language for potential signs of misinformation.
- The result will display whether the news is credible, potentially fake, or requires further verification.

### **Technologies Used:**
- HTML: Structure and form for user input.
- CSS: Basic styling for the tool’s interface.
- JavaScript: Logic for processing input, analyzing language patterns, and verifying source credibility.

### **How to Use:**
1. Clone the repository.
2. Open `index.html` in your browser.
3. Enter a news article text and a source URL in the provided fields.
4. Click the "Check News" button to analyze the content.

### **Future Improvements:**
- Integrating real-time source verification with external APIs.
- Implementing advanced language processing with NLP techniques.
- Adding a more extensive database of trusted news sources for better accuracy.

Feel free to contribute by submitting issues or pull requests
