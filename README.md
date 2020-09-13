# URL-Shortener-Microservice
## Working URL: https://URL-Shortener-Microservice.priyabihani.repl.co

This project is a part of my FreecodeCamp Microservies certification .

1) I can POST a URL to [project_url]/api/shorturl/new and I will receive a shortened URL in the JSON response.
Example : {"original_url":"www.google.com","short_url":1}
2)If I pass an invalid URL that doesn't follow the http(s)://www.example.com(/more/routes) format, the JSON response will contain an error like {"error":"invalid URL"}
3)When I visit the shortened URL, it will redirect me to my original link.
