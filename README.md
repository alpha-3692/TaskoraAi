# Taskora AI

A modern task manager website built with **only HTML and CSS**. It has 12 linked pages, a responsive layout, and smooth CSS animations. It is a front-end project, so it has no JavaScript and no backend.

## Features

- Public website: home, features, pricing, about, and contact pages
- Login and signup pages
- App area with a sidebar: dashboard, tasks, planner, calendar, and settings
- Task checkboxes that strike through the text, using only CSS
- Responsive layout for desktop, tablet, and phone
- Animations: hero entrance, floating preview card, scroll reveal, hover effects, and counting numbers
- Respects the `prefers-reduced-motion` system setting

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, custom properties, keyframe animations, media queries)
- Google Fonts: Sora and DM Sans

## Project Structure

```
Taskora-AI/
│
├── index.html
├── features.html
├── about.html
├── pricing.html
├── contact.html
├── login.html
├── signup.html
├── dashboard.html
├── tasks.html
├── planner.html
├── calendar.html
├── settings.html
├── README.md
│
├── css/
│   ├── style.css          # shared styles, navbar, hero, cards, forms
│   ├── auth.css           # login and signup pages
│   ├── dashboard.css      # app layout and sidebar pages
│   └── animations.css     # all animations (optional)

```

## Getting Started

1. Download or clone this folder.
2. Open `index.html` in any modern browser.

No installation or build step is needed. An internet connection is only used to load the Google Fonts. Without it, the pages fall back to system fonts.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero with app preview, features, how it works |
| Features | `features.html` | Feature cards |
| Pricing | `pricing.html` | Free, Pro, and Team plans |
| About | `about.html` | About the product |
| Contact | `contact.html` | Contact form |
| Log in | `login.html` | Login form |
| Sign up | `signup.html` | Registration form |
| Dashboard | `dashboard.html` | Stats and today's focus list |
| Tasks | `tasks.html` | Add-task bar and task list |
| Planner | `planner.html` | Morning, afternoon, and evening blocks |
| Calendar | `calendar.html` | Monthly calendar grid |
| Settings | `settings.html` | Profile and notification options |

## Limitations

HTML and CSS cannot store data or check passwords, so:

- Login and signup forms go straight to the dashboard without checking anything.
- "Add task", "Save changes", and "Send message" do not save or send anything.
- The tasks, planner, and calendar contain sample data.

## License

This project is for learning and personal use. Add a license of your choice, such as MIT, before sharing it publicly.

## Author

Built by **Mohit**.
