# dealers.json
NDSb Master Dealer List
[
  {
    "dealer_code": "ABC123",
    "partner": "Acme Co.",
    "contact": "John Doe",
    "phone": "555‑123‑4567",
    "email": "john@acme.com"
  },
  ...
]
├─ index.html          ← loads + searches the JSON
├─ dealers.js          ← small helper to fetch + build table
└─ admin/
    ├─ index.html      ← Decap CMS loader
    └─ config.yml      ← tells CMS where the JSON lives
