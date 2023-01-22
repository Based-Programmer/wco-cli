# wco-cli
Enjoy watching Cartoons &amp; Animes from wcostream.net

# Install

#### Linux
- First of all update & install the following [dependencies](#Dependencies) listed below
````
curl -L 'https://github.com/Based-Programmer/wco-cli/raw/main/wco-cli' -O
chmod +x wco-cli
# mv wco-cli /usr/local/bin/
````

#### Termux
```
pkg up -y
pkg in curl fzf nodejs aria2(Optimal, for downloading)
curl -L 'https://github.com/Based-Programmer/wco-cli/raw/main/wco-cli' -O
chmod +x wco-cli
mv wco-cli $PREFIX/bin/
```
- For using this script inside termux u should've mpv-android installed with "user-agent='Mozilla/5.0 (Windows NT 10.0; rv:108.0) Gecko/20100101 Firefox/108.0'" inside Settings/Advanced/'Edit mpv.conf' & no referrer


## Dependencies

- curl
- fzf
- nodejs (for decoding the link)
- mpv (Streaming video)
- aria2 (Optimal, for downloading)
