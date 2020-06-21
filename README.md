# SHELL SCRIPTS

## CREATE OPEN OVPN CONFIG

```bash
curl -O https://raw.githubusercontent.com/IvanAphanasyev/vpn-script-shell/master/new-config-user-days.sh
chmod +x new-config-user-days.sh
rm ${user_id}
./new-config-user-days.sh ${user_id} ${days}
```

## INSTALL SERVER

```bash
curl -O https://raw.githubusercontent.com/IvanAphanasyev/vpn-script-shell/master/new-config-user-days.sh
chmod +x new-config-user-days.sh
./new-config-user-days.sh
```

## FOR TESTING API NEED DELETE OPENVPN SERVER

Delete server using https://github.com/Nyr/openvpn-install

```bash
    ssh user_name@ip_address
    password: "password"

    wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh

    rm ./*
```

## DOWNLOAD FILE VIA SSHPASS

```bash
sshpass -p "password" scp username@ip:/root/user_id.ovpn .
```
