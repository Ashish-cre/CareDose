# CareDose

CareDose is a responsive frontend prototype for medication management, designed with senior citizens and caregivers in mind.

## Run locally

1. Open a terminal in this folder.
2. Run `npm install`.
3. Run `npm run dev`.
4. Open the local URL shown by Vite (normally `http://localhost:5173`).

## Project structure

- `src/main.jsx` contains the React routes, reusable layout components, and local demo state.
- `src/styles.css` contains the responsive visual design.
- `index.html` is the Vite entry document.

## Main features

- Landing, login, registration, patient dashboard, medicines, reminders, history, caregiver, about, and contact routes.
- Large readable UI, contrast-conscious controls, and responsive desktop/tablet/mobile layouts.
- LocalStorage demo persistence for medicines, schedule updates, and medication history.
- Add a medicine, mark upcoming doses as taken, filter history, and navigate the complete demo flow.

## QR scanner demo

The QR scanner is intentionally simulated for a frontend-only presentation. Start Scanner or Upload QR Image starts a brief visual scan, then displays mock Metformin details. Selecting Add to My Medicines stores that medicine in the local demo list.
