# Crest Academy — Premier Educational & Coaching Institute Website

Welcome to the official web repository for **Crest Academy**, a modern, responsive, and feature-rich institutional website designed for coaching institutes, secondary & higher-secondary academies, and competitive exam training centers.

---

## 📌 Table of Contents
- [About Crest Academy](#-about-crest-academy)
- [Key Features](#-key-features)
- [Website Pages & Architecture](#-website-pages--architecture)
- [Official Contact & Alternative Details](#-official-contact--alternative-details)
- [Project Directory Structure](#-project-directory-structure)
- [Quick Start & Local Setup](#-quick-start--local-setup)
- [Customization & Configuration](#-customization--configuration)
- [Tech Stack & Credits](#-tech-stack--credits)
- [License & Copyright](#-license--copyright)

---

## 🎓 About Crest Academy

**Crest Academy** is dedicated to nurturing academic excellence, conceptual clarity, and intellectual confidence in students across secondary and higher secondary levels. Combining rigorous classroom coaching with technology-aided digital tools (recorded lectures, digital assessments, diagnostic unit reports, and e-books), Crest Academy prepares learners for top marks in school board examinations (CBSE / ICSE / State) as well as competitive entrance and language tests (IELTS).

---

## ✨ Key Features

- **Responsive & Mobile-First**: Built with Bootstrap and custom responsive CSS to deliver a seamless experience on smartphones, tablets, laptops, and desktops.
- **Custom Vector Branding**: Features the official Crest Academy vector shield logo (`image/crest-logo.svg`) styled with gold and crimson institutional colors.
- **Interactive Course Showcases**: Multi-item carousel highlighting programs from middle school foundation to senior secondary science/commerce and language mastery.
- **Faculty Directory & Filtering**: Interactive faculty grid powered by Isotope.js to sort mentors by subject domains (Science, Commerce, Humanities, Languages).
- **Concept Video Gallery**: Embedded video player and multimedia modules for topic walkthroughs and digital lessons.
- **Modal Campus Gallery**: Photo grid with modal zoom functionality for annual awards, laboratory sessions, and campus events.
- **Student Zone & Downloads**: Direct links to download course syllabi, mark distribution charts, and sample question papers in PDF format.
- **Accordion FAQs**: Interactive frequently asked questions addressing parents' and students' queries on batch timings, doubt clinics, and curriculum comparison.
- **Inquiry & Feedback Forms**: Integrated modal and page-level registration and inquiry forms with instant validation.
- **Complete Primary & Alternative Contact Information**: Clear emergency helpline, primary campus phone, alternative inquiry line, admissions email, and responsive Google Map coordinates.

---

## 🌐 Website Pages & Architecture

| File | Page Name | Description |
| :--- | :--- | :--- |
| [`index.html`](index.html) | **Home** | Landing page featuring hero animation slider, scholarship assessment highlights, course carousels, concept video showcase, admission banners, faculty highlights, and campus map. |
| [`AboutCoachingC.html`](AboutCoachingC.html) | **About Us** | Institutional history, mission statement, pedagogical methodology, 48-hour exam helpline overview, and free demo booking form. |
| [`our_values.html`](our_values.html) | **Our Values** | Core tenets of Crest Academy: Courage & Curiosity, Responsibility, Student Empowerment, Continuous Innovation, and Student-Centric Pedagogy. |
| [`our_team.html`](our_team.html) | **Faculty Team** | Profiles and academic credentials of department deans and senior subject mentors. |
| [`course_secoundary.html`](course_secoundary.html) | **Secondary Courses** | Performance Booster curriculum for Classes VI–X covering Maths & Science, e-books, online assignments, and downloadable syllabi. |
| [`higher_secoundary.html`](higher_secoundary.html) | **Higher Secondary** | Rigorous foundational and board exam coaching for Classes XI–XII across Science and Commerce streams. |
| [`othercourse.html`](othercourse.html) | **Other Courses** | Comprehensive training for IELTS (Academic & General) with modules for Listening, Reading, Writing, and Speaking clinics. |
| [`gallery.html`](gallery.html) | **Campus Gallery** | Interactive image showcase highlighting annual awards, science laboratories, workshops, and student felicitations. |
| [`FAQ.html`](FAQ.html) | **FAQs** | Practical answers to questions about weekend batches, study material distribution, home tuition comparison, and doubt clearing. |
| [`contact_us.html`](contact_us.html) | **Contact Us** | Detailed campus address, primary & alternative telephone numbers, primary & alternative emails, working hours, responsive Google Map, social links, and message form. |

---

## 📞 Official Contact & Alternative Details

For inquiries, enrollment, demo classes, and student support, Crest Academy maintains both primary channels and dedicated alternative lines:

| Detail | Primary Channel | Alternative / Helpline Channel |
| :--- | :--- | :--- |
| **Phone / Mobile** | `+91 98765 43210` | `+91 98765 43211` |
| **Toll-Free Helpline** | `1800-123-CREST` (1800-123-2737) | `+1 (800) 555-0199` *(24/7 Student Support)* |
| **Email Address** | `info@crestacademy.com` | `admissions@crestacademy.com` / `helpline@crestacademy.com` |
| **Campus Address** | **Crest Academy Main Campus**<br>Park Centra Tower, 4th Floor, Sector-30<br>Gurugram, Haryana – 122001, India | **Interactive Map**: [Open Google Maps Location](https://maps.google.com/?q=Park+Centra+Sector+30+Gurugram) |
| **Working Hours** | **Monday – Saturday**: 8:00 AM – 8:00 PM | **Sunday**: 9:00 AM – 2:00 PM *(Helpline Active 24/7)* |

---

## 📂 Project Directory Structure

```text
Crest-Academy/
│
├── css/
│   ├── animate.css               # CSS animations
│   ├── bootstrap.css             # Bootstrap 3 framework (development)
│   ├── bootstrap.min.css         # Bootstrap 3 framework (minified)
│   ├── font-awesome.min.css      # Font Awesome 4.7 icon font
│   └── style.css                 # Master custom stylesheet & Crest Academy styling
│
├── fonts/                        # Font Awesome & custom typography webfonts
│   ├── batmfa__.ttf
│   ├── fontawesome-webfont.woff2
│   └── ...
│
├── image/                        # Images, banners, and vector graphics
│   ├── crest-logo.svg            # Official Crest Academy vector shield logo
│   ├── computer.jpg              # Course thumbnail
│   ├── tea 1.jpg, tea 2.jpg...   # Faculty headshots
│   └── ...
│
├── js/
│   ├── bootstrap.js              # Bootstrap JavaScript
│   ├── bootstrap.min.js          # Bootstrap JavaScript (minified)
│   ├── jquery-3.1.1.min.js       # jQuery 3.1.1 library
│   ├── isotope.pkgd.min.js       # Isotope layout & filtering engine
│   ├── isotape.function.js       # Isotope initialization script
│   └── main.js                   # Navigation & carousel custom logic
│
├── pdf/                          # Downloadable course resources & syllabi
│   └── ssc-equivalent-exam...pdf # Sample curriculum & marks distribution
│
├── index.html                    # Homepage
├── AboutCoachingC.html           # About Crest Academy page
├── our_values.html               # Institutional Values & Culture page
├── our_team.html                 # Faculty & Deans directory page
├── course_secoundary.html        # Secondary school course overview
├── higher_secoundary.html        # Higher secondary science & commerce overview
├── othercourse.html              # IELTS & language coaching overview
├── gallery.html                  # Photo & awards gallery with modal view
├── FAQ.html                      # Student & Parent FAQ page
├── contact_us.html               # Contact details, alternative channels & map
└── README.md                     # Comprehensive project documentation
```

---

## 🚀 Quick Start & Local Setup

Because Crest Academy is a static website built with pure HTML5, CSS3, and JavaScript, no complex build tools, node package installations, or database servers are required.

### Option 1: Direct File Preview
Simply double-click `index.html` or right-click and open it in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, Opera).

### Option 2: Using VS Code Live Server
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey) if not already installed.
3. Right-click on `index.html` and click **"Open with Live Server"**.
4. The site will launch at `http://127.0.0.1:5500/index.html` with hot reloading enabled.

### Option 3: Using Python Built-in HTTP Server
Run the following command from the project root:
```bash
# Python 3
python -m http.server 8000
```
Then navigate to: `http://localhost:8000`

---

## 🎨 Customization & Configuration

### Updating Contact Information
Contact details are centrally referenced in two key locations:
1. **Footer section (`<div class="f-003">`)** in each of the 10 HTML files.
2. **Main contact page (`contact_us.html`)** inside the `<div class="cA1-378left">` block.

To update phone numbers or emails, search for `+91 98765 43210` or `info@crestacademy.com` across the `.html` files.

### Customizing Brand Logo & Colors
- **Vector Logo**: Edit `image/crest-logo.svg` in any text or vector editor (such as Figma or Adobe Illustrator) to modify text, colors, or shield shapes.
- **Color Palette**: The primary brand color palette is defined in `css/style.css`:
  - **Crest Red / Crimson**: `#C12026` / `#EE1C25`
  - **Accent Gold**: `#FFD700`
  - **Deep Charcoal / Background**: `#1a1a1a` / `#ffffff`

---

## 🛠 Tech Stack & Credits

- **Markup & Styling**: HTML5, CSS3
- **CSS Framework**: [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/)
- **Scripting & Interactivity**: [jQuery 3.1.1](https://jquery.com/)
- **Filter & Sorting Library**: [Isotope by Metafizzy](https://isotope.metafizzy.co/)
- **Iconography**: [Font Awesome 4.7.0](https://fontawesome.com/v4/)
- **Typography**: [Google Fonts](https://fonts.google.com/) — *Nunito* and *IM Fell Great Primer*
- **Animation**: [Animate.css](https://daneden.github.io/animate.css/)

---

## 📄 License & Copyright

&copy; 2026 **Crest Academy**. All Rights Reserved.  
All content, branding, course structures, and website assets are protected under copyright law.
