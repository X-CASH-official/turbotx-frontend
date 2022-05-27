# turbotx-frontend
turbo tx frontend

If running the tool locally just open the `index.html` file in a web browser

If running on a server, install nginx using `apt install -y nginx` and then copy the `index.html` to the `/var/www/html/` directory `cp -a index.html /var/www/html/`

Note: This tool was designed to run on the official website or a locally without a webserver. If you want to run it on your own server you will need to change this line, and add your servers IP/domain instead of our IP/domain  
`const URL = location.hostname === "localhost" || location.hostname === "127.0.0.1" || location.hostname === "" ? "http://127.0.0.1:8000" : "http://162.55.235.87";`  
https://github.com/X-CASH-official/turbotx-frontend/blob/main/index.html#L212
