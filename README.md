# Random-GIF-Generator
This React application allows users to fetch and search for random GIFs using the Giphy API. The project uses a custom hook useGif for handling API requests and Axios for HTTP calls. The design is clean and responsive, styled with Tailwind CSS.


✨ **Features**
1. **Fetch Random GIFs:** Display a random GIF at the click of a button.
2. **Search for GIFs:** Enter a keyword to search for specific GIFs.
3. **Custom Hook:** The useGif hook handles API requests for both random and searched GIFs.
4. **Responsive Design:** Built with Tailwind CSS for a modern and adaptable layout.
5. **Axios for API Calls:** Axios is used for handling all API requests.

**🛠️ Technologies Used**
1. **React:** JavaScript library for building user interfaces.
2. **Tailwind CSS:** Utility-first CSS framework for designing responsive UIs.
3. **Axios:** Promise-based HTTP client for handling API requests.
4. **Giphy API:** Fetch random and searched GIFs.

**⚙️ How It Works**
This application connects to the Giphy API to fetch both random and user-searched GIFs. The API calls are managed via the useGif hook, which handles both the random and search functionality, managing the state and errors as well.

**📚 How to Use**
1. **Random GIF:** Upon launching, a random GIF will be displayed.
2. **Search for GIFs:** Use the search bar to enter a keyword and fetch GIFs related to that term.
3. **Refresh GIF:** Click "Get Random GIF" to display a new random GIF.
