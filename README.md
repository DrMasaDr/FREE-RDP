**FREE RDP/VPS FOR FREE ALL TIME MADE FOR EGYPT BY DXD MASA**

> MY WEBSITE FOR ALL TOOL [DXD PRO](https://dxdpro.blogspot.com/).
> DOWNLOAD NOMACHINE FOR RUN [NOMACHINE ](https://www.nomachine.com/).
> SIGN UP FOR NGROK TO RUN [NGROK ](https://dashboard.ngrok.com/).


### How to Install
```
COPY THIS CODE IN
https://shell.cloud.google.com/?fromcloudshell=true&show=terminal&pli=1 

```
```
      wget -O ng.sh https://github.com/DrMasaDr/FREE-RDP/raw/main/ngrok.sh > /dev/null 2>&1
chmod +x ng.sh
./ng.sh


function goto
{
    label=$1
    cd 
    cmd=$(sed -n "/^:[[:blank:]][[:blank:]]*${label}/{:a;n;p;ba};" $0 | 
          grep -v ':$')
    eval "$cmd"
    exit
}

: ngrok
clear
echo "Go to: https://dashboard.ngrok.com/get-started/your-authtoken"
read -p "Paste Ngrok Authtoken: " CRP
./ngrok authtoken $CRP 

clear
echo "Repo: https://github.com/DrMasaDr/FREE-RDP"
echo "======================="
echo "choose Server."
echo "======================="
echo "us - United States (Ohio)"
echo "eu - Europe (Frankfurt)"
echo "ap - Asia/Pacific (Singapore)"
echo "au - Australia (Sydney)"
echo "sa - South America (Sao Paulo)"
echo "jp - Japan (Tokyo)"
echo "in - India (Mumbai)"
read -p "choose ngrok region: " CRP
./ngrok tcp --region $CRP 4000 &>/dev/null &
sleep 1
if curl --silent --show-error http://127.0.0.1:4040/api/tunnels  > /dev/null 2>&1; then echo OK; else echo "Ngrok Error! Please try again!" && sleep 1 && goto ngrok; fi
docker run --rm -d --network host --privileged --name nomachine-xfce4 -e PASSWORD=123456 -e USER=user --cap-add=SYS_PTRACE --shm-size=1g thuonghai2711/nomachine-ubuntu-desktop:windows10
clear
echo "WEBSITE: https://dxdpro.blogspot.com/"
echo https://t.me/DXDPRO:
echo IP Address:
curl --silent --show-error http://127.0.0.1:4040/api/tunnels | sed -nE 's/.*public_url":"tcp:..([^"]*).*/\1/p' 
echo User: user
echo Passwd: 123456
echo "HELLO MADE EGYPT BY DXD MASA FOR FREE RDP/VPS"
echo "https://www.facebook.com/DXDMASA/"
echo "https://www.instagram.com/dxd_masa/"
echo "https://www.facebook.com/Masaaofficial"
echo "https://t.me/DXD_PRO"
echo "https://t.me/program_masa"
seq 1 43200 | while read i; do echo -en "\r Running .     $i s /43200 s";sleep 0.1;echo -en "\r Running ..    $i s /43200 s";sleep 0.1;echo -en "\r Running ...   $i s /43200 s";sleep 0.1;echo -en "\r Running ....  $i s /43200 s";sleep 0.1;echo -en "\r Running ..... $i s /43200 s";sleep 0.1;echo -en "\r Running     . $i s /43200 s";sleep 0.1;echo -en "\r Running  .... $i s /43200 s";sleep 0.1;echo -en "\r Running   ... $i s /43200 s";sleep 0.1;echo -en "\r Running    .. $i s /43200 s";sleep 0.1;echo -en "\r Running     . $i s /43200 s";sleep 0.1; done
```
```
```
```
```
```
DOWNLOAD GOOGLE CHROME COPY AND PAST IN TERMINAL

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo dpkg -i google-chrome-stable_current_amd64.deb

```
```
```
```
```
```
SETUP EXE FILE ON RDP/VPS

PAST THIS CODE IN TERMINAL

apt-get install wine32:i386
AND 
wine the file exe .exe
```
```
```
```
```
```
IF YOU GET ANY PROBLEM

PAST THIS CODE IN TERMINAL

apt-get install wine32:i386
sudo apt-get update -y
apt-get full-upgrade -y
```
```
```
## CONTACT ME ON

1.<a href="MY FACEBOOK">https://www.facebook.com/DXDMASA/</a> <br>
2.<a href="MY FACEBOOK PAGE">https://www.facebook.com/Masaaofficial</a> <br>
3.<a href="MY INSTAGRAM">https://www.instagram.com/dxd_masa/</a> <br>
4.<a href="MY TELEGRAM">https://t.me/DXDPRO</a> <br>
5.<a href="MY TELEGRAM">https://t.me/Dr_Masa_Dr</a> <br>
6.<a href="MY PAGE">https://t.me/DXD_PRO</a> <br>
7.<a href="MY PAGE">https://t.me/program_masa</a> <br>
8.<a href="MY TWITTER">https://twitter.com/DXDMASA</a> <br>

