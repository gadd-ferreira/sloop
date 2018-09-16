# sloop
sLoop: Loops the cursor around the screen when it reaches an horizontal edge


## Installation
```bash
curl -L https://github.com/gadd-ferreira/sloop/raw/master/dist/sloop -o /tmp/sloop && chmod +x /tmp/sloop && sudo mv /tmp/sloop /usr/local/bin/
```


## Usage



Manually with



```bash
sloop&
```



Automatically with .xinitrc
```bash
echo 'sloop&' >> ~/.xinitrc
```