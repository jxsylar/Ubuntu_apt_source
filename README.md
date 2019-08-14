# Ubuntu 修改 apt 源

清华源: https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/  
阿里云源: https://opsx.alibaba.com/guide?lang=zh-CN&document=69a2341e-801e-11e8-8b5a-00163e04cdbb

```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.bak
sudo apt edit-sources  # or  sudo vi /etc/apt/sources.list
sudo apt update
```
