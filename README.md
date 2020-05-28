# Notes-App
This is a simple command line NodeJS app that alllows you to read, write, delete and list down notes.

## Installing node modules
Use npm to download the require node modules

```bash
npm i
```

## Usage
1. Adding a notes
```bash
node app.js add --title="Note 1" --body="Sample body"
```

2. Removing a note
```bash
node app.js remove --title="Note 1"
```
3. Listing notes
```bash
node app.js list
```

4. Reading a note
```bash
node app.js read --title="Note 1"
```
