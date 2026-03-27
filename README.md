# tailng.com
Website content of tailng.com

## Genereate html files and start http server locally
```sh
find . -name "*.html" -type f -not -path "./partials/*" -delete
node generate-html.mjs
python3 -m http.server
```