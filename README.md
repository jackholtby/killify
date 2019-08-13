# killify

### What it does
A very short script to run when an ad comes on in Spotify desktop client (on Linux currently)
The script runs as follows.
1. Finds the process IDs of all processes that have "spotify" in their description
2. It then creates a text file with "kill" before each PID.
3. It makes the file executable, runs it, and then deletes it.
4. Spotify is then run again.

