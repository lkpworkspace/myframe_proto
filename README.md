# proto
myframe's communication protocol

# 依赖
- myframe框架 https://github.com/lkpworkspace/myframe
    - myframe框架的编译安装可以参考myframe的README
- protobuf
    ```sh
    sudo apt-get install protobuf-compiler libprotobuf-dev
    ```
# 安装
```sh
git clone https://github.com/lkpworkspace/proto.git
cd proto && mkdir build && cd build
cmake .. && make install
```
