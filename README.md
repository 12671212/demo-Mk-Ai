demo-mk-ai/
├── pages/
│   ├── index.js                 ← Home page with link to assets
│   ├── assets.js                ← Asset Explorer (GlassNeo Pulse theme)
│   ├── caption-generator.js     ← Caption tool with “Insert from Assets” button
│   ├── api/
│   │   ├── generate-caption.js  ← GPT integration
│   │   └── generate-image.js    ← Replicate integration
├── lib/
│   └── firebaseClient.js        ← Firebase + Firestore config
├── components/
│   └── Navbar.js                ← Nav bar with Assets link & theme toggle
├── public/                      ← Optional static assets
├── styles/
│   └── globals.css              ← GlassNeo Pulse styles
├── tailwind.config.js
└── package.json
