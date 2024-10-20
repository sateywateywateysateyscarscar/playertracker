# Player Tracker

The GtagTracker is the dependencies, The main.py is where the code goes

Main.py Code:

```
import GtagTracker
import os

def clear():
    os.system('cls')

def main():
    steamticket = "U not getting my steam ticket buddy."
    Codes = input('Code: ').split(',')
    GtagTracker.login_stuff(steamticket, Codes)
    input('Done. Press Enter To Do It Again.')
    clear()
    main()

main()
```
