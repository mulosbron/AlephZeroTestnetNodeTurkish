# <h1 align="center"> Aleph Zero Testnet Node Turkish </h1> 
![A0_Website_OG_Generic](https://user-images.githubusercontent.com/91866065/182647124-3f9916d0-ceea-4d9c-a938-3dafab049834.jpg)

## Linkler:
 * [Aleph Zero Resmi Twitter](https://twitter.com/aleph__zero)
 * [Aleph Zero Resmi Telegram](https://t.me/AlephZeroFoundation)
 * [Aleph Zero Resmi Reddit](https://www.reddit.com/r/AlephZero/)
 * [Aleph Zero Resmi Discord](https://discord.gg/alephzero)
 
## Sistem Gereksinimleri
### Minimum
#### Hardware Setup:

* CPU: modern desktop x86_64 (Intel, AMD) processor with at least 4 cores

* RAM:  16GB

* Storage: 1TB NVMe SSD

* Network: 25+Mbps

#### Cloud Setup:

* AWS: c5.large

* GCP: c2-standard-4

* Azure: F4s (+ additional persistent storage)

### Önerilen
#### Hardware Setup:

* CPU: modern desktop x86_64 (Intel, AMD) processor with at least 8 cores

* RAM:  32GB

* Storage: 2TB NVMe SSD

* Network: 100+Mbps

#### Cloud Setup:

* AWS: c5.xlarge

* GCP: c2-standard-8

* Azure: F8s (+ additional persistent storage)

![A0_Website_OG_Generic](https://alephzero.org/blog/app/uploads/2022/06/A0_Nodes_Requirements-1536x800.jpg)

## Komutları sırayla girelim:
```
sudo su

cd
```

## Gerekli kurulumlar ve güncellemeler:
```
sudo apt update && sudo apt upgrade -y

sudo apt install wget git -y

sudo apt-get install docker.io -y
```

## Dosyayı klonlayın:
```
git clone https://github.com/Cardinal-Cryptography/aleph-node-runner
```

## Kurulum ve çalıştırma(<> işaretlerini kaldırın):
```
cd aleph-node-runner

./run_node.sh -n <NODEADIN>
```

## Logları görüntüleme(<> işaretlerini kaldırın):
```
docker logs --follow <NODEADIN>
```

## Validator olmak için istenilen bilgileri alma:
```
./signer.sh
```
