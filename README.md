# auto-sust-yiban-infoupload

## Requirement

- [Node.js](https://nodejs.org/) > 12.0.0

## Usage

```bash
git clone https://github.com/ShirasawaSama/auto-sust-yiban-infoupload.git

cd auto-sust-yiban-infoupload

npm install
```

## Run

```bash
npm start
```

Or using `pm2`:

```bash
npm install -g pm2

pm2 run index.js
```

## Status

open `http://127.0.0.1:2333/status`

## Whitelist

Edit `config.json`:

```json
{
  "名字1": "",
  "名字2": ""
}
```

Then restart the application.

## Author

Shirasawa

## License

[MIT](./LICENSE)
