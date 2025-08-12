Image Gallery

A simple, clean PHP-based image gallery web application that displays a collection of images with titles and descriptions. The project demonstrates server-side rendering of images, clean separation of concerns using includes, and responsive, modern CSS styling.
Technologies

 PHP (server-side rendering)
 HTML5, CSS3
 CSS Flexbox for responsive gallery layout
 Custom CSS styling with simple.css (reset and base styles) and custom.css (gallery-specific styles)
 Basic URL query handling with $_GET

Features

Gallery Overview Page (gallery.php)
Displays all images with their titles in a responsive grid layout. Each image links to its individual details page.

Image Detail Page (image.php)
Shows the selected image, its title, and a formatted description. Includes navigation back to the gallery.

Reusable Components
Uses PHP includes for header (header.php) and footer (footer.php) to maintain consistent structure and style.

Image Data Management
Image titles and descriptions are managed in separate PHP includes (images.inc.php) for easy maintenance.

Responsive Layout
Uses CSS Flexbox to adapt the gallery to different screen sizes. Hover effects on images provide interactivity.

Safe Output Handling
Applies escaping functions (e()) to prevent XSS and safely output user data.
