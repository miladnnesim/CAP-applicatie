# Getting Started

Welcome to my read-only CAP project.

This project uses the recommended folder structure:

| File or Folder | Purpose                              |
| -------------- | ------------------------------------ |
| `app/`         | Fiori UI frontend                    |
| `db/`          | Domain models and initial data       |
| `srv/`         | Service definitions and custom logic |
| `package.json` | Project metadata and dependencies    |
| `readme.md`    | This getting started guide           |

---

## Requirements

Before running the project, make sure you have installed:

```bash
npm install axios dotenv
```

---

## Running the App

To start the CAP server locally, run:

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file in the cap-api-fiori folder and add:

```env
TOKEN_URL=https://41208216trial.it-cpitrial05-rt.cfapps.us10-001.hana.ondemand.com/http/cp006if002
IFLOW_URL=...
CLIENT_ID=...
CLIENT_SECRET=...
```

Replace the values with your actual API credentials and iflow url.

---

## Learn More

Find the full CAP documentation at:  
👉 https://cap.cloud.sap/docs/get-started/
