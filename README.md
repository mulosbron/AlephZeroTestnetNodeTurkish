# AlephTestnetNodeTurkish
sudo su
cd

sudo apt update && sudo apt upgrade -y
sudo apt install wget git -y
sudo apt-get install docker.io -y

Dosyayı klonlayın
git clone https://github.com/Cardinal-Cryptography/aleph-node-runner

Kurulum ve Çalıştırma(<> işaretlerini kaldırın)
cd aleph-node-runner
./run_node.sh -n <NODEADIN>

docker logs --follow <NODEADIN>

./signer.sh
