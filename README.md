# cheats
<p align="center">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/e21c7de1-2877-4355-9177-6c43d691f0c4" />
</p>

# Easy sharing 
Compartir una carpeta en red en un servidor remoto, navegar hasta la carpeta que se desea compartir
```
python3 -m http.server 8000 &
```
# Automatically shrink a pi image
Automatically shrink a pi image
```
wget https://raw.githubusercontent.com/Drewsif/PiShrink/master/pishrink.sh
chmod +x pishrink.sh
```
and
```
./pishrink.sh pikvm-orangepi.img
```
# Max compress
Máxima compresion
```
zip -9 orangepipc-kvm-msd-backup.zip orangepipc-kvm-msd-backup.img
```
# Split big files
Dividir un archivo ZIP en partes de 1,9GB
```
split -b 1900M orangepipc-kvm-msd-backup.zip orangepipc-kvm-msd-backup.zip.part-
```
