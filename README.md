Generic BSP layer for the Luckfox Lyra in PicoCalc hardware.

# How to use
Add the BSP to your kas file
```yaml
repos:
  meta-picocalc-bsp-rockchip:
    url: "https://github.com/Calculinux/meta-picocalc-bsp-rockchip.git"
    refspec: "main"
    layers:
      .:
```
You can include the kas-deps.yaml file to automatically get all the necessary layers
```yaml
header:
  version: 14
  includes:
    - repo: meta-picocalc-bsp-rockchip
      file: kas-deps.yaml
```
