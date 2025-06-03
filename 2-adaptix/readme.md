# AdaptixC2

## Instalacia AdaptixC2

```bash
git clone https://github.com/Adaptix-Framework/AdaptixC2.git
cd AdaptixC2

bash pre_install_linux.sh
sudo apt install golang-go
make server; make extenders; make client
```

## Kompilacia Extension-Kit

```bash
git clone https://github.com/Adaptix-Framework/Extension-Kit
cd Extension-Kit
cd AD-BOF; make
cd ../Aliases; make
cd ../Creds-BOF; make
cd ../Elevation-BOF; make
cd ../Execution-BOF; make
cd ../Injection-BOF; make
cd ../Kerbeus-BOF; make
cd ../LateralMovement-BOF; make
cd ../SAL-BOF; make
cd ../SAR-BOF; make
cd ../..
```

## Spustanie servera a klienta

```bash
cd dist
bash ssl_gen.sh
./adaptixserver -profile profile.json
./AdaptixClient
```
