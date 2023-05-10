# telegram-zero-day-rce-poc
Telegram zero day remote code execution vulnerability discovered in how the telegram client processes svg image attachments regarding XML tags within the svg images. Spawns a reverse shell and connects back to the ip/port that was specified while building the malicious svg file with the poc.py script.

## Instructions
1. command: `python poc.py -f [SVG FILE] -i [IP HERE] -p [PORT HERE]`

## Supported Operating Systems
- Windows
- Linux
