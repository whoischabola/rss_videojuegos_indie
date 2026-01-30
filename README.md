# DOMO — Journal for Digital & Physical Life


This repository contains our **Content Syndication Project** for the Markup Languages course. We have developed a minimalist digital magazine focused on Indie Game culture, fully integrated with a functional RSS news feed.

## 📋 Project Datasheet

Below are the details regarding the project requirements:

| Requirement | Details |
| :--- | :--- |
| **Topic** | Digital Magazine about **Indie Video Games** & Virtual Culture. |
| **Syndication Format** | **RSS 2.0** (Validated). |
| **Hosting Platform** | **GitHub Pages**. |
| **Aggregator Used** | **Feedly**. |
| **Web URL** | **https://whoischabola.github.io/isabelruizcallejon/** |
| **Feed URL** | **https://feedly.com/i/subscription/feed%2Fhttps%3A%2F%2Fwhoischabola.github.io%2Fisabelruizcallejon%2Ffeed.rss/** |

---

## 🎮 Theme & Design Concepts

**DOMO** is a fictional publication exploring the boundaries between virtual and physical life. We moved away from the traditional neon "gamer" aesthetic, opting instead for a clean, brutalist, and editorial design.

* **Content:** We cover indie releases (*Stardew Valley*), alternative distribution platforms (*Itch.io*), and artistic analysis (*Blasphemous*).
* **Visual Style:** The site uses a monochromatic color palette (`#f8f7f2`) with classic typography (Georgia & Helvetica). Images are presented in black and white, only revealing their true colors upon interaction (hover), simulating a print newspaper coming to digital life.

## 🛠️ Project Structure

The project consists of the following core files:

* `index.html`: The Landing Page containing the semantic structure of the magazine, including the header, navigation, and article sections.
* `styles.css`: The stylesheet featuring responsive design (CSS Grid & Flexbox) and custom hover effects.
* `feed.xml`: The XML file structured under the RSS 2.0 standard.

### Validation
The RSS file structure has been validated using [XMLValidation.com](https://www.xmlvalidation.com/), ensuring all `<channel>`, `<item>`, and `<guid>` elements comply with the standard.
<img width="1286" height="726" alt="image" src="https://github.com/user-attachments/assets/5a97e73a-61f5-48c0-915f-ab3146583148" />


---

## 🔀 Workflow (Git & Branches)

To organize our collaboration, we set up a **Branching Strategy** to distribute the workload across different files. We worked with 5 branches:

1. **`main`**: The final production branch.
2. **`DEV`**: Intended as the integration branch.
3. **`HTML`**: Branch dedicated to structure and content.
4. **`CSS`**: Branch dedicated to design and styling.
5. **`RSS`**: Branch dedicated to the XML feed creation.

We aimed to merge our individual work into the `DEV` branch to consolidate changes before the final release. Finally, we performed a merge into `main` to prepare the files for deployment on GitHub Pages.

---

## 👥 Authors

Project created by:
* **Daniel Pavón Téllez**
* **Isabel Ruiz Callejón**

---
*DOMO MAGAZINE © 2026 — TOKYO / SEVILLE*
