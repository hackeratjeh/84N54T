84N54T
#gunakan tools ini dengan bijak!
clear
figlet "Babang unull""
echo "~~~~~~~~~~~~~~~~~~~~~~~~"
echo "nama :husnul.unull"
echo "sosmed"
echo "@-Babangunull"
echo "fb-Babangunull"
echo "wa-082284790051"
echo
echo
echo "[ pilih nomor yang di inginkan ]"
echo "[1] dark fb"
echo "[2] dark domino island"
echo "[3] dark ig"
echo "[4] stabilkan jaringan"
echo "[5] install bahan"
echo
read -p [ pilih nomor ]>>> "pill
# batas gan
if [ $pill = "1"
then
echo "sedang menginstall..."  ;sleep 2
git clone https://github.com/84N54T.git
cd 84N54T.git
python2 da.py
echo "menginstall selesai [√]"
fi
# batas gan
if [ $pill = "2"
then
ping -s 1000
fi
#batas gan
if [ $pill = "3"
then
echo "sedang menginstall bahan..." ;sleep 2
pkg update && pkg upgrade
pkg install nano
pkg install figlet
pkg install git
pkg install toilet
pip2 install requests mechanize
echo "menginstall selesai [√]"
fi
# batas gan
if [ $pill = "0"
then
echo "thanks jangan lupa kembali :)"
exit
fi
