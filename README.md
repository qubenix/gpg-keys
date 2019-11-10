# qubenix gpg keys

## A. Clone repo
```
$ git clone https://github.com/qubenix/gpg-keys
```
## B. Import keys
```
$ gpg --import $(ls gpg-keys/*.pub)
gpg: key 0x09D159E1241F9C54: 3 signatures not checked due to missing keys
gpg: key 0x09D159E1241F9C54: public key "qubenix email key <qubenix@riseup.net>" imported
gpg: key 0x04BE1E61A3C2E500: public key "qubenix <qubenix@noreply.users.github.com>" imported
gpg: key 0xA95D4D197E922B20: public key "qubenix github key <qubenix@users.noreply.github.com>" imported
gpg: Total number processed: 3
gpg:               imported: 3
gpg: no ultimately trusted keys found
```