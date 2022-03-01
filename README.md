# superintendent.me
superintendent.me website code, 




# deplyoing
If for some Reason you want to rebrand and Change some Files, go for it, it is entirely made out of HTML And CSS so far, So it is quite simple

so first of all, install your webserver if you dont already have one
Commands will be based off of Ubuntu 20.04 lts

```
sudo apt install apache2
```
then go to your html directory, normally it is
```
/var/www/html/
```
Then Put the code inside of there, then go to the ip address of the server your hosting it on like 127.0.0.1 or localhost:80 and there you go, You have it!
for the .htaccess remove everything before the .htaccess, github doesnt allow me to upload hidden files

# Support
No, their is none, Unless I feel like paying attention to the issues of this repo. So have fun!
# cloudflare
To setup this sites code, you will want to buy a domain, and a VPS. then set up an cloudflare account and add a website, add in your domain name and then with the domain Holder, like godaddy, you want to change the namme servers to what cloudflare says to, once the TTL refreshes you should be able to setup dns setting using an A record to your VPS ip,
