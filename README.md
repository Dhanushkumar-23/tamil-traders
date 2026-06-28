# Sri Tamil Traders — Electricals, Pipes & Hardware

A simple ordering website for a local electrical and hardware shop. Customers browse what's in stock by aisle, add items to a cart, and place an order. Shop staff manage stock from a built-in admin dashboard — no backend required.

## Features

- *3D animated hero* — a wireframe bulb that "switches on" and rotates as you scroll, built with Three.js
- *Aisle-based catalog* — Bulbs & Lighting, Pipes & Conduits, Wires & Cables, Switches & Sockets, Tools & Others
- *Live stock status* — each product is stamped "In Stock" or "Out of Stock"
- *Cart & checkout* — add items, adjust quantities, and place an order with name, phone, and delivery address
- *Staff dashboard* — add, edit, or delete products, flip stock availability with a toggle switch, and track incoming orders
- *No backend needed* — runs entirely in the browser using localStorage, so it works straight off the file system or any static host

## Tech Stack

- HTML, CSS, vanilla JavaScript
- [Three.js](https://threejs.org/) for the 3D scroll animation
- Google Fonts (Oswald, Inter, Space Mono)

## Getting Started

1. Clone or download this repository.
2. Open the folder in VS Code (or any editor).
3. Open index.html with the *Live Server* extension, or any local server — avoid double-clicking the file directly, as some browsers restrict local file access.

No build step, no dependencies to install.

## Project Structure


.
├── index.html      # page markup
├── styles.css      # all styling
└── script.js       # catalog, cart, checkout, admin dashboard, 3D animation


## Staff / Admin Access

Click *"Staff login"* in the footer. Default passcode:


tamil123


> ⚠️ This is a soft client-side gate, not real authentication — the passcode is visible in the source code. Fine for a demo or internal tool; for a public production site, swap the storage layer and admin login for a proper backend with real authentication.

## Data Storage

Product stock, cart contents, and orders are saved in the browser's localStorage, scoped to whoever opens the page on their own device. There's no shared database — for a multi-device or multi-staff setup, this would need a real backend.

## License

Free to use and modify for your own shop or project.
