# ebt - easy backup tool
A simple shell script for backup. Speeds up backup process by compressing your directory or file and uploading it to Google Drive using "drive". </br>

**Advice:**
- For now, only zstd can be used.

**Dependencies:**
- tar
- zstd
- drive

**How to unzip?** </br>
```unzstd name.tar.zst``` </br>
```tar -xvf name.tar``` 

**How to decrease compression level quickly:** </br>
```sed -i -e 's/-15//g' ebt```

Acknowledgements: <br>
drive: https://github.com/odeke-em/drive </br>
zstd: https://github.com/facebook/zstd
