## Promote queue item

```cURL
curl -X POST "https://api.nightbot.tv/1/song_requests/queue/5688d2bdc93762323f402b9d/promote" \
  -H "Authorization: Bearer 4fb1fed8889ec9d1c319d5b3c9a54b23"

{
    "status": 200,
    "item": {
        "_id": "5688d2bdc93762323f402b9d",
        "createdAt": "2016-01-03T07:50:21.334Z",
        "updatedAt": "2016-01-03T07:50:21.334Z",
        "track": {
            "providerId": "r9gz0Z9yV1k",
            "provider": "youtube",
            "duration": 197,
            "title": "I'm Just a Kid - Simple Plan lyrics",
            "artist": "sabrina01021997",
            "url": "https://youtu.be/r9gz0Z9yV1k"
        },
        "user": {
            "name": "test_user_2",
            "displayName": "test_user_2",
            "providerId": "93854453",
            "provider": "twitch"
        },
        "_position": 1
    }
}
```

Promotes a queue item to the front of the queue

**HTTP Request**

`POST https://api.nightbot.tv/1/song_requests/queue/:id/promote`

**Scope**

`song_requests_queue`
