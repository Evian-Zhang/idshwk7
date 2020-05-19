# IDS Homework 7

## 相关文件

* `base.png`<br />用于作载体的图片
* `secret.txt`<br />姓名和学号的文本文件
* `result.png`<br />隐藏后的图片
* `extract.txt`<br />从隐藏后的图片中提取的信息
* `LSBSteg.py`<br />用于隐藏的代码，来自[RobinDavid/LSB-Steganography](https://github.com/RobinDavid/LSB-Steganography)

## 步骤

1. 隐藏文件

    ```console
    LSBSteg.py encode -i base.png -o result.png -f secret.txt
    ```

2. 提取信息

    ```console
    LSBSteg.py decode -i base.png -o extract.txt
    ```

    