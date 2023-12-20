If you want to see what if your UUID/HWID type ``wmic csproduct get uuid`` in CMD 
-- How it Works --

1. The script fires up the WMIC command using the `io.popen` function.
2. It then grabs the UUID from the output and trims it down to the key part.
3. Next, it checks if the obtained UUID matches the one it's expecting.
4. If not, it politely lets you know that you don't have the green light to run the trainer.
5. In that case, the script gracefully closes down Cheat Engine (CE).


THIS SCRIPT WAS NOT MADE BY ME, Thanks for Victory™ and AhmadBTT aka GamingAET
