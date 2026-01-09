```
curl -X GET "https://charts-spotify-com-service.spotify.com/auth/v0/charts/regional-global-daily/{{yyyy-mm-dd}}" \
  -H "Authorization: Bearer {{YOUR_BEARER_TOKEN}}" \
  -H "App-Platform: Browser" \
  -H "Accept: application/json" \
  -H "Origin: https://charts.spotify.com" \
  -H "Referer: https://charts.spotify.com/" \
  -H "User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/143.0.0.0 Safari/537.36 Edg/143.0.0.0"
  ```
