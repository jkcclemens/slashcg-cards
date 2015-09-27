# Slash cards
I was annoyed that the only format that the Slash cards came in was a PDF. So, I converted the PDF to a JSON file by hand from [this](http://static1.squarespace.com/static/52403f80e4b0cd883dbfb365/t/529dec8fe4b0eca039ce2607/1386081423074/Slash+pnp+131128.pdf).

This should allow for people to have access to the cards to make things!

If you notice any mistakes, please let me know with an issue, or make a pull request.

# Format
The JSON file is an array with several objects in it.

The objects all have the following keys:
- `name`: The name of the character on the card
- `origin`: The subtext beneath the character on the card, which is the character's origin
- `gender`: The gender listed on the card, which is one of the following
  - `m`: male
  - `f`: female
  - `t`: transgender
  - `/`: not applicable (?, never explained)
  - `|`: used for the tetris line block card
- `points`: The amount of points the card is worth
- `description`: The description on the card
