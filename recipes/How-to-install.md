
### Some errors
- "max virtual memory areas vm.max_map_count [65530] is too low, increase to at least [262144]"
    + Increase by: 
        `sudo sysctl -w vm.max_map_count=262144`

