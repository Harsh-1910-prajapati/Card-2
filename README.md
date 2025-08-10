### **Animated Flip Card** 🤩

This project showcases a dynamic card component that features a 3D flip animation on hover. The card is designed with a sleek, futuristic aesthetic, including a glowing, animated border.

#### Features
* **3D Flip Animation:** 🔄 When a user hovers over the card, a subtle 3D rotation reveals the content on the back of the card, while the initial SVG icon scales to zero.
* **Animated Gradient Border:** 🌈 The card is framed with an animated, multi-colored gradient border that moves continuously, giving it a vibrant, glowing effect.
* **Interactive SVG Icon:** 🚀 The front of the card displays a simple SVG icon that disappears with a smooth scale-down transition as the content is revealed.
* **Customizable Content:** ✍️ The hidden content includes a bold title and a descriptive paragraph, both styled with soft colors and shadows to complement the dark background.
* **Responsive Styling:** 📱 The component uses a `box-sizing: border-box` to ensure consistent padding and dimensions, making it easy to integrate into different layouts.

#### How to Use
To implement this card, simply copy the provided HTML and CSS code into a single file (e.g., `index.html`) and open it in a web browser. The animation will be triggered automatically when you hover your mouse over the card.

#### Customization
* **Dimensions:** You can adjust the `width` and `height` properties of the `.card` class to change the overall size of the component.
* **Colors:** The background and text colors can be customized by changing the hex codes in the CSS. For the animated border, modify the colors in the `linear-gradient` within the `.card__border` rule.
* **Icon:** Replace the SVG code with any other SVG you prefer.
* **Text:** The title and description can be easily edited by changing the text inside the `<p class="card__title">` and `<p class="card__description">` tags.
