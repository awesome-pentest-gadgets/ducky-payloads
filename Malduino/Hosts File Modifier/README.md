Original code from: https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payload---MissDirection (Bucky67GTO)

**Hosts File Modifier**
- Opens CMD as admin
- Changes hosts file ex. 0.0.0.0 www.google.com>>hosts (Changes www.google.com to resolve as 0.0.0.0, so whenever you type www.google.com you're actually going to 0.0.0.0)

**Modified**
- I had to do the special character \ like this (CTRL ALT +). I don't know if this applies to just the Finnish keyboard but my malduino couldn't type the special character as it was. (That's why the script looks little bit junky xD)

**Requirements:**
- Admin Privileges
- Optional: A webserver on that ip address
