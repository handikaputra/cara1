wget https://github.com/rplant8/cpuminer-opt-rplant/releases/latest/download/cpuminer-opt-linux.tar.gz

tar xf cpuminer-opt-linux.tar.gz

while [1];do ./cpuminer-sse2-a yespowerres-o stratum+tcp://stratum-eu.rplant.xyz:17040 -u walet.nama -t1
sleep 2
done
