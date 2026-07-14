# Solution Architecture

```
Schedule Trigger
        │
        ▼
RSS Feed
        │
        ▼
JavaScript Processing
        │
        ▼
OpenAI GPT
        │
        ▼
HTML Newsletter
        │
        ▼
Gmail
```

## Workflow Description

The workflow executes every weekend.

It collects Project Management news from RSS feeds.

JavaScript filters and prepares the data.

OpenAI generates a structured newsletter.

Gmail sends the newsletter automatically.
