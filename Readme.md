## Digital clock Bash Script
```bash
#!/bin/bash

clear
while true; do
    clear
    echo -e "\n\n\t\t$(date +"%H:%M:%S")"
    sleep 1
done
```
