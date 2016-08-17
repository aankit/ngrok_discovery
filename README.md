###Installation

Download and unzip ngrok into the directory you want to work in. In the command line, run the following commands to download and unzip ngrok

```
curl "https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-darwin-amd64.zip" -o grok-stable-darwin-amd64.zip
unzip -u grok-stable-darwin-amd64.zip
```

If you aren't on the command line yet, open up Terminal, `cd to the directory that ngrok unzipped into and run:

`./ngrok http 8080`


You should see an ngrok _dashboard_ with a bunch of info. Make sure that your tunnel status is online. If not, try a different port or consult this [useful documentation courtsey of github](https://developer.github.com/webhooks/configuring/#using-ngrok)

Copy and paste the url that appears on the line that looks like this:

`Forwarding                    http://[unique random numbers and letters here].ngrok.io -> localhost:8080`  

Open a new terminal tab and run:

`python -m SimpleHTTPServer 8080`


