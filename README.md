# LinuxFindUtility
A simplified version of the find utility on Linux systems.

This implementation of the find utility allows the user to perform a search fitting various criteria. Any number of criteria may be included in one search.

Implemented criteria include:
  1. find -w <where-to-look>  
  2. find -w <where-to-look> -n <specified name>  
  3. find -w <where-to-look> -m <specified number of minutes>  
  4. find -w <where-to-look> -i <specified i-node number>  
  5. find -w <where-to-look> criteria -d  
          Find files matching the search criteria and delete them. This will not delete folders.
  6. find -w <where-to-look> criteria -e <command>  
          Supported commands include cat, rm, and mv
