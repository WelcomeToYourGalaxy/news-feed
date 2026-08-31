# news-feed

A live wire on the news industry worldwide: who owns the newsroom, what
replaced the reporting, who is paying to pollute it, and what happens to the
people still doing the work.

Built after "The News Industry" on Welcome to Your Galaxy.

**This is a feed about the news industry, not a news feed.** That is the hard
part: every other wire here can lean on its vocabulary being rare, and this one
cannot, because every source it reads is the news industry writing about
everything else. So no subject term stands alone. "Journalist" only counts
beside jailed, detained, killed, charged or exiled. "Newsroom" only beside
cuts, closure or a raid. "Censorship" only beside an outlet, a broadcast or a
blocked site.

## The twenty subjects

| | |
|---|---|
| Who owns the news | Shareholder value over public service |
| What replaced the reporting | Newsrooms and news deserts |
| Machine-made news | State information operations |
| Bought and industrial disinformation | Framing and enemy-making |
| Rating the outlets | Checking, correcting and being wrong |
| Press freedom overall | Detention, prosecution and exile |
| Journalists killed | Watching the reporters |
| Blocking and shutting down | Lawsuits as a method |
| Distribution and dependency | Who pays for it |
| What it costs everyone else | What is set against it |

## Weight

A decision (2), institutional material (2), a measured figure (1), a pending
decision with a date (1), a named jurisdiction (1), a primary source (1). At
three or more it is marked consequential.

## Sources

183 wires. 29 direct feeds carried over from the sibling repos where they are
already proven, plus 138 Google News locale searches across 26 languages with
24 rotating queries, and 16 subject searches.

Note that `press` standing here means the industry reporting on itself, which
is worth knowing when reading those rows.

Worth adding, with URLs you have opened: Reporters Without Borders, the
Committee to Protect Journalists, IPI, IFJ, the Reuters Institute, NewsGuard,
Nieman Lab, Press Gazette, the Media Freedom Rapid Response and Rest of World.
This subject has better specialist sources than almost any other here, and the
direct list would improve more from them than any amount of extra searching.

## Running it

    python3 harvest_news.py
    python3 harvest_news.py --dry-run
    python3 verify_sources.py
