# Bluesky Promo Posting Guide

## Overview

Bluesky posts from `bluesky-posts.json` — adapted for Bluesky's 300-character limit and community norms (no hashtag spam, natural voice preferred).

## Posting via AT Protocol

Bluesky uses the AT Protocol. To post programmatically:

```bash
# Login and get session token
curl -X POST https://bsky.social/xrpc/com.atproto.server.createSession \
  -H "Content-Type: application/json" \
  -d '{"identifier": "YOUR_HANDLE.bsky.social", "password": "YOUR_APP_PASSWORD"}'

# Create a post
curl -X POST https://bsky.social/xrpc/com.atproto.repo.createRecord \
  -H "Authorization: Bearer YOUR_ACCESS_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{
    "repo": "YOUR_DID",
    "collection": "app.bsky.feed.post",
    "record": {
      "$type": "app.bsky.feed.post",
      "text": "YOUR POST TEXT",
      "createdAt": "2026-03-20T12:00:00Z"
    }
  }'
```

## Schedule

- **Week 1:** 1-2 posts/day — build presence
- **Week 2+:** 1 post/day — consistent cadence
- Bluesky is more conversational — respond to all replies

## Post Categories

| Type | IDs | Best for |
|------|-----|----------|
| **tagline** | 1, 15 | Launch, pinned |
| **excerpt** | 2, 4, 6, 8, 10, 12, 14 | Daily rotation |
| **hook** | 3, 9 | Discovery |
| **question** | 7, 11 | Engagement |
| **personal** | 5, 13 | Weekend, authenticity |

## Notes

- No hashtags on Bluesky — they don't function the same way
- Add link card embeds when possible for better engagement
- Bluesky audience skews toward writers and tech — lean into both angles
