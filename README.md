<div align="center">

<h1> Cosmos Nodeların Yedeğini Almak </h1>

  <h3>
  
Herhangi bir sorunla karşılaşırsanız Telegram Sohbet Grubumuza bekleriz [Core Node Chat](https://t.me/corenodechat)
  
</h3>
  
</div>

<br>

Özet: Sunucuna bağlan, nodeun dosyalarını bul örnek (root/.nibid/config/), Yedekleme işlemini yap.
Bunu 2 Programla göstericem.
1) Winscp
2) MobaXterm


<details>
      
<summary> <h1> Winscp ile yedekleme </summary> </h1>

  <h2>
    [WinScp İndirme Linki](https://winscp.net/eng/download.php)
  </h2>
  
## Önce Sunucumuza bağlanalım. İşaretlediğim yerlere sunucu bilgilerini girin ve sunucunuza bağlanın.

Eğer sunucuya bağlanırken private key dosyası kullanmıyorsanız 2. adımı es geçin.

![image](https://user-images.githubusercontent.com/76253089/223129569-e26ca533-89e1-4a13-b210-2a58b58b8480.png)

## Sunucunuza bağlandığınızda sizde daha az dosya gözükecektir. Ctrl + ALT + H tuşlarına aynı anda basın ve gizli dosyaları açın.
Bende gördüğünüz gibi .nibid ve .quasarnode klasörleri açığa çıktı.

![image](https://user-images.githubusercontent.com/76253089/223130530-169912b1-6910-45f8-8b33-dc35bd0b2625.png)

## .nibid sonra config içerisine girince priv_validator_key.json dosyasını göreceksiniz onu masaüstünüze çek bırak yapın ve işlem bu kadar.

![image](https://user-images.githubusercontent.com/76253089/223457002-53c8af94-4949-4ce9-8fd6-9a95f402bfde.png)

  </details>
  
  <details>
      
<summary> <h1> MobaXTerm ile Yedeklemek </summary> </h1>
  
  <h2> [MobaXterm İndirme Linki](https://mobaxterm.mobatek.net/) </h2>

## MobaXtermi indirip bilgisayarımıza kuralım. Sonrasında Altta gösterdiğim yerlere tıklayıp sunucu bilgilerimizi girelim.
  
 3. Adımda Private keyiniz varsa işaretlediğim yerden dosyanızı seçin. Eğer private key yerine şifre ile bağlanıyorsanız bu adımı geçin. Sunucu şifrenizi sunucuya bağlanırken soracak.
  
  ![image](https://user-images.githubusercontent.com/76253089/223460884-06140b98-4426-470e-a8e4-b972abbc0475.png)

## İşaretlediğim sembole basıp gizli dosyalarımızı açığa çıkartalım. Gördüğünüz gibi .nibid klasörü açığa çıktı 
  
  ![image](https://user-images.githubusercontent.com/76253089/223461646-b2f628f0-465a-44a2-8d8c-dcddce310d1f.png)

## .nibid / config / dosyalarına girin ve Priv_validator_key.json dosyanızı masaüstüne sürükle bırak yapıp yedekleyin.
  
  ![image](https://user-images.githubusercontent.com/76253089/223461995-bf236566-1a3b-453d-9833-7e373d83d705.png)

  
  
   </details>
