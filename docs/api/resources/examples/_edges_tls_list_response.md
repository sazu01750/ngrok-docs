<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-14T10:07:12Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2viQ5dBLxxw1NPnOYJ3EzyNXPG0",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2viQ5dBLxxw1NPnOYJ3EzyNXPG0"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2viQ4ISRspeNiXwZBuT5RhYpr8w",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2viQ4ISRspeNiXwZBuT5RhYpr8w"
        },
        "enabled": true
      },
      "created_at": "2025-04-14T10:07:01Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2viQ4EzDk78HZDl9dciFZH4mBPf",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2viQ4EzDk78HZDl9dciFZH4mBPf"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
