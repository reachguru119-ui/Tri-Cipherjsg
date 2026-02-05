# Tri-Cipherjsg

curl -X POST http://127.0.0.1:8000/api/voice-detection ^
  -H "Content-Type: application/json" ^
  -H "x-api-key: tri-cipherjsg" ^
  -d "{\"language\":\"Tamil\",\"audioFormat\":\"mp3\",\"audioBase64\":\"PASTE_BASE64_HERE\"}"
