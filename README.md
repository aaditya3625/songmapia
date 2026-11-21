# songmapia

A daily music game. Every dot on the map is a real place named in one artist's songs. Guess the artist in five tries.

## How it plays

You see a map of the places named in the songs of one secret artist. Type a guess, and each wrong guess is compared with the answer in four ways:

- **Genre**: green if you share the main genre, amber if the main genres differ but you share a genre tag.
- **Era**: the decade the artist first charted, with an arrow toward the answer.
- **Home**: green for the same US state, amber for the same region (or the same country's region for artists outside the US).
- **Shared pins**: how many places both artists name, counting places within 25 km as the same.

Two free hints are on offer: how many places are on the map, and a hint about the name. Tap any pin to see its name. When pins crowd together, scroll, pinch or double-click to zoom in, drag to move, and press Reset view to start over.

A new artist appears every day, the same for everyone, and the day changes at midnight UTC. Practice gives you as many extra rounds as you like. When a round ends you can copy your result and send it to friends. After the answer is revealed, each place is listed with the songs it appears in.

## Data & credits

- **Places and songs:** gathered from lyric pages, song-fact sites and press features. No lyrics are stored, only place names, song titles and links. `data/artists_master_all40.csv` lists every place with its song, coordinates, source and check links. A few places and first-chart years may still be off, so please open an issue if you spot a mistake.
- **Genres:** each artist's Wikipedia page.
- **Coastlines:** [Natural Earth](https://www.naturalearthdata.com/), public domain.
- **Font:** Space Grotesk, via Google Fonts.
- **Inspiration:** layout and style follow regnum, and the daily format follows Wordle.

songmapia is an independent project and is not affiliated with any artist, label or lyrics site.
