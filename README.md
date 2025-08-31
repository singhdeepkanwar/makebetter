## 🚀 Getting Started

To run this project on your local machine, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/makebetter-website.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd makebetter-website
    ```
3.  **Open the website:**
    Simply open the `index.html` file in your web browser.

    For the best experience and to avoid any potential CORS issues with local files, it is recommended to use a live server. If you are using Visual Studio Code, you can use the **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** extension.

## 🎨 Customization

This project was built to be easily customizable.

*   **Colors and Fonts:**
    All primary colors, fonts, and layout variables are located at the top of the `style.css` file within the `:root` selector. You can change the entire website's aesthetic by modifying these values.
    ```css
    :root {
        --bg-dark: #0A0A14;
        --primary-glow: #3182CE;
        --secondary-glow: #8A31CE;
        --text-primary: #F7FAFC;
        /* ...and so on */
    }
    ```
*   **Particle Animation:**
    The configuration for the `particles.js` animation can be found at the bottom of the `script.js` file. You can adjust the number of particles, their speed, color, and interactivity by changing the values in the `particlesJS` configuration object.

*   **Content:**
    All text and image content can be changed directly within the `index.html` file. Image placeholders are from [Unsplash](https://unsplash.com/).

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.