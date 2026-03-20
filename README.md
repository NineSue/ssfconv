### 简介
原项目地址 https://github.com/fkxxyz/ssfconv

在原本基础上修正`uint8`结果超过255可能会发生回绕的问题，用int()转一下。

致谢原作者。

### 使用

```shell
 uv venv .venv
 source .venv/bin/activate
 uv pip install pycryptodome pillow numpy
```
```shell 
# 使用示例
./ssfconv -t fcitx5 "/home/sa/project/OpenSource/Amoris.ssf" "catDream"
mkdir -p ~/.local/share/fcitx5/themes/
```