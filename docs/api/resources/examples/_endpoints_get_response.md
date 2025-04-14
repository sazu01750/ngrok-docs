<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-14T10:07:06Z",
  "description": "sample cloud endpoint",
  "domain": {
    "id": "rd_2viQ4HCONQ0Pn5ue165kaE2ap16",
    "uri": "https://api.ngrok.com/reserved_domains/rd_2viQ4HCONQ0Pn5ue165kaE2ap16"
  },
  "hostport": "endpoint-example2.com:443",
  "id": "ep_2viQ4uAfxNkLMvetsYGFa0Q1iZY",
  "metadata": "{\"environment\": \"staging\"}",
  "pooling_enabled": false,
  "proto": "https",
  "public_url": "https://endpoint-example2.com",
  "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
  "type": "cloud",
  "updated_at": "2025-04-14T10:07:06Z",
  "uri": "https://api.ngrok.com/endpoints/ep_2viQ4uAfxNkLMvetsYGFa0Q1iZY",
  "url": "https://endpoint-example2.com"
}
