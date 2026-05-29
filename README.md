AIzaSyBjG1AWtWzn9kJBy9h8M89ynOwG0aklCJ0


curl "https://generativelanguage.googleapis.com/v1beta/models/gemini-flash-latest:generateContent" \
  -H 'Content-Type: application/json' \
  -H 'X-goog-api-key: AIzaSyBjG1AWtWzn9kJBy9h8M89ynOwG0aklCJ0' \
  -X POST \
  -d '{
    "contents": [
      {
        "parts": [
          {
            "text": "Explain how AI works in a few words"
          }
        ]
      }
    ]
  }'
