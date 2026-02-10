# bfhl-bajaj-api

Simple Node.js + Express implementation for the Chitkara Qualifier:
- POST /bfhl
- POST /bajaj
- GET /health

Both POST endpoints accept a single key in the JSON body: `fibonacci`, `prime`, `lcm`, `hcf`, or `AI`.
All successful responses follow the exact structure required:
```json
{
  "is_success": true,
  "official_email": "jasnoor4784.be23@chitkara.edu.in",
  "data": ...
}
