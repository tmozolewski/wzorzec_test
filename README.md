
## Informacje
Playbook do instalacji systemu Ubuntu 18.04 z wzorca przygotowanego przez NETIS
Playbook usunie wszytskie partycje z pierwszego dysku oraz utworzy jedną z systemem plików ext4 

## Wymagania
Komputer musi być właczony z systemu LIVE **Ubuntu 18 64 bit**
Do uruchomienie playbooka wymagane są pakiery git oraz ansible
 ```
 sudo apt-add-repository multiverse
 sudo apt-get install git ansible --yes --force-yes
```

## Instalacja
Uruchomienie playbooka:
```
 ansible-pull -U https://github.com/netispl/wzorzec -i hosts
```
