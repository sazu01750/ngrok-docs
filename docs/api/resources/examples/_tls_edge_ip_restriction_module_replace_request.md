<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2viQ5badSt051f3WaavnR2UbVDg","ipp_2viQ5dq8hBhlw9n3elnLbMRYmQu"]}' \
https://api.ngrok.com/edges/tls/edgtls_2viQ5fIKb8oMEqdCHPj7AbjJVye/ip_restriction
