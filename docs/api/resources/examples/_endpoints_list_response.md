<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
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
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-14T10:07:04Z",
      "hostport": "3bbd8dbbb675.ngrok.paid:443",
      "id": "ep_2viQ4hbV0AJsYBvlnzPjXlBeKak",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2viQ2IGYUnusF3Q6hkrlz4PG3sO",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://3bbd8dbbb675.ngrok.paid",
      "tunnel": {
        "id": "tn_2viQ4hbV0AJsYBvlnzPjXlBeKak",
        "uri": "https://api.ngrok.com/tunnels/tn_2viQ4hbV0AJsYBvlnzPjXlBeKak"
      },
      "tunnel_session": {
        "id": "ts_2viQ4gXkstmDhBVk2KYSLlFhCAq",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2viQ4gXkstmDhBVk2KYSLlFhCAq"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-14T10:07:04Z",
      "upstream_url": "http://localhost:80",
      "url": "https://3bbd8dbbb675.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-14T10:07:02Z",
      "domain": {
        "id": "rd_2viQ4HCONQ0Pn5ue165kaE2ap16",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2viQ4HCONQ0Pn5ue165kaE2ap16"
      },
      "edge": {
        "id": "edgtls_2viQ4EzDk78HZDl9dciFZH4mBPf",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2viQ4EzDk78HZDl9dciFZH4mBPf"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2viQ4JFcNHTuKSbkgxghAASe4HM",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-14T10:07:02Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
