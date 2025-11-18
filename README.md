# npm-install
---
- create a folder mybot
- create a file index.js

## Folder Structure
```bash
mybot/
│
├── index.js
├── package.json             <-- Automatic
├── package-lock.json        <-- Automatic
├── node_modules/            <--  Automatic
│
├── auth/                    <-- Auto-created
│   ├── creds.json
│   └── other auth files
│
├── replies/                 <-- YOU must create this
│   ├── whatsapp.txt
│   ├── facebook.txt
│   ├── instagram.txt
│   ├── kali_linux_install.txt
│   └── location_tracking.txt
│
└── README.md
```
---
| packages      | version  |
|---------------|---------|
| node -v | v24.11.1 ✅ |
| npm -v  | v11.6.2 ✅ |
---
## create a folder (mybot)
```bash
mkdir mybot
```
## go to the folder 
```bash
cd mybot
```
## create a file (index.js)
```bash
nano index.js
```
## package.json file create command
```bash
npm init -y
```
## package-lock.json file create command
```bash
npm install
```
## create node_modules file coomnd
```bash
node_modules
```
