
To symlink to /usr/local/bin:
```bash
find . -type f -not -path "./README.txt" -maxdepth 1 -execdir ln -s "$(pwd)/{}" /usr/local/bin \;
```

Dependencies:

ygm
---
- ffmpeg
- you-get

gif
---
- ffmpeg
