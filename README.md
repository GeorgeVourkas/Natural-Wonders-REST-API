# 🌍 Natural Wonders REST API

A Node.js REST API that provides structured data about unique and extraordinary natural locations around the world. The API supports filtering via URL query parameters and is designed as a backend-only project.

---

## 🚀 Features

- Retrieve a list of natural wonders in JSON format
- Filter results using URL query parameters
  - `country`
  - `continent`
- Clean and consistent data structure
- UUID-based identification for each entry
- Local development setup

---

## 🛠 Tech Stack

- Node.js
- JavaScript (ES Modules)
- REST API architecture

---

## 📦 Data Structure Example

```json
{
  "name": "Pamukkale",
  "location": "Denizli",
  "country": "Turkey",
  "continent": "Asia",
  "is_open_to_public": true,
  "uuid": "550e8400-e29b-41d4-a716-446655440009",
  "details": [
    {
      "fun_fact": "The white terraces are made of travertine deposited by thermal springs."
    },
    {
      "description": "A natural site featuring tiered white terraces and warm mineral-rich waters."
    }
  ]
}
