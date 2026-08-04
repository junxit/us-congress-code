# Gaps in this history

Release points omitted because the official OLRC archive was
structurally damaged. They are skipped rather than committed, because
committing a truncated snapshot would invent a mass deletion followed
by a restoration -- a history that never happened.

| Release point | Published | Damage |
|---|---|---|

## Titles carried forward

These archives parse cleanly but are truncated: a title loses a large
share of its sections while OLRC does not list it as affected, and the
content returns in a later release point. `usc46.xml` drops from 912
sections to 576 across 113-44 and 113-45, then returns to 912.

Committing that verbatim would record hundreds of repeals and then
reverse them, so the previous snapshot's text is carried forward instead.

A title the archive declares torn down is exempt and its loss is
committed as the real change it is: OLRC eliminated Title 50 Appendix
in 2015, and Pub. L. 117-286 gutted Title 5 Appendix in 2022. Both
state it -- the first in its heading, the second by marking every
surviving section repealed, transferred or omitted.

| Release point | Published | Titles carried forward |
|---|---|---|
| `pl-113-44` | 2013-10-10 | title-28 (803 -> 638 sections), title-46 (912 -> 576 sections) |
| `pl-113-45` | 2013-10-15 | title-28 (803 -> 638 sections), title-46 (912 -> 576 sections) |

## Damaged titles carried forward

The archive for these titles was unusable, but OLRC did not list them as
affected by the release point, so the previous snapshot's text still
stands and was carried forward.

| Release point | Published | Titles |
|---|---|---|
| `pl-113-46` | 2013-10-17 | t16: dropped 4 unmatched end tags: </chapter>x1, </notes>x1, </section>x1, </subchapter>x1 |
| `pl-113-65` | 2013-12-20 | t31: unparseable (ParseError: not well-formed (invalid token): line 9593, column 91) |
| `pl-114-93not92` | 2015-11-25 | t50A: closed 1 unclosed elements |
| `pl-114-100not94not95` | 2015-12-16 | t50A: closed 1 unclosed elements |
| `pl-114-114not95not113` | 2015-12-28 | t50A: closed 1 unclosed elements |
| `pl-114-115not95` | 2015-12-28 | t50A: closed 1 unclosed elements |
