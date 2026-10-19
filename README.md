# Atashi Desktop

Atashi is a team of AI agents that remember you and do real work. Atashi Desktop is the app that lets that team work on your own computer, where your files already are, without you running a terminal.

- Website and downloads: https://atashi.com.au/desktop-app.html
- The same installers are also on this repository's Releases page, with a SHA256SUMS.txt file. These are the only two places to download Atashi Desktop from.
- Works on Windows and Linux. A Mac app is coming.
- This repository holds the setup instructions. The installers are attached to its Releases, not stored in the files. There is no source code here.

## Set it up with your own AI assistant

If you already use an AI coding assistant, such as Claude Code, you can have it walk you through the install. Open SETUP.md, copy the prompt in it, and paste it into your assistant. It will ask for your yes before every step. You stay in control, and nothing happens without your answer.

If you prefer to do it yourself, go to the download page above, pick your system, and check the SHA 256 checksum shown beside the download before you open it. If you download from the Releases page instead, the checksum must also match the one in SHA256SUMS.txt.

## What to know before you install

- The download page is the source of truth for the current version and its checksum. The files in this repository never repeat a checksum, so they can never be out of date. The checksum must match on the download page and in SHA256SUMS.txt. If the two differ, stop and do not install. A matching checksum catches a broken download. It cannot, by itself, prove the website or this account was not tampered with, because both are published by us.
- The Windows build is not yet code signed, so Windows will show a warning. The download page explains it. Only continue if you got the file from the download page or from this repository's Releases.
- Atashi never installs updates by itself. The app tells you when a new version exists, and you come back to the download page.
- The Robotics team, which flies a simulated drone and works with robot software, needs Linux (Ubuntu is the one we test on), plus the Gazebo simulator and ROS 2 installed on your computer. The desktop app does not install those for you yet.

## Who we are

Atashi.com.au Pty. Ltd., Sydney, Australia. Questions or problems: use the contact details on https://atashi.com.au.

Atashi is an independent product. It is not made by, endorsed by or partnered with Anthropic or any other AI company whose assistant you may choose to use with it.
