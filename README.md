# Mpuza UI — Job & Network Dashboard

A responsive web UI layout for a job/network platform dashboard built using **HTML** and **CSS** with Bootstrap Icons.  
This project demonstrates a multi-panel layout with sidebar profile, company info cards, job posts, and a right detail panel.

---

## Features

- Fixed top navigation bar
- Left sidebar with:
  - User profile card
  - Stats menu
  - Company page info block
  - Professional group section
- Main content area with:
  - Post box
  - Job mini cards
  - Job listing cards
- Right panel with:
  - Favorited jobs box
  - Detailed job description card
- Company banner + logo card style (Airtel-style block)
- Bootstrap icons integration
- Card-based modern UI

---

## Project Structure

```
project-folder/
│
├── index.html
├── style.css
├── README.md
│
├── profile.jpg
├── airtel.png
├── background.png
├── twapela.png
├── mpuza.png
```

---

## How to Run

1. Download or clone the project
2. Place all images in the same folder as the HTML file
3. Open `index.html` in your browser

No server required — runs locally.

---

## Technologies Used

- HTML5
- TailwindCSS
- Bootstrap Icons (CDN)

Tailwind used from:

```
https://cdn.tailwindcss.com
```


Bootstrap Icons CDN used:

```
https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css
```

---

## Layout Sections

### Topbar
- Logo
- Navigation icons with badges
- Search bar
- Profile mini + action button

### Sidebar
- Profile cover + avatar
- Profile stats
- Company info card with banner + logo
- Group section

### Content Area
- Post creation box
- Job mini cards row
- Job cards with actions

### Right Panel
- Favorite jobs info
- Detailed job card with countdown and description

---

## Customization Tips

You can easily customize:

- Colors → edit CSS variables or color values
- Images → replace image files
- Icons → change Bootstrap icon classes
- Cards → duplicate `.job-card` or `.mini-card`

---

## Future Improvements (Optional)

- Make fully responsive with media queries
- Add JavaScript interactions
- Connect to backend/job API
- Add dark mode
- Add real search functionality

---

## Output Screenshot

![Output](screen.png)

## Author

Created as a UI practice project for dashboard and job platform layout.

---

## License

Free to use for learning and personal projects.
