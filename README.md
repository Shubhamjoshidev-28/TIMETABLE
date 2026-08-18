# Timetable

A clean, responsive timetable that converts into landscape view when accessed on mobile devices.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic document structure using table, header, and division tags[cite: 1].
* **CSS3:** Flexbox, table layout algorithms, absolute positioning, and orientation-based media queries[cite: 2].

---

## 🎨 Frontend Class Reference

| Class Name | Description / Usage |
| :--- | :--- |
| `.cec-logo` | Header flex container holding the college logo image and section title[cite: 1, 2]. |
| `.time-table` | Responsive wrapper handling table overflow and touch scrolling[cite: 1, 2]. |
| `.time` | Small caption tag displaying lecture start and end timings in `thead`[cite: 1, 2]. |
| `.period` | Container displaying the period index or break title in `thead`[cite: 1, 2]. |
| `.days` | Table header cell (`th.days`) displaying the day abbreviation (Mo, Tu, etc.)[cite: 1, 2]. |
| `.Faculty` | Faculty name pinned to the bottom-right corner of a cell or batch slot[cite: 1, 2]. |
| `.lab` | Lab room number or lecture hall pinned to the bottom-left corner[cite: 1, 2]. |
| `.section` | Batch identifier label (e.g., `5F1`, `5F2`) pinned to the top-right corner of split slots[cite: 1, 2]. |
| `.sign` | Bottom footer container aligning author credits to the bottom-right edge[cite: 1, 2]. |

---

## 📁 Project Structure

```text
├── assets/
│   └── cec-logo.png        # College / Department logo
├── css/
│   └── time-table.css      # Core stylesheet and responsive rules
├── index.html              # Entry point markup
└── README.md               # Project documentation