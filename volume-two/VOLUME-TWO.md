# You Probably Think This Song Is About You Too

## What This Is

Volume Two. The sequel that isn't a sequel. The detective solved the case — found out the file was his, walked through the door, the small string one grinned, the film kept rolling. So now what?

This is the album after the movie. Scenes are tracks now. The detective isn't investigating — he's listening. The world is a record that keeps playing whether you flip it or not. Side A. Side B. The scratches are part of it.

## How It Gets Made

Shane talks. Claude shapes. Raw voice dumps go into `raw-voice/` as transcripts. Tracks get pressed from the raw material — same noir third person, same cadence, same detective. But the detective has been to the doctor now. He knows the brain was never broken. So the voice is different. Not wiser. Just... less surprised.

ElevenLabs has 29 days on the clock. Every locked track becomes audio. The album ships when the album ships.

## Sacred Rules — Volume Two

1. **Still no names.** The detective. The small string one. The old man. The garbage man. You know them. You've always known them.
2. **Tracks, not scenes.** This is an album. The language is musical. Tracks play, skip, scratch, repeat. The needle drops.
3. **Track 000 exists.** It's the silence before the album starts — the needle in the groove before the sound. It's not numbered in sequence. It's the opening of nothing. Volume One hid a scene at the end. Volume Two starts with one that barely exists.
4. **The B-Side is not labeled.** Somewhere in the tracklist, the album flips. No announcement. No interlude. The reader crosses from Side A to Side B without being told. That's the trick this time — you don't know when it happened. You just feel it.
5. **The hidden track plays after silence.** The last numbered track ends. Then there's silence (a blank page, white space, whatever it is). Then the hidden track. No number. No title in the manifest. It just starts. Like the ones on the old CDs where you had to wait.
6. **The detective is the same detective.** He didn't become someone else. He just kept driving.

## Recurring Characters (continued)

Everyone from Volume One can return. They don't have to. New faces show up the way they do — in the periphery, in the rearview, at the counter.

- **The detective** — still driving, still watching, but the case is closed. Now he's just a man with a file he already read.
- **The small string one** — older now. Still feral. Still beloved.
- **New peripherals** — whoever shows up when Shane talks. The voice brings them in. Claude doesn't invent characters. Shane does. Even accidentally.

## Recurring Motifs (inherited + new)

*From Volume One (use as echoes, not repetition):*
- The cupholder rattle
- The gas station
- The billboard
- The body votes
- The film keeps rolling

*New (discovered as tracks are written):*
- The needle / the groove
- The skip / the scratch
- Side A / Side B
- The silence between tracks
- (more will emerge from Shane's voice dumps — don't force them)

## Structure

```
TRACK 000 — The Groove
  The needle before the sound. Almost nothing. The album hasn't started yet.

SIDE A — [untitled until tracks exist]
  Tracks 001–???
  The detective after the case. The world keeps playing.

  [THE FLIP — unmarked, somewhere in here]

SIDE B — [untitled until tracks exist]
  Tracks ???–???
  The record has been playing this whole time. You just noticed.

SILENCE

THE HIDDEN TRACK — [no number, no title in manifest]
  The thing after the end. You had to wait for it.
```

The structure fills itself as Shane talks. Don't pre-plan the tracklist. The album tells you what it is.

## File Layout

```
volume-two/
  VOLUME-TWO.md          — this file (the album bible)
  raw-voice/             — unedited voice-to-text dumps from Shane
  tracks/drafts/         — all track files (track-000.md through track-XXX.md)
  tracks/interludes/     — if they show up. they might not. albums don't always have interludes
  tracks/archived/       — retired drafts
  compiled/              — full assembled manuscript when ready
  docs/
    MANIFEST.md          — track index with status, themes, connections
    TRACK_TEMPLATE.md    — blank template for new tracks
```

## Track File Format

Same bones as Volume One but the language shifted:

- Title
- Status: Demo / Track / FLIP (the unmarked crossover) / HIDDEN (the last one)
- Themes
- Connects To (tracks + Volume One scenes where relevant)
- Lyrics (the monologue — called lyrics now because album)
- Liner Notes (the notes section — because album)

## Voice & Tone

Same voice. Same rules:
- Noir third person
- Short punches, long runs
- No lectures, no sermons
- Humor where you don't expect it
- Callbacks land as echoes

But the detective has been through the doctor's office now. He read his own file. So:
- Less searching, more sitting with it
- The questions are different — not "who am I" but "what now"
- The world isn't a mystery anymore. It's a record. It plays. You listen or you don't.

## The Pipeline

1. Shane records voice → dumps text into `raw-voice/` or pastes in chat
2. Claude shapes raw voice into track draft → `tracks/drafts/track-XXX.md`
3. Shane approves / redirects / riffs more
4. Track locks → status moves to Track
5. Locked tracks → ElevenLabs audio generation
6. Album compiles when it compiles

## Credit

Written by Shane Brazelton.
Co-built with Claude (Anthropic).
The sequel nobody asked for. The one that was always coming anyway.
