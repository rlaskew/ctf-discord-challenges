# ctf-discord-challenges
A set of tips and tricks for solving 'Join our Discord' challenges in CTFs


## Why did you make this page?
I noticed lots of people in discord (including me) struggle or spend more time then necessary on these challenges, and there is a github or other guide for every other type of challenge/tool/technique in cybersecurity. 

## contributing
(WIP) If you want to contribute, create fork, then a new-branch, then pull request -- only README.md changes will be accepted

## Tip: Read things carefully
Including each tip below and the CTF rules. 

## Tip: Use ChatGPT
Remember to use ChatGPT or similar for tips and tricks not covered here

## Tip: Check the Rules, then check them again on Discord
Frequently rules are posted on the web, then again on Discord, frequently worth another look.

## Tip: Check the Rules Again -- sometimes the CTFs have multiple flag formats 
for example, one CTF I played in multiple flag formats:   ABCD{real_flag} and ACBD{different_real_flag}

## Tip: Make sure to read the FULL Discord Channel Descriptions 
Sometimes the only way to get the full text of the description is to browse the channel and see the dialog when you hover over the description at the top of the pages as a TOOLTIP !! 

## Tip: Try leaving the discord server and rejoining
Sometimes you'll see something you had not noticed previously

### TODO: Text to incorporate
Common Places to Search in Discord for Flags
1. Pinned Messages
Check the pinned messages in every channel. Flags or hints are often pinned by admins or bots.

2. Channel Descriptions (Topics)
Hover over or click the channel name to see the topic or description — flags or partial flags may be embedded here.

3. Discord Server Description / Welcome Channel
The server’s welcome message, rules, or about section may contain flags or links to them.

4. Message History
Skim older messages, especially from admins, bots, or challenge creators. Use search to look for keywords like:

flag

CTF

ctf{, flag{, etc.

5. Bot Commands / Interactions
Interact with bots using common commands like !help, !flag, !ctf, etc.

Look for hidden outputs, easter eggs, or bot DMs.

6. File Attachments
Check uploaded files, such as images, PDFs, zip files.

Try exiftool, strings, or binwalk on images and documents.

7. Hidden Markdown or Spoilers
Some flags may be hidden using:

||spoiler tags||

Small font (Unicode tricks)

Invisible characters

Empty lines (scroll up)

8. Voice Channel Names
Some servers hide flags in the names of voice channels or their descriptions.

9. Emojis or Reactions
Check for custom emojis named like :flag: or :ctf:.

Reactions on specific messages might reveal something — hover to see user names or try replicating the behavior.

10. User Profiles
Look at the profile descriptions, custom statuses, or bios of admins or bots.

11. Discord Invite Links / External Links
Flags may be at the other end of an external link, possibly leading to a:

Website with a hidden path or JS

Pastebin/Gist

Another Discord server

12. Channel Permissions
Sometimes hidden channels appear after you complete an action or role.

Try emoji-react role selection or solve an initial puzzle to unlock more channels.

🧠 Pro Tips
Use Ctrl+F or Discord’s search to look for keywords like flag, ctf{, or }.

Some servers may embed flags using Zero Width Characters, Base64, or other encoding methods.

Try asking bots or people suspiciously too helpful.

Join the server using a browser and mobile app — sometimes the UI varies and reveals different things.

If you’re allowed to, and you’re stuck, you can share the server’s general structure (without leaking anything private), and I can help narrow down your search.
