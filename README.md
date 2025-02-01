```bash
$ curl -X GET https://descriptionapi.onrender.com/aboutme -i
HTTP/1.1 400 Bad Request
Content-Type: application/json; charset=utf-8
{"error":"Missing Authorization header."}
```

```json
{
  "error": {
    "message": "The profile description you are looking for does not exist.",
    "reason": "Missing or invalid Authorization header.",
    "tips": "Use Authorization header with <Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJyb2xlcyI6WyJ1c2VyIl0sImZhdm9yaXRlX251bWJlciI6NH0.VP2HoH_HYUFAbdlC827jz1Lr0NQDoyoxIZNztHw6hxQ>."
  }
}
```

