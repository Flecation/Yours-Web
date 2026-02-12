# YoursWeb — Template-Based Website Builder

## Project Overview
**YoursWeb** is a **template-based website builder system** created using **HTML, CSS, JavaScript, PHP, and MySQL**.

Users can:
- Register and log in
- Create a website (draft)
- Choose a template
- Edit website sections (Hero/About/Contact, etc.)
- Preview and save changes
- Publish the website and share a public link

---

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Backend:** PHP
- **Database:** MySQL
- **DB Tool:** MySQL Workbench
- **Server:** PHP Built-in Server (`php -S ...`) or Apache (XAMPP)

---

## Main Features
### User Features
- Register / Login / Logout (PHP Sessions)
- Dashboard: list created websites
- Create new website (Title + Unique Slug)
- Template selection
- Website editor:
  - Edit sections (Hero/About/Contact)
  - Save data to MySQL (JSON-based content storage)
- Publish / Unpublish website
- Public website page accessible by slug

### Optional (Extra Marks)
- Image upload (logo/hero)
- Theme customization (colors/fonts)
- View counter (analytics)
- Projects/Services list (add/remove items)
- Admin panel to manage sites

---

## Project Flow
1. User opens the system
2. Register or Login
3. Dashboard (list websites)
4. Create new site (title + slug)
5. Choose template
6. Edit content in editor
7. Save as draft or publish
8. Public visitors can view published site by slug

---

## Folder Structure (Suggested)
