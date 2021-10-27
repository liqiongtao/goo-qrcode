# 字节

```
buf, err := qrcode.New("http://googo.io").Get()
```

# base64

```
b64img, err := qrcode.New("http://googo.io").Base64Image()
if err != nil {
}
```

# 输出图片

```
err := qrcode.New("http://googo.io").Output(c)
if err != nil {
}
```
