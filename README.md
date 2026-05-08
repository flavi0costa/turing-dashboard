# turing-dashboard

turing-dashboard/
├── web-ui/                 # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── WatchlistPanel.jsx
│   │   │   ├── LayoutCanvas.jsx
│   │   │   ├── PreviewPane.jsx
│   │   │   ├── HardwarePanel.jsx
│   │   │   ├── ProfileManager.jsx
│   │   │   └── ThemeSelector.jsx
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── index.js
│   ├── package.json
│   └── .gitignore
│
├── backend/                # Python daemon
│   ├── monitor_daemon.py
│   ├── data_fetcher.py
│   ├── renderer.py
│   ├── config_manager.py
│   ├── requirements.txt
│   └── .gitignore
│
├── config/
│   ├── config.json         # Profiles, layouts, watchlist
│   └── cache/              # Preços cached
│
├── .gitignore
└── README.md