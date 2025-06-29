demo-mk-ai/
├── pages/
│   ├── index.js                 # Home page with Assets teaser
│   ├── assets.js                # Premium Asset Explorer (GlassNeo Pulse)
│   ├── caption-generator.js     # Caption tool with Insert from Assets
│   ├── mockup-generator.js      # Image mockup tool
│   ├── dashboard.js             # Saved outputs & asset history
│   └── api/
│       ├── generate-caption.js  # OpenAI GPT integration
│       └── generate-image.js    # Replicate SDXL integration
├── lib/
│   └── firebaseClient.js        # Firestore / Firebase config
├── components/
│   └── Navbar.js                # Navbar with Assets link & theme toggle
├── styles/
│   └── globals.css              # GlassNeo Pulse Tailwind styles
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── seed_assets.json             # Sample Firestore import for `premium_assets`
