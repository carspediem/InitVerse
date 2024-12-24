# InitVerse

# Burner cüzdan aç ve kayıt ol
      https://candy.inichain.com?invite=A6967PX7ESC4DFINO36OX9HQC

# Açtığın cüzdan ile faucetten token al
      https://faucet-testnet.iniscan.com/

#  Screen aç 
      screen -S init

# Inichain gerekli dosyaları indir
      wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64

# İndirdiğin dosyaya yetki ver
      chmod +x iniminer-linux-x64

#  <YOUR_WALLET_ADDRESS> yerine 1.adımda açmış olduğun burner cüzdan adresini yapıştır ve başlat
      ./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672 --cpu-devices 1 --cpu-devices 2


#  Örnek böyle olacak
      ./iniminer-linux-x64 --pool stratum+tcp://0x2a728d7E39aE9414471b7c2e504E6EFC635BE009.Worker004@pool-core-testnet.inichain.com:32672 --cpu-devices 1 --cpu-devices 2



Notlar:

1. Yaklaşık 1-2 saat sonra cüzdan adresini aratarak aşağıdaki siteden durumu control et:
https://genesis-testnet.yatespool.com

2. Eğer sunucunun veya bilgisayarının gücü yetmiyorsa "--cpu-devices 2" sil sadece 1 tane kalsın. Eğer yetiyorsa daha fazla ekle - mesela --cpu-devices 2, --cpu-devices 3, --cpu-devices 4...

3. Durdurmak için CTRL + C

4. Başlatma kodundaki "Worker001" istediğin gibi değiştirebilirsin

5. Birden fazla sunucuda aynı cüzdan adresiyle kasabilirsin.
