# Founders Council

**Based on The Mal Show**, hosted by Youssef Samy Salem.

A six seat decision council for founders and operators in Egypt, the Gulf and the wider MENA region.
Each seat is an archetype built from three or more guests on The Mal Show, with their failures weighted as heavily as their wins.
Bring a decision to Claude, hear five honest positions, get one call.

How to use it, with worked examples: [athr21.com/writing/mal-show-council](https://athr21.com/writing/mal-show-council/) · [بالعربي](https://athr21.com/ar/writing/mal-show-council/)

## What is in the notes

One file per episode: key takeaways with timestamps, the numbers said on the show (marked as not checked), up to six short quotes, the stories and mistakes, and which seat each point feeds. In blind tests on six founder decisions, the council with these notes scored as well as one given the full transcripts (36 against 34 out of 50, twelve runs each).

## Why

Most AI "advisory boards" think like Silicon Valley: raise fast, burn, scale, exit. That advice breaks in a market where payroll cannot slip, customers pay in 90 days, a currency can move 30 percent in a year, and the company's money and the family's money are often the same pool. The people on The Mal Show built and funded companies in this region. Their stories, including what went wrong, are the ground this council stands on.

## The seats

| Seat | Lens | Built from |
|---|---|---|
| [Treasurer](seats/treasurer.md) | Cash is the clock. Everything else is a plan. | Ep 6, 8, 10, 5, 14, 13 |
| [Capital Sceptic](seats/capital-sceptic.md) | Money is a tool with an owner. Whose, on what terms, for what use? | Ep 7, 5, 3, 8, 15, 12, 11 |
| [Safety Net](seats/safety-net.md) | Take the risk, but survive being wrong, so you can bet again. | Ep 9, 6, 2, 10, 15 |
| [Conscience](seats/conscience.md) | How the money is made matters as much as how much. | Ep 4, 3, 9, 7, 6, 12 |
| [Long View](seats/long-view.md) | What does this look like in five years, and what are you not seeing? | Ep 1, 8, 2, 7, 10, 11, 13, 14 |
| [Ambassador](seats/ambassador.md) | Buyers here decide on trust before price. Who vouches for you, and does the founder carry the story? | Ep 5, 8, 10, 7, 9, 6, 4, 3, 11 |

No seat is a named guest. Nobody here says "I am Talal". Every seat lists the episodes it draws on and carries a section on what went wrong for the people behind it.

## Install

Pick the one that matches how you use Claude.

### 1. Claude app (claude.ai, desktop or mobile): add it as a skill

1. Download [mal-show-council-skill.zip](https://github.com/Athr21/mal-show-council/raw/main/dist/mal-show-council-skill.zip). Do not unzip it.
2. In Claude, open Settings, then Capabilities, and switch on code execution if it is off.
3. Under Skills, choose Upload skill and pick the zip.
4. Start a new chat and type: `run it through the council: <your decision>`.

### 2. Claude Code or Cowork: install it as a plugin

```
/plugin marketplace add Athr21/mal-show-council
/plugin install mal-show-council@athr21
```

Restart, then ask: `founders council: <your decision>`.

### 3. Any chat, no install: paste one file

Open [COUNCIL.md](COUNCIL.md), copy the whole file, paste it into a Claude Project's instructions or the first message of a chat, then write your decision in one or two sentences.

## How a run goes

The chair restates the decision and names the seats that matter for it, tests the goal and the numbers on your own figures, asks for up to three missing facts, then each seat speaks (position, risk, one question back, what would change its mind) or passes in one line. It names the disagreements and ends with one call, a confidence level and the one thing to check this week. It also says when a council is the wrong tool.

A full run on a realistic decision: [examples/example-run.md](examples/example-run.md) (a 60 person Cairo company choosing between a Series A now and 12 more months on profits).

## Rules we kept

- Archetypes, never impersonation. Three or more guests per seat.
- No transcripts. Each episode has our own notes in [skills/mal-show-council/references/notes](skills/mal-show-council/references/notes): key takeaways in our words, timestamped, with a handful of short quotes (15 words or fewer) for credit. The council cites a guest only from these notes or the seat text.
- What went wrong gets as much space as what worked.
- Nothing invented. If the show does not support a claim, the seat does not make it.
- No product, no pitch. Not investment advice.

## Credits

The Mal Show, hosted by Youssef Samy Salem: https://www.youtube.com/@TheMalShow1

- Ep 1, Roy Casagranda: https://www.youtube.com/watch?v=1J21W5nwvAU
- Ep 2, Abrar Khan (CryptoWala): https://youtu.be/nNzqQe3gXeU
- Ep 3, Abdallah Abu-Sheikh (Maal): https://www.youtube.com/watch?v=7mkkEIxdzD8
- Ep 4, Angel Wesley (Maal): https://www.youtube.com/watch?v=pqHYPOsMX04
- Ep 5, Dalia El Mohamady (Sawari Ventures): https://www.youtube.com/watch?v=nsCYRwU1SFs
- Ep 6, Talal Tabbaa (CoinMENA): https://www.youtube.com/watch?v=TR8loAasutc
- Ep 7, Wael Nafee (Raed Ventures): https://www.youtube.com/watch?v=azeLAwjjtHE
- Ep 8, Philip Bahoshy (MAGNiTT): https://www.youtube.com/watch?v=JBpEUVksXfA
- Ep 9, Sherine Kabesh (Flash): https://www.youtube.com/watch?v=Z5LKPclJCHY
- Ep 10, Jad Antoun (Huspy): https://www.youtube.com/watch?v=oKBXH8uTFHE
- Ep 11, Nader Bastaki (Dubai Future District Fund): https://www.youtube.com/watch?v=X3-n1BSYl9g
- Ep 12, Omar Al Yawer (Rüya Partners): https://www.youtube.com/watch?v=JgTtnOKKKB4
- Ep 13, Mohamad Kaswani (ex Mortgage Finder): https://www.youtube.com/watch?v=nVutIDpMhs0
- Ep 14, Vishnu Katara (MAL): https://www.youtube.com/watch?v=RFyOwRZZSas
- Ep 15, Armineh Baghoomian (PFG): https://www.youtube.com/watch?v=Bswa_N5huto

The seats and the method are our own work and do not represent the views of the show or its guests.

## Licence

Content is licensed under CC BY 4.0. See [LICENSE](LICENSE).

Made by Athr21 (athr21.com), built on The Mal Show with thanks to Youssef Samy Salem.
