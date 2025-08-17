# Conference Expense Planner

The **Conference Expense Planner** is a practice React application that helps users plan and calculate expenses related to hosting a conference at a convention center.  

The app guides the user through selecting venue rooms, audio/visual add-ons, and catered meals. It dynamically calculates pricing based on user input and provides a pop-up summary with a detailed expense breakdown.  

---

## 🚀 Features

### Landing Page
- Company name and branding  
- Background image  
- Company description  
- **Get Started** button → navigates to the product selection page  

### Product Selection Page
Organized into **three main sections**:

1. **Room Selection**  
   - Auditorium Hall – capacity 200, $5500 ea  
   - Conference Room – capacity 15, $3500 ea  
   - Presentation Room – capacity 50, $700 ea  
   - Large Meeting Room – capacity 10, $900 ea  
   - Small Meeting Room – capacity 5, $1100 ea  
   - ➕ Increment and ➖ decrement buttons for selecting room quantities  

2. **Add-ons Selection**  
   - Speakers – $35 ea  
   - Microphones – $45 ea  
   - Whiteboards – $80 ea  
   - Projectors – $200 ea  
   - Signage – $80 ea  
   - ➕ Increment and ➖ decrement buttons for selecting add-on quantities  

3. **Meals Selection**  
   - Breakfast – $50 per person  
   - Lunch – $60 per person  
   - High Tea – $25 per person  
   - Dinner – $70 per person  
   - Text input field for entering the number of attendees for each meal  

### Navigation Bar
- A **Show Details** button  
- Clicking it opens a **pop-up summary window**  

### Pop-up Summary
- Displays a table with:
  - Item type  
  - Unit cost  
  - Quantity  
  - Subtotal  
- Shows the **total expense** at the bottom  

---

## 🛠️ Tech Stack
- **React** (functional components & hooks)  
- **CSS Modules** for styling  
- **Props & State** for dynamic UI updates  
- **map() function** to render items dynamically  

---

## 📊 Key Functionalities
- Dynamic pricing calculation  
- Increment/decrement buttons for item selection  
- Form input for meal counts  
- Real-time updates to total cost  
- Pop-up modal with full breakdown  

---

## 🔮 Relation to Final Project
This practice project shares many similarities with the **Final Project: Household Plant Shopping Cart**, including:  
- Landing page and navigation  
- Product arrays and selection arrays  
- Subtotal & total cost calculations  
- Increment/decrement buttons  
- Dynamic pricing display  
- Use of Redux Toolkit (in final project) for global state management  

---

## 📂 Project Structure
