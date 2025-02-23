Simple Tampermonkey (https://www.tampermonkey.net/) script to remove fallback ads on Tweakers.net

1. install tampermonkey in your browser
2. make a new userscript and copy the content of script into it, enable it
3. ...
4. profit

Tweakers thankfully includes a little ::before element with the word "Advententie"
We can look for this with tampermonkey and delete the surrounding div

You will see the ad load at first, but because the script runs every 0.5 seconds, it is deleted quickly
