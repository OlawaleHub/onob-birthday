# Happy Birthday, Madam Onob 🎉

A birthday card made by the Telesales Team — a five-page web experience with a
rotating photo carousel, a personal message from every team member, and a
closing celebration.

## What's inside

A single self-contained page (`index.html`) plus her photos. No build step, no
dependencies, no frameworks — just HTML, CSS and a little JavaScript.

- **Cover** — opens with a presentation note from the Team Lead
- **Greeting** — her name, in gold
- **Letter** — a few honest words, signed
- **Moments** — her photos on a rotating 3D carousel
- **Birthday texts** — a personal message from each of the eight team members
- **Finale** — a candle to blow out, then balloons, lights and music

## Running it locally

Open `index.html` in a browser. That's it.

If you prefer a local server:

```bash
python -m http.server 8000
```

then visit http://localhost:8000

## Deploying

This is a static site — no build command, no output directory.

1. Push this repository to GitHub.
2. On [Vercel](https://vercel.com), **Add New → Project**, import the repository.
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Deploy.

## Notes

- Photos live in `photos/` and are referenced as `1.jpg` … `5.jpg`.
- The music is generated in the browser, so there is no audio file to host.
- Sound starts only when the candle is blown out, and can be muted with the
  speaker button on that page.
