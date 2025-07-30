# Smile School Landing Page

This project is a simple HTML-only landing page for **Smile School**, a fictional platform promoting various tutorials and content about smiling. The design and layout are based on a Figma prototype.

## 💡 Purpose

This project is part of a static HTML-only assignment to demonstrate:

- Semantic HTML structure
- Accessibility practices
- W3C compliance
- Content organization using semantic tags (`header`, `main`, `section`, `footer`, etc.)

## 📁 Structure

The HTML page includes the following sections:

- **Header**: Contains navigation links and the logo
- **Hero / Get Schooled Section**: Main call-to-action with a heading, subtexts, and a registration button
- **Learn from the Pros**: Introduces four individuals with profile pictures and achievements
- **Testimonial / Comment Section**: Includes a user quote and image
- **Popular Tutorials**: Four tutorial previews with titles, descriptions, authors, ratings, and durations
- **Free Membership Section**: Highlights four membership perks
- **FAQ Section**: Displays frequently asked questions in two rows, each with two items
- **Footer**: Contains the logo, social media icons, and copyright

## 🌐 Language Declaration

Since the document currently uses placeholder text (`Lorem ipsum`), the `lang` attribute was intentionally set to:

```html
<html lang="zxx">
```

> `zxx` stands for "no linguistic content", which helps prevent W3C validator warnings when real content is not yet available.

This avoids false language-related validation issues during development.

## ✅ W3C Validation

The HTML structure has been written to be **fully W3C-compliant**. Key points include:

- Proper use of semantic tags
- Self-closing void elements (`<meta>`, `<img>`, etc.)
- All `section` elements contain at least one heading tag (`<h1>`, `<h2>`, etc.), as required for accessibility and structure

> ✔ No critical errors are shown in [W3C Markup Validator](https://validator.w3.org/) after applying the above.

## 📷 Assets

All image paths point to a local `img/` folder. To preview the project as intended, ensure you have the appropriate images available in that directory. The images were exported from Figma using the **"Export as PNG"** feature.

## 📝 Notes

- Styling (CSS) is not yet applied. This project focuses on correct HTML structure.
- Buttons and navigation links do not have functional behavior—these are static placeholders.
- All text content is currently mock (Lorem Ipsum) and can be replaced with real content as needed.

## 📄 License

This project is for educational purposes only.

