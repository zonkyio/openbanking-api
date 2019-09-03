# Zonky Open Banking API
Repository for Zonky Open Banking API documentation. The latest version of the documentation is publicly available on Apiary (https://zonkyopenbanking.docs.apiary.io).

## Local Development
You can build and export the documentation locally outside Apiary with a few simple steps. All you need is working Node.js environment on your machine.

1. Clone this repository
```bash
git clone git@github.com:zonkyio/openbanking-api.git
cd openbanking-api
```

2. Install project dependencies
```bash
npm install
```

3. Run development server
```bash
npm run dev
```
Server will start on `http://localhost:3000` and will listen for changes in `apiary.apib` file.

4. Export documentation
```bash
npm run build
```
The documentation will be exported to a single `output.html` file.
