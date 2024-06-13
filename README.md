##这是一个基于RPC的分布式通信框架，编译请按如下步骤：

mkdir build

cd build

cmake ..

make

##运行：

cd bin

./provider -i test.conf

./consumer -i test.conf
