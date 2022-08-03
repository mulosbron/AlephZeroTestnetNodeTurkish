# AlephTestnetNodeTurkish
![A0_Website_OG_Generic](https://user-images.githubusercontent.com/91866065/182647124-3f9916d0-ceea-4d9c-a938-3dafab049834.jpg)

# Komutları sırayla girelim.
```
sudo su

cd
```

# Gerekli Kurulumlar ve Güncellemeler
```
sudo apt update && sudo apt upgrade -y

sudo apt install wget git -y

sudo apt-get install docker.io -y
```

# Dosyayı Klonlayın
```
git clone https://github.com/Cardinal-Cryptography/aleph-node-runner
```

# Kurulum ve Çalıştırma(<> işaretlerini kaldırın)
```
cd aleph-node-runner

./run_node.sh -n <NODEADIN>
```

# Logları Görüntüleme
```
docker logs --follow <NODEADIN>
```

# Validator Olmak İçin İstenilen Bilgileri Alma
```
./signer.sh
```
