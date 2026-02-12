# Chat Summary — YoursWeb

## Final Project Name
YoursWeb — Template-Based Website Builder

## Goal
Users can build a simple website from a template:
Register/Login → Create site → Edit sections → Publish → Share public link

## Must-have Modules
1) Auth (register/login/logout using sessions)
2) Dashboard (list user’s sites)
3) Create Site (title + unique slug)
4) Editor (edit sections and save to DB)
5) Publish/Unpublish
6) Public View (open site by slug)

## MVP Scope (Beginner Friendly)
- 1 template (Portfolio)
- 3 sections: Hero, About, Contact
- Save content in MySQL using JSON (site_content.content_json)
- Public URL: /public/site.php?slug=...

## Database Tables
- users
- sites
- site_content (JSON per section)
- site_assets (optional for images)

## Suggested Folder Structure
config/, auth/, site/, public/, assets/

## How to run (no XAMPP control panel)
php -S localhost:8000
Open http://localhost:8000

## Next Steps (coding order)
1) Database + config/db.php
2) Register/Login/Logout
3) Dashboard + Create Site
4) Editor save/load (Hero/About/Contact)
5) Publish + Public page
6) Add 1 extra feature (theme OR projects OR upload)
