# Web Racer
## Challenge Info

DOWNLOAD LINK: http://chal.ctf-league.osusec.org/websocketracer_server.js
ACCESS: http://chal.ctf-league.osusec.org/websocketracer.html

- Looking at the Javascript source code, your "car" must reach a position of at least 1000 while also clicking the "lock" button, then you will see the flag.
- The distance of your "car" resets every so often

## My Solve
I used [Autohotkey](https://www.autohotkey.com/) for this. I got the idea because I've used Autohotkey in the past for gaming / speedrunning / custom keybinds and macros.

I asked ChatGPT to write me a script.

![](https://media.discordapp.net/attachments/1090136825013747712/1105398259373056070/image.png?width=998&height=670)

![](https://media.discordapp.net/attachments/1090136825013747712/1105398385273475112/image.png?width=995&height=670)

```
$LButton::
Click, 15
Return
```
- Set this to 15 to make sure I get over 1000

![](https://media.discordapp.net/attachments/1090136825013747712/1105400947447959662/image.png?width=700&height=670)

## Video Demo
- With the autoclicker macro set up, just spam click on the Increment Position button.
- Use Tab + Space keys to click Lock Position at close to the same time
- If you get lucky (well there's probably a technique to it but I didn't get that deep), you will get the flag soon.
  - You can record yourself doing this and then play back the video frame by frame in case you only see the flag briefly.
![](https://github.com/solderq35/ctf-writeups/blob/main/web_racer.gif)