# Text-to-Speech API Example

## Endpoint

POST /webhook/text-to-speech

### Request

```json
{
  "text":"Hello World",
  "voice_id":"21m00Tcm4TlvDq8ikWAM",
  "model_id":"eleven_multilingual_v2"
}
```

### Success Response

- HTTP 200
- Content-Type: audio/mpeg

Returns generated speech audio.

### Error Response

```json
{
  "success": false,
  "message": "Missing required parameter."
}
```
