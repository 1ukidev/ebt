# ebt - easy backup tool
A simple shell script for backup. Speeds up backup process by compressing your directory or file and uploading to Google Drive.</br>

**Dependencies:**
- tar
- zstd (https://github.com/facebook/zstd)
- drive (https://github.com/odeke-em/drive)

**How to unzip?**</br>
```unzstd <name>.tar.zst```</br>
```tar xf <name>.tar``` 

**How to decrease compression level quickly:**</br>
```sed -i 's/-15//g' ebt```
