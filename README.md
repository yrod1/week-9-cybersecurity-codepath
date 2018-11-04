# week-9-cybersecurity-codepath

I deployed three honey pots

1. Dionaea
2. ElasticHoney
3. ShockPot

I encountered every issues that exists and spent way too much time trouble shooting.
I could not get changes made from my terminal to show up on the google cloud although when I accessed them from my terminal they looked correct.
This was resolved by using the google cloud terminal.

I attempted to use the given mhn repository and it was laden with dead dependencies.
I then used threatstream's repository and it worked.

I attempted to access the front page of the server and I could not get to it.
I then when crawling around linux updating outdated dependencies and this never fixed the issues.
After all that work I realized it was settings on my google cloud server that were not in the firewall but in the server itself.
After turning on its ability to be accessed by http I attempted again only to have it fail.
I had damaged the mhn by updating and fiddling with its dependencys so I had to remove everything and start again.
Finally I was able to get this project to work.

Because I was unable to get the terminal to work from my local machine, even when I could see the project, I had to workaround to get the session.json info.
I had to enter the vm, find the data, cat it into the terminal and then copy and paste it.
This project needed a ton of workarounds.


I sustained 162 attacks in about 2 hours.
