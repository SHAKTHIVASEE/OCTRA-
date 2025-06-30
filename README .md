# octra terminal client

## how to install and run transactions (step by step)

1. open terminal in gitpod and install Python

```bash
sudo apt install python3 python3-pip python3-venv python3-dev -y
```

2. run these commands :

```bash
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
python3 -m venv venv
source venv/bin/activate # for windows use: venv\Scripts\activate
pip install -r requirements.txt
cp wallet.json.example wallet.json
```

3. open wallet.json 
```bash
nano wallet.json
```

4. Edit it (change placeholders to your wallet data):

```json
{
  "priv": "private-key-here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

5. run to open frontend UI to make transaction

```bash
./run.sh
```

6. Now you can send transaction to other wallets, Some of my address given below to make transactions...

octCNEFKoAi13tbERnj8UdwyUUneM5MacJKhPSh5Kkvdoeu
octFrhYexg3h67DrBMuV1GGGTspPiHB1N8WL97HdyznxB15
oct8heKLgiUtNUaJppBesFSCRpcY7ja1zKr5EzCNxozQrLK
octBiACKTeoxody5Qr6ezmjGULYcgHM7X93oZFoWoPSHTxt
octFjXfCRgWYpnnmNLLbVvzA1U8pbQEFZtFQRnjmNiUNvor
octCNEFKoAi13tbERnj8UdwyUUneM5MacJKhPSh5Kkvdoeu
