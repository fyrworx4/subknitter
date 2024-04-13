# subknitter
Quick python script to generate a list of IPs given an octet range and/or comma-separated numbers

Usage:

```bash
python3 subknitter.py 10.10.1-5.7,9
```

Output:

```
10.10.1.7
10.10.2.7
10.10.3.7
10.10.4.7
10.10.5.7
10.10.1.9
10.10.2.9
10.10.3.9
10.10.4.9
10.10.5.9
```
