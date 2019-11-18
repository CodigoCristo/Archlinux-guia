# Archlinux-guia
Una Guía de instalación y Personalización de Arch Linux, desde instalación de BIOS y UEFI, controladores de vídeo privados y open-source ...

Extras:

sudo pacman -S android-file-transfer msmtp libmtp libcddb gvfs gvfs gvfs-afc gvfs-smb gvfs-gphoto2 gvfs-mtp gvfs-goa gvfs-nfs gvfs-google gst-libav geoclue dosfstools mtools jfsutils f2fs-tools btrfs-progs exfat-utils ntfs-3g reiserfsprogs udftools xfsprogs nilfs-utils polkit gpart ark xarchiver unarchiver binutils gzip lha lrzip lzip lz4 p7zip tar xz bzip2 p7zip lbzip2 arj lzop cpio unrar unzip zstd zip lzip unarj zstd pulseaudio pulseaudio-alsa pavucontrol pamixer pulseeffects pulseaudio-equalizer lib32-alsa-plugins lib32-libpulse pulseaudio-equalizer-ladspa libcanberra-pulse libcanberra-gstreamer ffmpeg aom libde265 x265 x264 libmpeg2 xvidcore libtheora libvpx schroedinger sdl gstreamer gst-plugins-bad gst-plugins-base gst-plugins-base-libs gst-plugins-good gst-plugins-ugly xine-lib libdvdcss libdvdread dvd+rw-tools lame jasper openjpeg libmng vcdimager --noconfirm

<br>

WINE


sudo pacman -S wine-staging winetricks kdialog dosbox cups samba 
giflib lib32-giflib libpng lib32-libpng libldap lib32-libldap
gnutls lib32-gnutls mpg123 lib32-mpg123 openal lib32-openal
v4l-utils lib32-v4l-utils libpulse lib32-libpulse
libgpg-error lib32-libgpg-error alsa-plugins lib32-alsa-plugins
alsa-lib lib32-alsa-lib libjpeg-turbo lib32-libjpeg-turbo
sqlite lib32-sqlite libxcomposite lib32-libxcomposite
libxinerama lib32-libxinerama libgcrypt lib32-libgcrypt
ncurses lib32-ncurses opencl-icd-loader lib32-opencl-icd-loader
libxslt lib32-libxslt libva lib32-libva gtk3 lib32-gtk3
gst-plugins-base-libs lib32-gst-plugins-base-libs 
sdl sdl2 lib32-sdl2 vkd3d lib32-vkd3d 
vulkan-headers vulkan-tools vulkan-icd-loader lib32-vulkan-icd-loader 
ocl-icd lib32-ocl-icd opencl-headers 

<br>
<br>

Puede parecer que hay muchas bibliotecas para instalar, pero para que los juegos se instalen y funcionen correctamente, los necesitará.
<br>
<br>
Para habilitar el repositorio multilib, descomente el [multilib] en /etc/pacman.conf
