# Project Ideas
Rather than just tweeting ideas out to the void, I'll start keeping project ideas here.

---

## Small Projects

### MHMCMC
Simulate the Monty hall problem using MCMC. CLI?

### AWS - S3 Cloud drive (small?)
CLI. Use a file watcher and the s3 sync tool to create a custom cloud drive in a bucket.

---

## Bigger Projects

### KNN - Allergies
I have bad allergies... sometimes. I'm allergic to Juniper pollen and something else.  Using [this resource](http://pollenandmold.stlouisco.com/Pollen_Day_Text.aspx), I can get daily pollen counts. With SMS, I could poll myself at noon every day, asking how I'm feeling (good/bad? 1-5?).

Tracking pollen counts and daily health, I could use KNN classification to analyze whether or not I'd need antihistamines on a given day.

**Problems:**
* Data gathering doesn't happen on weekends, creating gaps in consecutive day-to-day data.
* No records are made record until around 9-10am.

By 10am, I already know if I need allergies. Puts a damper on daily analysis.

Multi-day patterns: "Given counts of x,y, and z today and yesterday, tomorrow looks bad." But without weekend data, predictions would be limited to Tues-Saturday?


### Tabletop Status Board
Mostly a D&D thing, assumes a laptop and... tablet? tv?. One view for the DM, one view for players.

DM view is high level,
Player view focuses on the current turn.

UI Organizes by sessions -> encounters -> characters

Each encounter has:
1. A background image
1. A list of characters.

For each character:
1. Track turn order
1. Manage status conditions
1. Manage notes.
