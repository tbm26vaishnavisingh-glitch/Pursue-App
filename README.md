# 🥂 PURSUE — Premium Minimalist Fashion App  

Pursue is a high-end, luxury-focused minimalist fashion ecommerce experience.  
Products start at **₹15,000** and go up to **₹70,000**, mirroring high-fashion boutique pricing and experience.

Every time a user adds an item to the cart, the CTA reads **“Pursue This.”**  
This reinforces the brand philosophy — luxury is not bought, it is *pursued.*

The app walks the user through the complete shopping journey:

**Browse → Add to Cart → Pursue This → Checkout → Address → Delivery.**

---

## 🔗 Project Links
| Resource | Link |
|--------|-------|
| **Supabase** | https://supabase.com/dashboard/project/gqijkjdfmmiveuzchelc/editor/18604 |
| **Loom Walkthrough** | _add Loom video link here_ |
| **Figma UI File** | https://www.figma.com/design/So3odxDYIKMzbACbD27cAI/Premium-Minimalist-Fashion-App |

---

## 🧩 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vite + TypeScript + HTML/CSS |
| Database | Supabase (JSONB product catalog + orders) |
| Auth | Email/Password (Signup + Login + Forgot Password) |
| Version Control | Git + GitHub |

---

## ✨ Core Features

### 1. Landing Page  
- Presents the Pursue brand, minimal aesthetic, luxury pricing & product catalogue.

### 2. Authentication  
- ✔ Signup  
- ✔ Login  
- ✔ Forgot Password  

### 3. CRUD in Action  
| Operation | Example in App |
|---|---|
| **Create** | Add product(s) to cart, create an order |
| **Read** | View products, cart, past orders |
| **Update** | Modify quantity, edit address |
| **Delete** | Remove items from cart |

### 4. Full Order Flow  
> Add to Bag → **Pursue This** → Checkout → Address → Delivery Tracking

---

## 🗄️ Database (Supabase)

Table: `kv_store_1c267159`  
Stores:

- `categories` → Jackets / Shirts / Trousers / Suits etc.
- `product:*` → Individual product objects with JSONB fields like:
  - `id`
  - `name`
  - `price`
  - `image`
  - `material / fit / description`

Products are fetched directly from Supabase for real-time catalog access.

---

## 🚀 Running the Code

```bash
# Install dependencies
npm i

# Start development server
npm run dev
