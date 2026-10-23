# What is new

These notes are written in plain words for people who use Atashi, not for developers. They cover what you will notice.

## 1.0.14

- A folder you add to a project shows up in the folder card straight away, just like a removal does.
- The app is stricter about where an agent may write: a project's write access can no longer be pointed outside the folders you gave it.

## Earlier releases

### Work mode is now your choice
- Work mode starts switched off for every profile. The first time you press Work, Atashi asks one plain question: it will open your own AI assistant (Claude Code, Codex or Gemini) on this computer with your sign in, and asks whether to turn Work on. Yes turns it on and it stays on for your profile. Not now leaves it off. Talk is not affected.
- A switch for Work is in Settings, so you can change your mind later.

### Working with your team on your computer
- When a plan needs a tool, you now get a clear card asking to connect it. It only opens a safe sign in address, any key field is optional, and saying No clears anything you typed.
- The approval card names the engine the plan will really run on.
- The Yes on a plan tells you which tools it lets run on your computer, and names any tool that can make changes apart from tools that only read.
- The card keeps showing the connections your plan uses, even after you say Yes.
- A project folder inside a larger git checkout with several worktrees no longer stops with "could not check this project's git settings" at the Read only and Edit files in this folder levels.

### Rooms
- When a room run is refused, you get a plain sentence instead of raw text, and a plan that can no longer run does not offer Try again.
- A run that failed no longer stays marked as working, and Stop clears it.
- Open plans load when you open a room and when a turn ends.
- A reviewer in a team plan waits for the teammates whose work it needs to check, so it does not report on work that does not exist yet. This now also holds for plans an agent raises itself.
- Approving a plan in a room runs it in the room's project folder.
- A plain question or a one off ask in a room is no longer kept as a standing order, so it does not come back later as an open request.
- Saving memories after a room turn no longer holds up the end of the reply.

### Chat
- Opening an agent from the side rail takes you to its newest chat in the project you are in, and the project is kept.
- Leaving a direct message no longer cancels the send that starts an approved run.
- A card raised while a desktop run is going shows up when the run ends, without a reload.

### Atashi Desktop
- If Atashi Desktop closes unexpectedly, its background helper now closes with it instead of staying open.

### Phone
- When an agent asks a question with options, you can answer it from the Office on your phone, with larger buttons, one answer per press, and your typed draft kept.

### Settings
- The Talk picker shows what a turn will really use.
- Connections explains when a command was not approved on your computer.

### Team and activity
- A waiting card you have dealt with leaves the list and the count.
- The project picker uses the same colours as the rest of the app.

If anything here is not in your version, the download page shows which version is current.
