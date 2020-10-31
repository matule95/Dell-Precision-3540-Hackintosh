# macOs Catalina 10.15.5 - Dell Precision 3450

![Dell Precision 3450](https://i.dell.com/is/image/DellContent//content/dam/global-site-design/product_images/dell_client_products/workstations/mobile_workstations/precision/15_3540/pdp/laptop-precision-3540-pdp-gallery-504x350.jpg?fmt=jpg&wid=570&hei=400)

## OS

- Dual Boot macOs 10.15.5 + Windows 10 1903

## What Works

- CPU + IGPU Power Management
- Battery Status
- HDMI
- Sleep and Wake
- Audio ALC236
- Keyboard with Brightness and Audio fn keys
- Trackpad with Gestures
- WIFI (Changed Wifi card to BCM94360NG purchased here https://www.aliexpress.com/item/4000133686502.html?spm=a2g0o.cart.0.0.6d933c00jrbW24&mp=1)

## What doesn't work

- Bluetooth
- Trackpad buttons
- AMD Radeon Pro WX 2100

## Notes

macOs 10.15.5 broke HDMI (doesn't work even with framebuffer) so you must change use the kexts found in Graphics.of.Catalina.10.15.4. Install them with Kext Wizard in S/L/E and repair kext cache & permissions.

## Usefull Guides

- OpenCore --> https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html
- Fix HDMI --> https://www.reddit.com/r/hackintosh/comments/hu46xm/fix_hdmi_port_and_possibly_others_not_working_on/
