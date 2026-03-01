# SkillSpark — Web Technologies Assignment 01

        Muhammad Taha Tariq [2502077]

This is my submission for the Web Technologies assignment.


                            Muhammad Taha Tariq [2502077]


 I built a 5-page promotional website for a fictional startup called **SkillSpark** — an online platform where university students can learn tech skills.

---

## Pages Included

- `index.html` — Home page
- `courses.html` — Course listing
- `about.html` — About us page
- `register.html` — Registration form
- `contact.html` — Contact page



## Folder Structure

skillspark/
├── index.html
├── courses.html
├── about.html
├── register.html
├── contact.html
├── css/
│   └── style.css
├── assets/
│   └── images/
└── README.md
```

---

## What I Used

- HTML5
- CSS3 (custom variables, transitions, media queries)
- Bootstrap 5.3
- Bootstrap Icons
- Google Fonts (Nunito)
- Plain JavaScript (no jQuery or extra libraries)

---

## What's on Each Page

**Home Page (index.html)**
- Sticky navbar with dropdown
- Hero section with headline, buttons, and stats
- Course tracks table showing all 4 tracks
- 3 feature cards
- "Why SkillSpark" section with a comparison table
- Testimonials carousel (2 cards per slide, 3 slides)
- Footer with links and newsletter input

**Courses Page (courses.html)**
- 6 course cards with filter buttons
- Each card shows price badge, old price, rating, and Enroll Now button
- Clicking any card opens a Bootstrap modal with course details
- A full course list table at the bottom for quick overview

**About Page (about.html)**
- Mission and vision cards
- Progress bars (scroll-triggered animation)
- Achievements table (year-by-year growth)
- Team grid (4 people)
- Team expertise table
- Company milestone timeline

**Register Page (register.html)**
- 2-column form layout on desktop
- All required fields: first/last name, email, phone, course dropdown, university, password
- Radio buttons for experience level (styled cards)
- Checkboxes for terms, newsletter, mentorship
- File upload for student ID
- Password show/hide button
- Form validation with Bootstrap is-valid/is-invalid classes
- Success message on valid submit

**Contact Page (contact.html)**
- Contact info (email, phone, address, hours)
- Contact form with validation
- Google Maps embed
- FAQ table

---

## Extra Features I Added (Bonus)

- **Dark/Light mode toggle** in the navbar (saved to localStorage so it remembers)
- **Scroll to top button** (appears when you scroll down)
- **Scroll-triggered animations** (cards and sections fade in as you scroll)

---

## Design Notes

I went with a light theme by default using a teal/cyan color scheme. Dark mode is available via the toggle button. The font is Nunito from Google Fonts.

Tables are styled with custom thead colors, striped rows, and hover effects using Bootstrap's table utilities plus some custom CSS.

---

## How to Run

Just open `index.html` in a browser. No build step, no server needed.

If you have VS Code, the Live Server extension makes it easier to work with.

---

## Responsiveness

Tested and working on:
- Mobile (375px)
- Tablet (768px)
- Desktop (1280px+)

Uses Bootstrap's `col-sm-*`, `col-md-*`, and `col-lg-*` grid classes throughout.

---

## Sample Commit Messages

```
initial folder structure and files
added navbar with dropdown menu
built hero section
added course tracks table to homepage
created feature cards section
added comparison table to why choose us section
completed testimonials carousel
added footer and social links
built courses page with 6 cards
added filter buttons for courses
added course details modal
created course list table
built about page - mission and vision
added progress bars
added achievements table
created team grid
added team expertise table
built milestone timeline
created registration form
added form validation
built contact page
added contact form with validation
added google maps embed
added FAQ table to contact page
dark mode toggle working
scroll to top button added
scroll reveal animations added
final cleanup and testing
```

---

**Assignment:** Web Technologies — CLO 01  
**Deadline:** March 2026
