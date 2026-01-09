## Global Chart
```
curl -X GET "https://charts-spotify-com-service.spotify.com/auth/v0/charts/regional-global-daily/{{yyyy-mm-dd}}" \
  -H "Authorization: Bearer {{YOUR_BEARER_TOKEN}}" \
  -H "App-Platform: Browser" \
  -H "Accept: application/json" \
  -H "Origin: https://charts.spotify.com" \
  -H "Referer: https://charts.spotify.com/" \
  -H "User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/143.0.0.0 Safari/537.36 Edg/143.0.0.0"
  ```

## Country List

```
https://charts-spotify-com-service.spotify.com/auth/v0/charts/regional-{{lower(code)}}-daily/{{yyyy-mm-dd}}
```

```
 "countryFilters": [
        {
            "code": "GLOBAL",
            "readableName": "Global"
        },
        {
            "code": "AR",
            "readableName": "Argentina"
        },
        {
            "code": "AU",
            "readableName": "Australia"
        },
        {
            "code": "AT",
            "readableName": "Austria"
        },
        {
            "code": "BY",
            "readableName": "Belarus"
        },
        {
            "code": "BE",
            "readableName": "Belgium"
        },
        {
            "code": "BO",
            "readableName": "Bolivia"
        },
        {
            "code": "BR",
            "readableName": "Brazil"
        },
        {
            "code": "BG",
            "readableName": "Bulgaria"
        },
        {
            "code": "CA",
            "readableName": "Canada"
        },
        {
            "code": "CL",
            "readableName": "Chile"
        },
        {
            "code": "CO",
            "readableName": "Colombia"
        },
        {
            "code": "CR",
            "readableName": "Costa Rica"
        },
        {
            "code": "CY",
            "readableName": "Cyprus"
        },
        {
            "code": "CZ",
            "readableName": "Czech Republic"
        },
        {
            "code": "DK",
            "readableName": "Denmark"
        },
        {
            "code": "DO",
            "readableName": "Dominican Republic"
        },
        {
            "code": "EC",
            "readableName": "Ecuador"
        },
        {
            "code": "EG",
            "readableName": "Egypt"
        },
        {
            "code": "SV",
            "readableName": "El Salvador"
        },
        {
            "code": "EE",
            "readableName": "Estonia"
        },
        {
            "code": "FI",
            "readableName": "Finland"
        },
        {
            "code": "FR",
            "readableName": "France"
        },
        {
            "code": "DE",
            "readableName": "Germany"
        },
        {
            "code": "GR",
            "readableName": "Greece"
        },
        {
            "code": "GT",
            "readableName": "Guatemala"
        },
        {
            "code": "HN",
            "readableName": "Honduras"
        },
        {
            "code": "HK",
            "readableName": "Hong Kong"
        },
        {
            "code": "HU",
            "readableName": "Hungary"
        },
        {
            "code": "IS",
            "readableName": "Iceland"
        },
        {
            "code": "IN",
            "readableName": "India"
        },
        {
            "code": "ID",
            "readableName": "Indonesia"
        },
        {
            "code": "IE",
            "readableName": "Ireland"
        },
        {
            "code": "IL",
            "readableName": "Israel"
        },
        {
            "code": "IT",
            "readableName": "Italy"
        },
        {
            "code": "JP",
            "readableName": "Japan"
        },
        {
            "code": "KZ",
            "readableName": "Kazakhstan"
        },
        {
            "code": "LV",
            "readableName": "Latvia"
        },
        {
            "code": "LT",
            "readableName": "Lithuania"
        },
        {
            "code": "LU",
            "readableName": "Luxembourg"
        },
        {
            "code": "MY",
            "readableName": "Malaysia"
        },
        {
            "code": "MX",
            "readableName": "Mexico"
        },
        {
            "code": "MA",
            "readableName": "Morocco"
        },
        {
            "code": "NL",
            "readableName": "Netherlands"
        },
        {
            "code": "NZ",
            "readableName": "New Zealand"
        },
        {
            "code": "NI",
            "readableName": "Nicaragua"
        },
        {
            "code": "NG",
            "readableName": "Nigeria"
        },
        {
            "code": "NO",
            "readableName": "Norway"
        },
        {
            "code": "PK",
            "readableName": "Pakistan"
        },
        {
            "code": "PA",
            "readableName": "Panama"
        },
        {
            "code": "PY",
            "readableName": "Paraguay"
        },
        {
            "code": "PE",
            "readableName": "Peru"
        },
        {
            "code": "PH",
            "readableName": "Philippines"
        },
        {
            "code": "PL",
            "readableName": "Poland"
        },
        {
            "code": "PT",
            "readableName": "Portugal"
        },
        {
            "code": "RO",
            "readableName": "Romania"
        },
        {
            "code": "SA",
            "readableName": "Saudi Arabia"
        },
        {
            "code": "SG",
            "readableName": "Singapore"
        },
        {
            "code": "SK",
            "readableName": "Slovakia"
        },
        {
            "code": "ZA",
            "readableName": "South Africa"
        },
        {
            "code": "KR",
            "readableName": "South Korea"
        },
        {
            "code": "ES",
            "readableName": "Spain"
        },
        {
            "code": "SE",
            "readableName": "Sweden"
        },
        {
            "code": "CH",
            "readableName": "Switzerland"
        },
        {
            "code": "TW",
            "readableName": "Taiwan"
        },
        {
            "code": "TH",
            "readableName": "Thailand"
        },
        {
            "code": "TR",
            "readableName": "Turkey"
        },
        {
            "code": "AE",
            "readableName": "UAE"
        },
        {
            "code": "UA",
            "readableName": "Ukraine"
        },
        {
            "code": "GB",
            "readableName": "United Kingdom"
        },
        {
            "code": "UY",
            "readableName": "Uruguay"
        },
        {
            "code": "US",
            "readableName": "USA"
        },
        {
            "code": "VE",
            "readableName": "Venezuela"
        },
        {
            "code": "VN",
            "readableName": "Vietnam"
        }
    ],
    ```
