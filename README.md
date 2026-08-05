
cube
NASA's astronomy picture of the day, in a simple dark page.

setup
npm install
npm run dev
api key
By default it uses NASA's DEMO_KEY. That works, but the rate limit is low.

If you want your own key:

Get one free at https://api.nasa.gov/
Copy .env.example to .env
Put your key in there:
VITE_NASA_API_KEY=whatever_they_gave_you
Restart the dev server
Don't commit .env. It's already in .gitignore.

usage
prev / next — move one day at a time
date picker — jump to a specific day
random — random day since June 1995
crt — optional scanline overlay
Keyboard: ← → for days, R for random.

deploy
npm run build