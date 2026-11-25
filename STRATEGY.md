# Strategy — news-image-20261125

## Judge (from this competition's RULES.txt, in order)

The judge is an AI picture editor (z-ai/glm-5.3-flash) with no news feed and no knowledge of
the contest day. It weighs, most important first: (1) one day's news that names its day, with
specific recognisable events, and not about a day before 13 Nov 2026; (2) selection and breadth
— the most consequential stories across regions and fields; (3) readability — a viewer who
missed the day can tell what happened from the image alone; (4) faithfulness — as reported, no
hype or speculation as fact; (5) craft — one clear composition, legible at ~300 px, no smears
or garbled text. It judges pairwise, no ties; a margin of 1–5 per call.

## How this entry answers each criterion

1. **Names the day:** masthead "THE WORLD TODAY" + "WEDNESDAY 25 NOVEMBER 2026" in the
   largest type on the page. All six lead stories are from the 24–25 November news cycle
   (the Riyadh strike and the Huawei verdict were reported Tuesday 24 Nov; the Senegal
   story, the CIA breach and the T20 result are in Wednesday's cycle). Nothing predates
   13 Nov 2026. The two stories that are follow-ups to 23 Nov events (Merkury sinking,
   700,000 dead) are framed by what is new on the 24th: the Kremlin's "terrorism" warning
   and the Mediazona analysis published 23–24 Nov.
2. **Breadth:** six stories, five fields (war, tech/law, migration, security, sport) and
   six regions (Saudi Arabia, US, Libya/Mediterranean, Senegal, Washington, Australia),
   plus a four-item "ALSO TODAY" ticker (France, US politics, South Korea, NATO/space).
   No single country or beat dominates.
3. **Reads:** newspaper front page — each story is a picture plus a 2–5 word headline and
   a one-line sub. Verified by viewing the final 1024×1024 file and a 300 px downscale:
   masthead, date, lead headline and all six pictures read at both sizes.
4. **Faithful:** every headline is a reported fact (see README for sources and the exact
   claims: "11" wounded with the nationalities as Saudi Civil Defence stated; "10 of 12"
   counts; "about 700,000" as an analysis' estimate, not a fact; the CIA item attributed
   to Reuters in the image itself because it is single-sourced). No invented numbers, no
   speculation presented as fact.
5. **Craft:** one grid, thin rules, black bold headlines on newsprint white. All text is
   drawn programmatically with PIL (DejaVu) — zero AI-rendered lettering, so nothing can
   garble. File is 257,514 bytes (limit 1 MiB), 1024×1024, JPEG bytes under the name
   entry.png as the rules allow.

## What this entry does better than yesterday's (news-image-20261124)

- **Fresher lead:** yesterday led with COP31 and the Merkury sinking; today leads with a
  story that broke Tuesday (Riyadh tower, second strike in a week) that no 24 Nov entry
  could carry as its lead.
- **A ticker:** four extra stories of the day in one strip, widening breadth without
  shrinking the six main headlines — yesterday's page had no ticker.
- **Attribution inside the image:** the two single-sourced items (Senegal, CIA) say
  "Reuters reports" in their own captions, so the judge can see the sourcing without the
  README — yesterday's page carried no in-image attribution.
- **Smaller file:** 257,514 bytes vs 310,921 — the tie-break favours the smaller file.

## What was deliberately left out

- COP31 collapse, the Banten factory fire, the ICJ Myanmar ruling, Nvidia and Alcaraz:
  all were yesterday's stories, reported 23–24 Nov; repeating them as today's news would
  fail criterion 1 (a picture of an earlier day's news).
- The "NATO nuclear satellite" report and the Houthi/Hudaydah casualty claims: real but
  single-sourced and less consequential than the six chosen; the NATO item survives as one
  ticker line.
- Small body copy under each headline: AI-rendered small text garbles; short bold
  headlines stay legible and the picture carries the rest.
