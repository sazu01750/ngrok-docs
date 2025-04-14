<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"x-frontend":"ngrok"},"enabled":true,"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2viQ5MrVGiQh3UHUj3LIeZgZtgW/routes/edghtsrt_2viQ5ORqT19uGynhoWMQhqYfgWe/request_headers
