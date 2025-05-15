# google-inspired-search-ui
A simple Google-inspired search interface built using HTML, CSS, and SVG icons.
# Google Search Clone

This project is a clone of Google's search interfaces built using HTML and CSS. It demonstrates frontend development fundamentals, including form handling, layout styling, and linking multiple pages. The site replicates the behavior of Google Search, Google Image Search, and Google Advanced Search.

## 📁 Project Structure

- `index.html` – Main Google Search page.
- `image_search.html` – Google Image Search page.
- `advanced_search.html` – Google Advanced Search page.
- `styles.css` – Custom CSS styling for all pages.

## ✅ Features

### 1. Multi-Page Navigation
- Three separate pages: **Google Search**, **Image Search**, and **Advanced Search**.
- Navigation links in the upper-right corner allow switching between pages.

### 2. Google Search (index.html)
- Users can type a search query and either:
  - Click **"Google Search"** to go to standard Google results.
  - Click **"I’m Feeling Lucky"** to go directly to the first result.
- Search bar is centered with rounded corners, styled to match Google aesthetics.
- Search buttons are also centered and positioned beneath the input field.

### 3. Image Search (image_search.html)
- Users can enter a query and click a button to open Google Image search results.

### 4. Advanced Search (advanced_search.html)
- Four search options:
  - All these words
  - This exact word or phrase
  - Any of these words
  - None of these words
- Text inputs are vertically stacked and left-aligned.
- The **"Advanced Search"** button is styled blue with white text and executes a Google advanced search using the provided fields.

## 💡 Technical Notes

- Forms use the `GET` method to send queries to actual Google URLs.
- Query parameters are based on inspecting Google's own URLs and form field names.
- CSS mimics the clean and minimal style of Google's UI.

## 📸 Demo



## 🔗 Usage

Clone the repository and open `index.html` in your browser to get started.

```bash
git clone <your-repo-url>
cd google-search-clone
open index.html
