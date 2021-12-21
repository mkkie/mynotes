Variables
```bash
$ awk -v a=0.3 -v b=0.4 "BEGIN {print a+b}"
0.7
```

Getline
```bash
echo -e "line1\nline2" | awk 'BEGIN{ getline; getline; print}'
line2
```