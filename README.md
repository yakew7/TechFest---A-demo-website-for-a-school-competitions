Yash Kewlani
# School Tech Fest


---

## How to Open
1. Download and unzip the project folder.
2. Open **index.html** in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Either sign up or login through the follwing user credentials
   **username**- yash **password**- kewlani
   **username**- design **password**- summative
4. Navigate through the pages using the buttons and links.

---

## Implemented Features
### 1. Countdown Clock (JavaScript)
- Located on the Home page **(main.html)**.
- Displays time remaining until September 30, 2025.

### 2. Search/Filter Events (JavaScript)
- On the Home page, under Event Details.
- Filters competitions/workshops based on search text (name or category).

### 3. Registration Form with Validation (JavaScript)
- Located at **register.html**.
- Checks:
  - Name and school are filled in
  - Event selection is made
  - Contact number is exactly 10 digits
- Shows clear error messages.
- Redirects to Home with a success message on completion.

### 4. **Simulated Live Updates**  
- Found on **updates.html** with announcements and winners.
- Gallery grid for event images.

### 5. **Responsive Layout & Styling**  
- Uses CSS Flexbox and responsive units for adaptability.
- Consistent color theme and button styles across all pages.

---

## Accessibility Features
- Alt text for all images.
- High contrast color combinations.
- Clear button labels.
- Keyboard navigation supported.

---

## Technologies Used
- HTML5 – Semantic structure
- CSS3 – Layout and styling (flexbox, gradients, shadows)
- JavaScript (Vanilla) – Interactivity and DOM manipulation

---

## Pages Overview
1. **start.html** – Login page (username/password check, mock navigation)
2. **main.html** – Home page (countdown timer, CTAs, search filter)
3. **register.html** – Registration form with validation
4. **updates.html** – Live updates, gallery, winners list
5. **about.html** – About, organisers, sponsors

---

## Testing
### Devices Tested On:
- Laptop (1920×1080)
- Tablet (768×1024)

### Browsers Tested On:
- Google Chrome (latest)
- Microsoft Edge
- Mozilla Firefox

### Test Cases:
| Feature                 | Test Description                               | Result |
|-------------------------|-----------------------------------------------|--------|
| Countdown               | Time decreases every second                   |✅|
| Event search filter     | Filters events dynamically                    |✅|
| Registration validation | Empty/invalid inputs trigger error messages   |✅|
| Page navigation         | All links and buttons navigate correctly      |✅|
| Responsive layout       | Pages adjust for mobile/tablet/desktop        |✅|

---

## Known Issues
- Login page currently does not check real credentials (mock navigation).
- Live updates are static text, not dynamically updating from a server.
- No image carousel — gallery is static.

---

## Future Improvements
- Implement backend to store registrations and live updates.
- Add a JavaScript-powered image carousel in the Gallery.
- Improve mobile layout for long text sections.

---

© 2025 School Tech Fest  
Created by Yash Kewlani – MYP 5 Design Project
