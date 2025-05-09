
# Web Development Assignment - Part 1: Research Task

## 1. CSS Units: px, em, rem

- **px**: A constant unit used to measure the size or dimensions of elements in CSS. It is not affected by the default font size or user settings.  
  **Example**:  
  ```css
  font-size: 20px;
  ```

- **em**: A relative unit that depends on the font size of the parent element.  
  **Example**:  
  If the parent’s font size is 16px, then:  
  ```css
  font-size: 2em; /* equals 32px */
  ```

- **rem**: Similar to em, but it depends on the root element’s font size (usually the `<html>` tag).  
  **Example**:  
  If the root font size is 16px:  
  ```css
  font-size: 2rem; /* equals 32px */
  ```

**Example CSS Code**:
```css
p {
    font-size: 16px;
}

h1 {
    font-size: 2em;
}

h2 {
    font-size: 2rem;
}
```

---

## 2. HTML Audio and Video Tags

- **`<audio>`**: Used to embed audio files in a webpage. The `controls` attribute allows users to play/pause the audio.  
  **Example**:
  ```html
  <audio controls>
      <source src="audiofile.mp3" type="audio/mp3">
  </audio>
  ```

- **`<video>`**: Used to embed video files in a webpage. It also supports controls.  
  **Example**:
  ```html
  <video controls>
      <source src="videofile.mp4" type="video/mp4">
  </video>
  ```

---

## 3. What is Web Accessibility and How Can We Improve It?

**Definition**:  
Web accessibility means designing websites so that they can be used by everyone, including people with disabilities.

**Ways to improve accessibility**:
- Use **alternative text for images**:
  ```html
  <img src="image.jpg" alt="Description of the image">
  ```

- Ensure **keyboard navigation** (e.g., Tab key)

- Improve **contrast**:  
  Use color combinations that are readable by visually impaired users.

- Use **semantic HTML tags**:  
  Tags like `<header>`, `<footer>`, `<main>`, `<article>` help structure the content for screen readers.
