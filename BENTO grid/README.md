
# 🍱 Bento Grid Feature Showcase

A modern, responsive dashboard layout built with **CSS Grid** and **Semantic HTML**. This project is a clone of a high-end fintech UI, designed to showcase product features using the popular "Bento Box" design pattern.

## 🚀 Overview

The goal of this project was to master complex grid structures by moving away from standard 12-column layouts and exploring **7-column / 5-row coordinate systems**. It features a "Corporate Memphis" illustration style and a soft pastel aesthetic.

### Key Learnings:

* **Semantic HTML5:** Used `<section>` and `<article>` tags instead of generic `div`s to improve SEO and accessibility.
* **CSS Grid Areas:** Implemented `grid-template-areas` for precise control over asymmetrical tile spans.
* **Responsive Design:** Learned how to manage viewport heights (`vh`) and prevent content overflow in small grid units.
* **Version Control:** Managed the development lifecycle using **Git** (staging, committing, and pushing to GitHub).

---

## 🛠️ Tech Stack

* **HTML5** (Semantic structure)
* **CSS3** (Grid, Flexbox, Custom Properties)
* **Git/GitHub** (Version control)

---

## 🧩 How it's Built

### The Grid Logic

The layout uses a 7-column grid to achieve the specific offsets seen in the "Credit Card Strategy" and "Compare & Apply" boxes.

```css
grid-template-areas: 
    "box1 box1 box1 box2 box2 box2 box2"
    "box1 box1 box1 box2 box2 box2 box2"
    "box1 box1 box1 box3 box3 box4 box4"
    "box5 box5 box5 box5 box6 box6 box6"
    "box5 box5 box5 box5 box6 box6 box6";

```

### Internal Alignment

Each card uses **Flexbox** to keep the headings at the top and the illustrations centered or anchored to the bottom, ensuring the UI stays clean even if the text length changes.

---



