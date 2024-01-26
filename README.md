# Browser-Fingerprinting
Simple Frontend Browser Fingerprinting

## Usage
Simply include `finger.js` in your web frontend and check `F12` => `Console`. 

## Result
Best-case you'll receive this. Might not be accurate - commercial fingerprinting libraries are huge and cost up to 500€ / months, so what gives... 

```javascript
{
  "userAgent": "Mozilla/4.0 (Windows NT 15.0; Win44; x14; rv:1141.0) Gecko/2345346 Firefox/23523.0",
  "webGL": "ANGLE (NVIDIA, NVIDIA GeForce RTX 9900MAXULTRA Direct3D19 vs_1_1 ps_1_1)",
  "canvas": 34634654603,
  "audio": 3453075474574,
  "clientRects": -346243870,
  "timezone": "Europe/Berlin",
  "localTime": "Fri Jan 26 2024 23:04:43 GMT+0100 (Mitteleuropäische Normalzeit)",
  "systemTime": "2024-01-26T22:04:43.479Z",
  "languages": "de, en-US, en",
  "browserFeatures": {
    "javascript": "Enabled",
    "flash": "Disabled",
    "activeX": "Enabled",
    "java": "Disabled",
    "cookies": "Enabled"
  },
  "browserDetails": {
    "browser": "Mozilla/4.0 (Windows NT 15.0; Win44; x14; rv:1141.0) Gecko/2345346 Firefox/23523.0",
    "platform": "Win2"
  },
  "cookies": [
    {
      "name": "uniqueVisitorId",
      "value": "visitor_17023523520"
    }
  ]
}
```
