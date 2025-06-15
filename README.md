# Blog Website

A simple, responsive blog website built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Clean and modern UI with smooth animations
- Dark mode toggle
- Mobile-friendly navigation
- Newsletter subscription form
- Scroll-to-top button
- Sample blog posts with images

## File Structure

- `index.html` - The main HTML file containing the structure of the blog
- `styles.css` - CSS file with all the styling for the blog
- `script.js` - JavaScript file with interactive functionality

## How to Use

1. Clone or download this repository
2. Open `index.html` in your web browser to view the blog

## Customization

### Adding New Blog Posts

To add a new blog post, copy and paste the following HTML structure inside the `<section class="blog-posts">` element in `index.html`:

```html
<article class="post">
    <div class="post-image">
        <img src="YOUR_IMAGE_URL" alt="Blog Post Image">
    </div>
    <div class="post-content">
        <h3>Your Blog Post Title</h3>
        <div class="post-meta">
            <span><i class="fas fa-calendar"></i> Date</span>
            <span><i class="fas fa-user"></i> Author Name</span>
        </div>
        <p>Your blog post excerpt or summary goes here...</p>
        <a href="#" class="read-more">Read More</a>
    </div>
</article>
```

### Changing Colors

The main color scheme can be modified by changing the color values in the `styles.css` file. The primary color is `#0066cc`.

### Adding Pages

To create additional pages (like About or Contact):

1. Create new HTML files (e.g., `about.html`, `contact.html`)
2. Copy the header and footer from `index.html`
3. Add your content in between
4. Update the navigation links in all pages to point to the new files

## Browser Compatibility

This blog website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- Add a search functionality
- Implement comments section
- Create individual blog post pages
- Add pagination for blog posts
- Implement a contact form

