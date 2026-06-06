# Raise a Rock Docs

Current suggested structure, will work on this after the website-game is coded

raise-a-rock-docs/
│
├── staff/                                  # discord login required to view
│   ├── index.html                          # staff landing, links to all internal docs
│   ├── backend.html                        # how the hono server is structured
│   ├── database.html                       # full schema explained, table by table
│   ├── crons.html                          # decay cron logic, rates, famine/storm modifiers
│   ├── events.html                         # event engine internals, phase transition logic
│   ├── xp.html                             # xp formula, leveling thresholds, skill point math
│   ├── deployment.html                     # render setup, turso setup, env vars, mutual ping
│   └── api.html                            # all endpoints documented with example requests
│
├── css/
│   ├── public.css                          # styles for public pages
│   └── staff.css                           # styles for staff pages
│
├── js/
│   ├── auth.js                             # discord oauth flow, session cookie, staff gate
│   └── stats.js                            # live api polling for rock stats + event status
│
├── assets/                                 # branding, logo, any doc images
│
├── index.html                              # public landing, live rock stats widget
├── mechanics.html                          # how the game works (feeding, cleaning, praising)
├── classes.html                            # all 6 classes, dual class system, evolution trees
├── events.html                             # naming ceremony, invasion, storm, famine explained
└── world.html                              # territory system, hex map, fog of war, account slots
