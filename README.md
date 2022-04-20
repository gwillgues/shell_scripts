# shell_scripts
A collection of personal shell scripts

# iplookup
This is a simple 1 liner that takes the first argument provided to it ($1), and queries https://ipinfo.io via curl. I found that during day to day use, it took up more time than necessary to type curl and the URL of ipinfo.io every time I needed to look up an IP address ( with more accuracy / different results than a WHOIS query ), so I wrote this and put it in /usr/bin/

Usage: iplookup 8.8.8.8 
Output (2022):
{
  "ip": "8.8.8.8",
  "hostname": "dns.google",
  "anycast": true,
  "city": "Mountain View",
  "region": "California",
  "country": "US",
  "loc": "37.4056,-122.0775",
  "org": "AS15169 Google LLC",
  "postal": "94043",
  "timezone": "America/Los_Angeles",
  "readme": "https://ipinfo.io/missingauth"
}
