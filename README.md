# webExamples
Several web examples

## Maps
A google Maps V3 example

To run it please get a Google Maps Javascript API key (from [here](https://console.developers.google.com/apis/library)).
Replace YOUR_KEY_HERE in maps/index.html with your own key or use this command

```bash
sed -i "s/YOUR_KEY_HERE/<your own key>/g" maps/index.html
```

Then run it simple with

```bash
python -m SimpleHTTPServer
```

And go to localhost:8000/maps/
