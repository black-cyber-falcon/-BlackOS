# -BlackOS
​A minimal, Arch-inspired Linux distribution running in a sandboxed proot environment on Android. Designed for portability and full user control.
# BlackOS

​Once extracted, you will find the BlackOS/ directory containing the system structure.
​Usage
​To start the system, use your preferred proot command or script.
Example:
proot -0 -r $HOME/BlackOS -b /dev -b /proc -b /sys -w /home/root /bin/bash --login
Features
​Minimalist: A clean environment with only the core essentials.
​Root Access: Full root privileges inside the sandbox.
​Customizable: Follows the DIY philosophy—you decide what to install.
​License
​This project is open-source.
