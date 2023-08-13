# Hosted link https://ayush19bansal.github.io/Flexbox-Photo/
![image](https://github.com/Ayush19bansal/Flexbox-Photo/assets/118842033/19bd1f0c-b4b2-4549-bce4-545ab6b67b9e)
![image](https://github.com/Ayush19bansal/Flexbox-Photo/assets/118842033/56726853-e173-47c3-8179-18c713b2783c)

# HTML
![image](https://github.com/Ayush19bansal/Flexbox-Photo/assets/118842033/27ab336c-1607-4825-9708-f62b3c60be2a)
This code snippet is an example of an HTML structure for creating a simple photo gallery using CSS Flexbox. Here's a breakdown of what each part does:

1. `header class="header": This is a header section containing an `h1` element with the title "css flexbox photo gallery".

2. `div class="gallery"`: This is the main container for the photo gallery. It uses the CSS Flexbox layout to organize the images.

3. `img src="..."`: These are a series of `img` elements, each with a `src` attribute pointing to an image URL. These images will be displayed in the photo gallery.

The Flexbox layout is used to arrange the images in a row with the default justification of center. The images themselves are being displayed using their original aspect ratios and are centered both vertically and horizontally within their containers.

By using Flexbox, you can create a responsive and visually appealing photo gallery layout without relying heavily on complex CSS or JavaScript. The code provided sets up the basic structure, but you can further customize it with additional CSS styles to enhance the appearance and behavior of the gallery.

# CSS
![image](https://github.com/Ayush19bansal/Flexbox-Photo/assets/118842033/ee3bb2d2-5e5f-4acb-a179-86d8703df695)
![image](https://github.com/Ayush19bansal/Flexbox-Photo/assets/118842033/3f0211ee-1594-43a4-a468-fcab704f7b81)
This CSS code snippet defines the styling for a photo gallery using Flexbox layout. Here's a brief explanation of each part:

1. `* { box-sizing: border-box; }`: Applies the border-box box-sizing model to all elements, ensuring that padding and borders are included in the total width and height of elements.

2. `body { ... }`: Sets basic styles for the body, including removing default margin, setting font-family to sans-serif, and providing a light background color.

3. `.header { ... }`: Styles the header section with text alignment at the center, uppercase text transformation, padding, background color, color, and a colored border at the bottom.

4. `.gallery { ... }`: Styles the main gallery container. It uses Flexbox with properties like `display`, `flex-direction`, `flex-wrap`, `justify-content`, `align-items`, `gap`, and sets a maximum width, margin, and padding. This creates a responsive, centered, and evenly spaced layout for the gallery.

5. `.gallery img { ... }`: Styles the individual images within the gallery. Images have a width of 100% and a maximum width of 350px. The height is fixed at 300px with `object-fit: cover` to maintain aspect ratio and fill the container. Additionally, images have rounded corners for a smoother appearance.

6. `.gallery::after { ... }`: Adds an empty element after the last image in the gallery, creating space in a two-column layout. The width of the empty element is set to match the width of the images.

This CSS code provides a visually appealing photo gallery layout that adapts well to different screen sizes while maintaining consistent spacing and appearance for the images.
