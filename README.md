 #usr/bin/bash
clear
bi='\033[34;1m' #biru
i='\033[32;1m' #ijo
pur='\033[35;1m' #purple
cy='\033[36;1m' #cyan
me='\033[31;1m' #merah
pu='\033[37;1m' #putih
ku='\033[33;1m' #kuning
#MAKASIH YANG DA BANTU
clear
echo
echo
echo
echo $i" ASSALAMUALAIKUM $i"
echo $i" DAFFA HAUZAN NST $i"
echo
echo $i"██████████████████████████████████████████████
echo $i"|"$me" 1"$i" |"$cy" DARK FB                       "$i"|"$i"
echo $i"|"$me" 2"$i" |"$cy" script mantap                 "$i"|"$i"
echo $i"|"$me" 3"$i" |"$cy" Install bahannya              "$i"|"$i"
echo $i"|"$me" 4"$i" |"$cy" Exit                          "$i"|"$i" 
echo $i"██████████████████████████████████████████████
echo
#maaf yaa sikit script
echo "["$i""Pilih Nomornya""$bi"]"
         ╔═════╝
read -p" ╚══─} " pil

if [ $pil = 1 ]
then
clear
figlet -f slant "W A I T"|lolcat
sleep 1
git clone https://github.com/rezadkim
cd TAIK
python2 run.py
fi

if [ $pil = 2 ]
then
clear
figlet -f slant "W A I T"|lolcat
sleep 1
git clone https://github.com/daffahauzannst/MANTAB-JIWA-WOI
cd MANTAB-JIWA-WOI
sh README.md
fi

if [ $pil = 3 ]
then
clear
apt update && apt upgrade
apt install python2
pip2 install mechanize
pkg install ruby
gem install lolcat
pkg install git
pkg install php
figlet -f slant " MANTAP "|lolcat
fi

if [ $pil = 4 ]
then
clear
figlet -f slant "E X I T"|lolcat
sleep 2
echo $cy"TERIMA KASIH TEMAN TEMAN"
sleep 2
echo $i"Bila Ada Kesalahan Kamu Bisa Nanya Kepada Saya"
sleep 2
echo $ku"WhatsApp :"$i" 0882 6147 4586"
echo $ku"Facebook :"$i" DAFFA NST"
sleep 2
echo $pur">> MAKASIH ASSALAMUALAIKUM <<"
echo $cy"BANG DY AKU DA BUAT SCRIPT"
exit
fi
