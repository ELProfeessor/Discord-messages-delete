 This Script will wipe your messages and skip deleting your messages in channels or DMs you pick
 
 Supports multiple conversations to keep (Just add more IDs to EXCLUDED_CHANNEL_IDS)
 Automatically skips those conversations while deleting everything else


🔹 How to Use It

    Find All the DM/Channel IDs You Want to Keep
        Open index.json
        Find "Direct Message with [username]"
        Copy the number next to it (That’s the DM Channel ID).
        Paste it into the EXCLUDED_CHANNEL_IDS list.

    Get Your Discord Token
        Open Discord in your browser
        Press F12 → Go to Network → Find an API request
        Copy your Authorization token
        Replace "YOUR_DISCORD_TOKEN" in the script with your token.

    Run the Script in Your Browser Console
        Open Discord.com in Chrome or Firefox
        Press F12 → Go to Console
        Paste the script and press Enter
If you don’t want to use index.json to find DM/Channel IDs, you can find them directly from Discord using Developer Mode. Here’s how:
🔹 Finding a DM Channel ID (for Private Messages)

    Enable Developer Mode
        Open Discord.
        Go to User Settings → Advanced.
        Toggle Developer Mode ON.

    Get the Channel ID for a Direct Message
        Open your DM with the person (e.g., Friend).
        Right-click anywhere in the chat window.
        Click Copy Channel ID.
        Paste it somewhere (that’s the DM’s unique ID).

🔹 Finding a Channel ID (for Servers)

    Open the server where the channel is located.
    Right-click on the channel name (in the left sidebar).
    Click Copy Channel ID.

🔹 Finding a User ID (If Needed)

    Right-click on the user’s profile (in chat or member list).
    Click Copy User ID.

🔹 What You Need for the Script

    For DMs → Use DM Channel IDs
    For Server Messages → Use Channel IDs
