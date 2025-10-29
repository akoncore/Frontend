
# 🛍️ Angular Shop Application

This project is a small **Shop Application** built using the **Angular** framework.  
It allows users to select product categories, view products, like, remove, and mark them as favorites.

---

## 🚀 Technologies Used

- **Angular 17+**
- **TypeScript**
- **HTML / CSS**
- **VS Code** (recommended editor)

---

## 📁 Project Structure
src/
└── app/
├── Components/
│ ├── product-item/
│ │ ├── product-item.component.ts
│ │ ├── product-item.component.html
│ │ └── product-item.component.css
│ └── product-list/
│ ├── product-list.component.ts
│ ├── product-list.component.html
│ └── product-list.component.css
├── app.component.ts
├── app.component.html
├── app.component.css
├── app.routes.ts
└── app.config.ts

---

## 🧩 Main Components

### 🔹 AppComponent
- The root component of the entire application.
- Manages product categories and the full product list.
- Filters products based on the selected category.

**Example:**
```typescript
categories = ['Food', 'Drinks', 'Sauce', 'Desert', 'Favorite'];

<button (click)="likeProduct()">Like</button>
<button (click)="removeProduct()">Remove</button>
<button (click)="favoriteProduct()">Favorite</button>

