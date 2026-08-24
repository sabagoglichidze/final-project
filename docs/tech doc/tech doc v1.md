# Technical and Content Specification Document: MaxAre

## Project Overview

"MaxAre" is an informational platform designed to provide tourists with essential travel details, destination highlights, and planning resources. The primary goal of this early-stage version is to establish a clean, static, and user-friendly experience using pure frontend technologies, focusing heavily on content layout, tourist guidance, and interactive inquiry handling.

---

## Site Architecture / Sitemap

* **Home (Landing Page):** Welcome introduction, featured highlights, and quick access to key sections.
* **Destinations / Highlights:** Detailed guides and information on locations, attractions, and local experiences tailored for tourists.
* **About Us:** Information regarding the mission, background, and purpose of the MaxAre platform.
* **Contact / Inquiry:** Dedicated page allowing visitors to submit travel-related questions, booking queries, or feedback.

---

## Content & UI Layout per Page

### 1. Home Page

* **Hero Section:** High-impact visual banner with a welcoming tagline, brand title ("MaxAre"), and a primary call-to-action button leading to destinations.
* **Introduction / Value Proposition:** Short summary highlighting why MaxAre is the ideal guide for tourists.
* **Featured Cards Grid:** Quick-preview cards showcasing top tourist destinations or categories.
* **Footer:** Quick links, social media handles, and copyright information.

### 2. Destinations Page

* **Filter Bar:** Simple UI controls to sort tourist spots by category or region.
* **Destination Info Cards:** Grid layout featuring location images, titles, brief descriptions, and key tourist facts (e.g., best time to visit, highlights).

### 3. About Page

* **Mission Statement:** Explaining the vision behind MaxAre and how it helps travelers.
* **Information Blocks:** Text and imagery detailing the core values and features offered to visitors.

### 4. Contact / Inquiry Page

* **Introductory Text:** Encouraging tourists to reach out for assistance or custom inquiries.
* **Inquiry Form Section:** Clean, centered container housing the interactive contact form.

---

## Form Specification (Contact / Inquiry Form)

### Required Input Fields

* **Name:** Text input (`<input type="text">`) for the user's full name.
* **Email:** Email input (`<input type="email">`) for the user's contact address.
* **Destination of Interest:** Dropdown selection (`<select>`) listing available tourist regions or a "General Inquiry" option.
* **Travel Dates:** Date picker inputs (`<input type="date">`) for expected arrival and departure.
* **Message / Comments:** Textarea (`<textarea>`) for specific tourist questions or notes.

### Frontend JavaScript Validation Rules

* **Required Field Check:** Ensure all mandatory fields (Name, Email, Destination) are not left empty upon submission.
* **Email Format Validation:** Verify that the email input contains a valid structure (includes an "@" symbol and a domain extension like `.com` or `.ge`).
* **Date Logic Validation:** Confirm that the departure date is chronologically later than the arrival date.
* **DOM Feedback Handling:** Prevent default form submission behavior, clear validation error messages dynamically if inputs are corrected, and display an on-screen success notification (e.g., *"Thank you for your inquiry, [Name]! We will get back to you shortly."*).

---

## Technical Guidelines

* **HTML5 Semantics:** Utilize meaningful tags (e.g., `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) to ensure structural clarity and accessibility.
* **CSS Organization:**
* Employ modern layout tools including CSS Flexbox and CSS Grid for responsive design.
* Define global design tokens and color variables (such as brand colors, font sizes, and spacing) in the `:root` scope.


* **JavaScript DOM Manipulation:**
* Keep script execution modular inside `main.js`.
* Use clean event listeners (`addEventListener`) for form validation handling, UI toggles, and dynamic DOM element creation without external dependencies.