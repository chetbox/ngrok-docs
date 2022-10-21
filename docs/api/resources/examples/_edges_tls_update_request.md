
#### Example Request

```bash 
curl \
-XPATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"environment\": \"production\"}"}' \
https://api.ngrok.com/edges/tls/edgtls_2EmMQDNFUwrhyqRdTmWwUoJNEMN