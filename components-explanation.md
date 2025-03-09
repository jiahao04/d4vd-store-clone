# Bootstrap Components Explanation

This document explains the Bootstrap components used in the webpage.

## General Setup

*   **Bootstrap CSS and JS:** The following lines import Bootstrap's CSS for styling and JavaScript for interactive components.
    ```
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
          integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
            crossorigin="anonymous"></script>
    ```
*   **Bootstrap Icons:** This line imports Bootstrap Icons for using icons in the webpage.
    ```
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    ```

## Layout

*   **`container`**: Provides a responsive fixed-width container.
*   **`row`**: Creates a horizontal row using Bootstrap's grid system.
*   **`col-2`, `col-3`, `col-4`, `col-1`, `col`**: These classes define the size of the columns within the row, using Bootstrap's grid system. For example, `col-2` makes the logo take up 2 columns.
*   **`d-flex`**: Enables flexbox layout.
*   **`align-items-center`**: Vertically aligns items to the center within the flex container.
*   **`justify-content-around`**: Distributes space evenly between and around items in the flex container.
*   **`justify-content-end`**: Aligns items to the end of the flex container.
*   **`flex-grow-1`**:  Makes the element grow to fill the available space in a flex container.

## Content

*   **`img-fluid`**: Makes the image responsive, scaling it to fit its container.
*   **`fs-5`**: Sets the font size to a larger size (size 5 in Bootstrap's font size scale).

## Components

*   **`dropdown`**: This class is the base class for creating Bootstrap dropdown menus.
*   **`dropdown-toggle`**:  Indicates that the button toggles a dropdown menu.
*   **`dropdown-menu`**: The container for the dropdown menu items.
*   **`dropdown-item`**: Styles each item within the dropdown menu.
*   **`collapse`**: This class is used to create a collapsible element. It is used in conjunction with JavaScript to toggle the visibility of the element.
*   **`offcanvas`**: Creates an off-canvas panel that can be toggled from the side of the screen.
*   **`offcanvas-end`**: Positions the off-canvas panel to appear from the right side of the screen.
*   **`offcanvas-header`**: Styles the header of the off-canvas panel.
*   **`offcanvas-body`**: Styles the body of the off-canvas panel.
*   **`modal`**:  A class that designates an element as a modal.
*   **`fade`**:  This class adds a fade effect when the modal is shown and hidden.
*   **`modal-dialog`**: A class that styles the modal's dialog box.
*   **`modal-dialog-centered`**: A class that vertically centers the modal in the viewport.
*   **`modal-dialog-scrollable`**:  Makes the modal body scrollable if the content is too long.
*   **`modal-lg`**:  A class that sets the modal to a larger size.
*   **`modal-content`**: A class that styles the modal's content area.
*   **`modal-header`**: A class that styles the modal's header.
*   **`modal-title`**: A class that styles the modal's title.
*   **`modal-body`**: A class that styles the modal's body.
*   **`badge`**: Used to highlight an item’s status or category.

## Utilities

*   **`text-danger`**: Sets the text color to a shade of red (Bootstrap's danger color).
*   **`text-white`**: Sets the text color to white.
*   **`text-bg-dark`**: Sets the text color to white and the background color to dark gray on the badge.
*   **`text-bg-danger`**: Sets the text color to white and the background color to red on the badge.
*   **`bg-dark`**: Sets the background color to dark gray.
*   **`border-0`**: Removes the border from the button.
*   **`link-secondary`**: Styles the link with the secondary color from Bootstrap's theme (often a muted color).
*   **`link-underline`**: Provides a default underline for links.
*   **`link-underline-opacity-0`**: Removes the underline from the link.
*   **`rounded-pill`**: Makes the badge have rounded ends.
*   **`mx-1`**: Adds horizontal margin with a size of 1 (Bootstrap's spacing scale).
*   **`ms-2`**: Adds margin to the start (left in LTR, right in RTL) with a size of 2 (Bootstrap's spacing scale).
*   **`me-5`**: Adds margin to the end (right in LTR, left in RTL) with a size of 5 (Bootstrap's spacing scale).
*   **`my-5`**: Adds margin on the top and bottom (y-axis) with a size of 5 (Bootstrap's spacing scale).
*   **`mb-5`**: Adds margin to the bottom with a size of 5.
*   **`z-n1`**: This class sets the `z-index` of the element to a negative value (-1).  This is used to place the video behind other content on the page.  Bootstrap's z-index scale uses values like `z-0`, `z-1`, `z-2`, `z-3`, `z-4`, and `z-5`.
*   **`position-fixed`**:  This class sets the element's positioning to fixed, meaning it's positioned relative to the viewport and doesn't move when the page is scrolled.
*   **`w-100`**: Sets the width of the element to 100% of its parent container.
*   **`min-vh-100`**: Sets the minimum height of the element to 100% of the viewport height.
*   **`object-fit-cover`**:  Specifies how the content of a replaced element (like `<img>` or `<video>`) should be resized to fit its container. `cover` makes the content fill the container, potentially cropping it to maintain the aspect ratio.
*   **`overflow-x-hidden`**: This class is used to prevent horizontal scrolling on the body.

## Customize

*   **`btn-none`**: A custom class to remove button styling, likely defined in a separate CSS file or inline styles.

## Icons

*   **`bi bi-facebook`, `bi bi-twitter-x`, `bi bi-instagram`, `bi bi-youtube`, `bi bi-apple`, `bi bi-spotify`, `bi bi-tiktok`**: These classes are used to display social media icons using Bootstrap Icons.
*   **`bi bi-search`**: Represents the search icon from Bootstrap Icons.
*   **`bi bi-person`**: Represents the person icon from Bootstrap Icons, often used for user profiles or login links.
*   **`bi bi-cart3`**: Represents the shopping cart icon from Bootstrap Icons.
*   **`bi bi-exclamation-circle`**: Represents the exclamation circle icon, often used for warnings or important messages.

