# ebt - easy backup tool
A simple shell script for backup. It speeds up the backup process by compressing your directory or file and uploading it to Google Drive using the drive tool. </br>

**Advice:**
- For now, only zstd can be used.

**Dependencies:**
- tar
- zstd
- drive

**How to unzip?** </br>
Use unzstd: </br>
```unzstd name.tar.zst```

**How to decrease compression level quickly:** </br>
```sed -i -e 's/-15//g' ebt```

Acknowledgements: <br>
drive: https://github.com/odeke-em/drive </br>
zstd: https://github.com/facebook/zstd
