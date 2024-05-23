تست سرعت سرور مجازی


روش یک



````
wget https://install.speedtest.net/app/cli/ookla-speedtest-1.2.0-linux-x86_64.tgz
````

````
tar -xvzf ookla-speedtest-1.2.0-linux-x86_64.tgz
````

````
chmod +x speedtest
````

````
./speedtest
````

````
./speedtest --server-id=55462
````
````
./speedtest --server-id=53619
````
روش دوم

````
wget -qO- bench.sh | bash
````


روش سوم

````
sudo apt-get remove speedtest-cli
````

````
sudo apt-get install curl
````

````
curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash
````

````
sudo apt-get install speedtest
````

````
speedtest --server-id=55462
````


روش چهارم:

````
apt install iperf3
````

````
iperf3 -s
````

````
iperf3 -c ipserverkharej -i 1 -t 10  -P 20
````


````
iperf3 -c ipserverkharej -R -i 1 -t 10 -P 20
````

