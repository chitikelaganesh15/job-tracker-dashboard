# Job Application Tracking Dashboard

A professional React dashboard to track job applications with local storage persistence.

## Features

- Dashboard with statistics (Total, Applied, Interview, Rejected)
- Add, edit, and delete job applications
- Search by company name and filter by status
- Data saved in local storage (persists after refresh)
- Responsive, modern UI

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

```
src/
├── components/
│   ├── Header.jsx
│   ├── Stats.jsx
│   ├── JobForm.jsx
│   ├── JobList.jsx
│   ├── JobCard.jsx
│   └── SearchFilter.jsx
├── App.jsx
├── App.css
└── main.jsx
```

## Build for Production

```bash
npm run build
```
