# Issue tracker: board.md cards

Seat 34 tracks work as cards in `docs/processed/project/board.md`, not GitHub Issues. Students have read-only access to the school repo, and the course uses the board.

- A card is one line: `S34-NN | title | owner | milestone`, plus tags (see `triage-labels.md`) and a PR link when there is one.
- Sections: Backlog, Ready, Doing, Review, Done, Dropped. Move a card by moving its line.
- A new card takes the next free number, named at the top of `board.md`, and claims it in the title of the PR that adds it. Never reuse a number.
- Never delete a card. A card no longer needed goes to Done or Dropped with a one-line note saying why.
- A board change goes through a PR like any other change. Never edit another seat's files.
- Do not run `gh issue create` or `gh label create` for this seat.
