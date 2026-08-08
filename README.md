# Football Transfer News Archive

A structured archive of recurring European football transfer reports, with **Manchester United** as the primary focus.

## Scope

This repository stores transfer-market reports only. Other recurring intelligence streams such as gaming news, market recaps, reading recommendations, or project monitoring belong in separate repositories.

Coverage priority:

1. Manchester United
2. Major Premier League clubs
3. Real Madrid, Barcelona, Bayern Munich and other major European clubs

## Archive layout

```text
reports/
  2026/
    07/
      2026-07-18.md
      ...
    08/
      2026-08-01.md
      ...
RULES.md
INDEX.md
```

Each Markdown file is a snapshot of the report that was generated for that calendar day. If a weekly summary was included in that day's original report, it remains in the same file so the historical delivery is preserved.

## Source and confidence policy

Reports prioritize club, league and association announcements, followed by high-quality football reporting such as BBC Sport, The Athletic, Sky Sports, The Guardian, David Ornstein, Fabrizio Romano and reliable club/local correspondents.

Transfer states are kept distinct: official/registered, near completion, agreement or medical arranged, negotiations, interest/preliminary contact, and low-confidence rumor.

## Historical archive notice

These files preserve the report **as delivered at the time**. Transfer reporting changes quickly, and later information can supersede an earlier report. A historical report may therefore contain claims that were later corrected, denied or overtaken by events. The archive should be treated as a time-stamped intelligence record rather than a retroactively rewritten database of final facts.

## Backfill policy

Historical reports are imported only when a sufficiently complete prior report can be recovered from sent-email or chat history. Missing dates are left missing rather than reconstructed from guesswork.

Initialized for archival use on 2026-08-09.
