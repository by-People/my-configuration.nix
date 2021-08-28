# my-configuration.nix
This is my simple NixOS configuration snapshot. If you want to use, please read side by side with the default configuration.nix.

✒️You can use this for your personal NixOS desktop configuration

1. This will install grub as bootloader (assuming you are using a gpt EFI partition)

2. You can adjust the time zone in the section
#Set your timezone
- To view the time zone. (on terminal)
$ timedatectl list-timezones

3. In enp3s0f2 and wlp2s0 adjust to your network interface. Check by command
$ ip a

Things to note :

- permission of unfree package added ( You can install unfree package like google-chrome)
- tlp and flatpak will be added 
- xfce the default dekstop with lightdm
- the default username (reiza=myname) please change it
- 2 users (reiza and guest)
- pipewire can be enabled by omitting # (read wiki)


BAHASA

# configuration.nix
Ini adalah snapshot konfigurasi NixOS sederhana saya. Jika ingin menggunakan, silakan baca berdampingan dengan default configuration.nix.

️Anda dapat menggunakan ini untuk konfigurasi desktop NixOS pribadi Anda

1. Ini akan menginstal grub sebagai bootloader (dengan asumsi Anda menggunakan partisi gpt EFI)

2. Anda dapat menyesuaikan zona waktu di bagian
#Setel zona waktu Anda
- Untuk melihat zona waktu. (di terminal)
$ timedatectl list-timezones

3. Di enp3s0f2 dan wlp2s0 sesuaikan dengan antarmuka jaringan Anda. Periksa dengan perintah
$ ip a

Hal-hal yang perlu diperhatikan:

- izin paket tidak gratis ditambahkan (Anda dapat menginstal paket tidak gratis seperti google-chrome)
- tlp dan flatpak akan ditambahkan
- xfce dekstop default dengan lightdm
- nama pengguna default (reiza=namasaya) tolong ubah
- 2 pengguna (reiza dan tamu)
- pipewire dapat diaktifkan dengan menghilangkan # (baca wiki)
