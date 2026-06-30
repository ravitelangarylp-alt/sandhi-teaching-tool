# Sanskrit Sandhi Learning Platform (Team Trayee)

An interactive, web-based educational tool designed to teach various **Sanskrit Sandhi rules** through visual aids, practice exercises, and games. 

This platform presents a comprehensive collection of **Ac-Sandhi** (vowel sandhis) and **Hal-Sandhi** (consonant sandhis) in a beautifully designed, responsive interface with multilingual support (Kannada, English, and Sanskrit).

## 📚 Included Sandhi Chapters

The platform covers the following major sandhis:

1.  **Yan Sandhi** (`यण् सन्धिः`)
2.  **Ayadi Sandhi** (`अयादि सन्धिः`)
3.  **Guna Sandhi** (`गुण सन्धिः`)
4.  **Vriddhi Sandhi** (`वृद्धि सन्धिः`)
5.  **Savarna Dirgha Sandhi** (`सवर्णदीर्घ सन्धिः`)
6.  **Purvarupa Sandhi** (`पूर्वरूप सन्धिः`)
7.  **Pararupa Sandhi** (`पररूप सन्धिः`)
8.  **Varttikas** (`वार्त्तिकानि`)
9.  **Comprehensive Sandhi Exam** (`अच् सन्धि परीक्षा`)
10. **Jashatva Sandhi** (`जश्त्व सन्धिः` - Hal Sandhi)

## ✨ Key Features

- **Beautiful & Responsive Design**: Built with a warm, academic color palette, smooth CSS animations, and responsive layouts that work on both desktop and mobile devices.
- **Sutra Explanation**: Each lesson starts with the original Paninian Sutra (`सूत्रम्`) and a clear, simple explanation of the rule in Kannada.
- **Transformation Maps**: Visual diagrams show exactly how letters change during a sandhi (e.g., `अ + इ = ए`).
- **Interactive Games**: A Drag-and-Drop game is included in most chapters to let students reinforce their learning by placing letters in the correct "Purva", "Para", and "Adesha" slots. (The Jashatva chapter features a unique Jhal-to-Jash matching game).
- **Master Sandhi Chart**: A complete "Ac-Sandhi Master Chart" is available. It highlights the specific rule being taught in each chapter while keeping other rules visible for reference.
- **Multilingual Interface**: A toggle button at the top allows users to switch between **ಕನ್ನಡ (Kannada)**, **English**, and **संस्कृतम् (Sanskrit)** for all instructions and explanations.
- **Practice Exercises**: Each chapter contains carefully curated Abhyasa (practice) exercises with blanks (`______`) for students to fill in.
- **Detailed Varttikas Page**: A dedicated section explaining the four major Varttikas (exceptions/annotations) related to the `एङि पररूपम्` sutra.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure for each page.
- **CSS3**: 
  - Custom properties (CSS Variables) for easy theming.
  - CSS Grid and Flexbox for responsive layouts.
  - Keyframe animations (`@keyframes`) for page transitions.
- **Vanilla JavaScript**:
  - Client-side logic for Drag-and-Drop games.
  - Simple client-side Internationalization (`i18n`) for language switching.
  - DOM manipulation for dynamic interactions.

## 💻 How to Use

1.  **Download** or clone the repository to your local machine.
2.  Because this project uses pure HTML, CSS, and JavaScript, **no web server or special build process is required**.
3.  Simply open any `.html` file (e.g., `yan.html`, `guna.html`, `exam.html`) directly in your web browser (Chrome, Firefox, Safari, or Edge) to view the page.

## 📂 Project File Structure

| File Name | Description |
| :--- | :--- |
| `yan.html` | Lesson on **Yan Sandhi** (इ/उ/ऋ/ऌ → य्/व्/र्/ल्). |
| `ayadi.html` | Lesson on **Ayadi Sandhi** (ए/ओ/ऐ/औ → अय्/अव्/आय्/आव्). |
| `guna.html` | Lesson on **Guna Sandhi** (अ/आ + इ/उ/ऋ/ऌ → ए/ओ/अर्/अल्). |
| `vriddhi.html` | Lesson on **Vriddhi Sandhi** (अ/आ + ए/ओ/ऐ/औ → ऐ/औ). |
| `savarna.html` | Lesson on **Savarna Dirgha Sandhi** (अ+अ→आ, इ+इ→ई, etc.). |
| `purvarupa.html` | Lesson on **Purvarupa Sandhi** (पदान्त ए/ओ + अ → एऽ/ओऽ). |
| `pararupa.html` | Lesson on **Pararupa Sandhi** (Upasarga + ए/ओ → ए/ओ). |
| `varttika.html` | Dedicated page explaining important **Varttikas** for Pararupa Sandhi. |
| `exam.html` | **Comprehensive Exam** containing 80 sandhi questions and a 16-question sloka exercise. |
| `jashatva.html` | Lesson on **Hal-Sandhi: Jashatva** (झल् letters converting to 3rd letters / जश्). |
| *(Any CSS / JS embedded)* | All styling and logic are contained within the respective HTML files. |

## 🖋️ Credits & Fonts

- **Sanskrit Text**: Rendered using the **[Inknut Antiqua](https://fonts.google.com/specimen/Inknut+Antiqua)** font (Sans-serif serif styling).
- **Kannada Text**: Rendered using the **[Laila](https://fonts.google.com/specimen/Laila)** font.
- *Both fonts are served via Google Fonts.*
- Content, code, and design by **Team Trayee**.

---

*Happy Learning! 🌟 यशः स्यात्।*
