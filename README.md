# Caimán Browser

Chromium 155.0.8059.39 para FLinux 32 bits, con la marca Caimán.

## Archivos

- `caiman-browser.tcz` - Paquete Tiny Core (127 MB)
- `caiman-browser.tcz.dep` - Dependencias (nss.tcz, nspr.tcz)
- `caiman-browser.tcz.md5.txt` - Verificación MD5

## Instalación

1. Bajar los 3 archivos
2. Verificar: `md5sum -c caiman-browser.tcz.md5.txt`
3. Instalar: `tce-load -i caiman-browser.tcz`
4. Para carga automática: agregar `caiman-browser.tcz` a `tce/optional/onboot.lst`

## Fuente

Binarios oficiales de Debian trixie i386 (security.debian.org), Chromium 155.0.8059.39-1~deb13u1.
Incluye libudev1.
