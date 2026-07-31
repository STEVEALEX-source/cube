# cube apod

just a simple single-file app I made to check out NASA's astronomy pic of the day. wanted something clean with date navigation and a random button. added a fallback image too so the page doesn't break if the api acts up or hits a limit.

## changing the api key

it uses `DEMO_KEY` by default, but nasa's rate limits on that are pretty low. if you wanna use your own key:

1. grab a free key from [nasa's api site](https://api.nasa.gov/)
2. open `index.html` in your editor
3. find this line near the bottom:
   ```javascript
   const apiKey = "DEMO_KEY";