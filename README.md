# Sneakslab

Sneakslab is an online sneaker store built for the way people actually shop. Browse 366 sneakers from top brands, from the latest drops on the homepage carousel to seasonal collections. You can narrow the catalog by brand, price and size, and every product page shows its available sizes and real reviews. Prices appear in your local currency automatically. Save favorites to your wishlist, check out quickly with saved addresses, and track every order after it ships. If you need help, the help center covers returns, shipping and order status, and live chat connects you to support right away. Behind the storefront, a complete admin back office keeps orders, promotions, stock, users and support tickets running smoothly.

<p align="center">
  <b><i>"Sakam adda sapatos mi."</i></b>
  <br>
  "We have shoes for your feet."
</p>

## Tech Stack

| Category | Technology |
| --- | --- |
| Runtime | ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white) |
| Backend | ![Express](https://img.shields.io/badge/Express_5-000000?style=for-the-badge&logo=express&logoColor=white) |
| Templating | ![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black) |
| Frontend | ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| Database | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) |
| Real-time | ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white) |
| HTTP Client | ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) |
| Email | ![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white) |
| Hosting | ![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white) |

## How It Works

- **Server:** a Node.js and Express 5 app that renders EJS views, with MongoDB storing products, users, orders and support tickets.
- **Catalog:** products are imported in bulk from the Sneaker Database API, then managed locally with their own stock.
- **Local pricing:** visitors are geolocated by IP, and prices are converted to their own currency using live exchange rates.
- **Accounts:** sessions with bcrypt-hashed passwords. Verification and password-reset emails are sent through Resend.
- **Support chat:** runs over Socket.IO, with one room per ticket so customers and admins talk in real time.
- **Deployment:** hosted on Render.

## Highlights

- A 366-sneaker catalog imported from the Sneaker Database API, with search and brand, price and size filters
- Detects the visitor's country and shows prices in their local currency
- Live support chat on tickets over Socket.IO
- An admin back office for orders, sales, stock, users, support and activity logs
- Loading skeletons and custom 404 and 500 pages, so the app handles failures gracefully

---

> This repository is maintained by the project members, and all features were developed as a team. This project is in fulfillment of the course Web Systems and Technologies 2 at the University of Baguio - School of Information Technology.
