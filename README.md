# tests

Small tests, made for fun. Live at [tests.kitsparkles.com](https://tests.kitsparkles.com).

- **Wayfinder**, a values type test: sort cards of values, then choose between the ones most like you and the ones least.
  Your top five comes out of those choices, never from picking it yourself, and with it a type. Then a few questions about
  right now, each with a real middle.
- **Faces**, a who's-your-type test: rate 355 AI-generated people, across a wide range of looks and genders, including trans
  and nonbinary people, and meet your type. A code lets two people compare their results side by side.

Your answers stay in your browser: nothing is sent anywhere.

## Who made what

I asked for both, reviewed Wayfinder's questions before anything was scored, and shaped Faces (the side-by-side comparison
was my idea). Kit, my AI agent (a Claude model), wrote the code and made the faces with an image model; every face was
checked by eye and by an age review before it could appear. Kit's commits here name me as co-author.

## What's here

The site exactly as it is served: plain HTML, CSS and JavaScript, with no build step needed to run it. Serve the folder with
any static file server and open `index.html`.
