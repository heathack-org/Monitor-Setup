# Monitor-Setup
html for setting up one of our thermal monitors

This is just a test so far - for our current thermal monitors, connect to 192.168.4.1 on the monitor itself.

The idea behind this code is that the monitor user can load HTML from the internet, then connect to the monitor's access point instead, and submit the form.  That gives them as much time as they want to type an SSID and password, and removes the step of browsing to 192.168.4.1 - an unfamiliar skill to many, where they end up searching instead.

We don't know if they'll accept typing an SSID and password into a website form, even if they aren't submitting it to anything on the web. 

We're also not sure if we can disable the submit button if they have an internet connection, but it would be handy if we could.  Users are often confused about where they are connected because many devices will do anything to avoid lack of access.  If they are still connected to the internet, we could perhaps trigger another page here to appear to tell them they made a mistake.
