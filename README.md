# ATUALIZAR PACOTES DO SISTEMA
```
apt-get update -y; apt-get upgrade -y;
```

# SINCRONIZAR NA VPS, COMPATÍVEL COM O PAINEL JSINFINITY-SSH!
# NÃO COMPATÍVEL COM SCRPT SSHPLUS PRO!
# ATUALIZAÇÃO 2/08/2022.
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/gugajs/plusnssh/main/gestorssh/sincpainel && chmod +x sincpainel && dos2unix sincpainel && ./sincpainel
```

# ATUALIZAÇÃO PAINELWEB JSINFINITY-SSH, TBM FUNCIONA EM OUTRAS VERSÕES DE PAINEL V20 E ETC... EM DEBIAN 8 OU UBUNTU 14!
# ATUALIZAÇÃO 2/08/2022.
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/gugajs/plusnssh/main/gestorssh/update && chmod +x update && dos2unix update && ./update
```

# INSTALAR PAINELWEB JSINFINITY-SSH DEBIAN 8 OU UBUNTU 14!
```
wget raw.githubusercontent.com/gugajs/plusnssh/main/gestorssh/install ; bash install
```

# DEFINIR/ALTERAR SENHA ROOT
```
wget raw.githubusercontent.com/gugajs/plusnssh/main/gestorssh/senharoot ; bash senharoot
```

# SINCRONIZAR NA VPS, CASO SEJA SSHPLUS PRO!
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/gugajs/plusnssh/main/gestorssh/sincrazy && chmod +x sincrazy && dos2unix sincrazy && ./sincrazy
```
