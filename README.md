# Filterable_Gallery
"Filterable Gallery: A visually appealing web app showcasing images in Computer Science, Commerce, and Arts categories. Filter images with ease and enjoy a responsive, user-friendly experience. Perfect for exploring diverse subjects. Built using HTML, CSS, and JavaScript." 

**Filterable Gallery Project Documentation**

**1. Introduction**
The Filterable Gallery is a web application that showcases a collection of images grouped into different categories, such as Computer Science, Commerce, and Arts. The application allows users to filter the images based on their chosen category using a menu of buttons. This documentation provides an overview of the project, its features, and the underlying code implementation.

**2. Project Overview**
The Filterable Gallery project is a simple and elegant web application designed to display a visually appealing collection of images. Users can easily navigate through the images by filtering them based on specific categories. The project utilizes HTML, CSS, and JavaScript to create a responsive and interactive gallery.

**3. Project Components**
The project consists of the following main components:

a. HTML (`index.html`):
- Defines the structure of the web page, including headings, buttons, and image containers.
- Provides the foundation for the Filterable Gallery application.

b. CSS (`style.css`):
- Applies styling to the web page elements, such as fonts, colors, layout, and image appearance.
- Ensures a visually appealing and user-friendly design.

c. JavaScript (`app.js`):
- Implements the filtering functionality for the gallery.
- Handles button clicks and displays the images according to the selected category.

**4. Design and Styling**
The project utilizes a custom Google Font, "Mochiy Pop One," to enhance the visual presentation of the gallery. The font choice creates a professional and modern look for the application. The overall color scheme features shades of blue for headings and buttons, along with a subtle gray background, offering a balanced and soothing design.

**5. Functionality**
The main functionality of the Filterable Gallery includes:

a. Image Filtering:
   - Users can filter the gallery images by clicking on the buttons in the menu.
   - Each button corresponds to a specific category: "All," "Computer Sci," "Commerse," and "Arts."
   - Clicking on a category button will display only the images belonging to that category, hiding the others.

b. Responsive Design:
   - The gallery is designed to adapt to different screen sizes and devices, providing a consistent user experience across platforms.

**6. Implementation**
The JavaScript code (`app.js`) drives the filtering functionality. The code implementation can be summarized as follows:

a. Initialization:
   - The script retrieves all buttons with the class "btn" from the menu and stores them in the `buttons` variable.
   - Similarly, all elements with the class "store-item" are collected and stored in the `storeItems` variable.

b. Event Listeners:
   - Click event listeners are added to each button to trigger the filtering function (`filterItems`) when a button is clicked.

c. Filtering Function:
   - The `filterItems` function handles the filtering logic.
   - It prevents the default behavior of button clicks to avoid page navigation.
   - It gets the `data-filter` attribute value from the clicked button, representing the selected category.

d. Filtering Process:
   - The function loops through all the store items.
   - If an item's category matches the selected filter or if the filter is set to "all," the item is displayed (by adding the "visible" class and removing the "hidden" class).
   - Otherwise, the item is hidden (by adding the "hidden" class and removing the "visible" class).

e. Button Highlighting:
   - The function removes the "active" class from all buttons to reset their appearance.
   - It then adds the "active" class to the clicked button, visually highlighting the active filter.

**7. Conclusion**
The Filterable Gallery project showcases an elegant and user-friendly web application that allows users to explore a collection of images based on different categories. With its responsive design and intuitive functionality, the gallery provides an enjoyable browsing experience for users interested in various subject areas. The project's HTML, CSS, and JavaScript components work harmoniously to create a visually appealing and interactive web gallery, making it a valuable addition to any web development portfolio.
