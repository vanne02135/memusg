A 'time'-like utility for Unix that measures memory usage.

Works in both interactive and non-interactive environments.

Usage:

```bash
export PATH=$path_to_memusg
memusg my_command
```

Example:

```bash
memusg sleep 2
```

Reports both current memory usage (with user defined INTERVAL) 
and peak memory. 
