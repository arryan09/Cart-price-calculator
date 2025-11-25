# Task 4 — Cart Price Calculator

This project calculates the total price of items in a cart using Express.js.

---

## 📌 API Route

### POST `/cart/total`

#### Request Example
json
{
  "items": [
    { "name": "Pen", "price": 10, "qty": 3 },
    { "name": "Notebook", "price": 40, "qty": 2 }
  ]
}
