flask qrcode service demo
===========================

Just a simple demo of qrcode generate service!

url with params => return png response

### deploy

```
pip install -r requirements.txt

python run.py

#http://127.0.0.1:8000/qrcode?data=http://www.baidu.com&ecl=H&v=1&border=1&size=200
```

### dependency

- [flask](https://github.com/mitsuhiko/flask)
- [python-qrcode](https://github.com/lincolnloop/python-qrcode)
- [pillow](https://github.com/python-pillow/Pillow)


