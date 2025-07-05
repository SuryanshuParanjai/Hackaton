# ReLive — See How Cities Have Changed Over Time

**ReLive** is a creative web app built for the "One API to Rule Them All" hackathon category. It uses the Wikipedia API to fetch information about any city in the world. With an elegant UI, dark mode toggle, loading animation, and ChatGPT integration, ReLive offers an immersive experience to explore city histories.

---

## Features

- Search any city (e.g., Paris, London)
- Dark mode toggle for better readability
- Animated loader while fetching data
- ChatGPT integration (optional)
- Wikipedia REST API for real-time data
- Deployed frontend via Netlify

---

## Tech Stack

### Frontend:
- React.js — UI library
- Tailwind CSS — Styling and dark mode
- Axios — HTTP client
- Netlify — For deployment

### Backend:
- Node.js — JavaScript runtime
- Express.js — Server framework
- CORS — Enable frontend-backend communication
- Wikipedia REST API — To fetch city summaries

---

## Folder Structure

Hackaton/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ │ ├── CityCard.js
│ │ │ └── Loader.js
│ │ ├── App.js
│ │ └── index.js
│ ├── public/
│ ├── tailwind.config.js
│ ├── postcss.config.js
│ └── package.json
├── server/ # Node.js backend
│ ├── app.js
│ └── package.json
└── README.md

---

![WhatsApp Image 2025-07-05 at 18 45 55_1dab6f65](https://github.com/user-attachments/assets/8524440f-c438-4ed0-af2d-92c5350519b9)
![WhatsApp Image 2025-07-05 at 19 14 23_ba1bc005](https://github.com/user-attachments/assets/4c59a1fa-bb73-410a-b49c-905f8dbe276c)
![WhatsApp Image 2025-07-05 at 04 11 12_8c4355e3](https://github.com/user-attachments/assets/b686880e-9207-4947-af14-245a588d4062)
![WhatsApp Image 2025-07-05 at 04 11 12_e1a6c73d](https://github.com/user-attachments/assets/669e9568-d6a9-490f-9ce0-ec9daf09f960)
![WhatsApp Image 2025-07-05 at 04 11 13_4d763c8b](https://github.com/user-attachments/assets/bbc853db-efa4-4062-b78c-ddb057a69ed9)

## Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/relive.git
cd Hackaton

### Backend Setup
cd server
npm install
node app.js

### Frontend Setup
cd client
npm install
npm start


API Used
We use the Wikipedia REST API to fetch clean and concise information about cities using this endpoint:

ruby
Copy
Edit
GET https://en.wikipedia.org/api/rest_v1/page/summary/{city}
Example:

ruby
Copy
Edit
https://en.wikipedia.org/api/rest_v1/page/summary/London


One API to Rule Them All — Hackathon Innovation Challenge

Stretching the Wikipedia API to offer a sleek and creative city exploration experience.

Wikipedia Foundation for the open API

Tailwind CSS team

OpenAI for ChatGPT integration (optional)







