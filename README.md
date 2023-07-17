# Lenovo-Yoga-C740-81TD-OpenCore-Hackintosh
My customized OpenCore EFI folder and config for running macOS Ventura and Sonoma on the Lenovo Yoga C740 81TD 15IML

EFI is based on OpenCore 0.9.4 Dev.. Readme is WIP

## Configured for Lenovo Yoga C740 81TD

| Device      | Model               |
| ----------- | ------------------- |
| Laptop      | Lenovo Yoga C740-15IML-81TD |
| CPU         | Intel Core i5-10210U |
| RAM         | Samsung 12GB 8+4 2667 MHz |
| Storage     | Sabrent Rocket 1TB NVMe SSD |
| GPU         | Intel Graphics UHD 630 |
| Audio  | Realtek ALC285 |
| Wireless    | Intel(R) Wi-Fi 6E AX210 160MHz |
| Display     | Lenovo Touch Display 1920x1080  |

# BIOS Setup
## Enable
-Load BIOS config defaults and then disable the security settings below<br><br>

# Disable
-Secure Boot<br>
-intel platform trust technology (Intel PTT)<br>
-Intel(R) SGX<br><br>

# Current Issues
-Display does not wake up from sleep<br>
-Touch screen only works when closing the laptop for 2 seconds and opening it<br>
-No Lenovo Pen/Wacom support<br>
-Microphone does not work as Intel SST is not supported<br>

# Working
-Everything Else including iMessage & Facetime with appropriate SMBIOS/ROM configuration<br>
-AirportItlwm kexts are included for Ventura and Sonoma, it is auto configured in the config, AirportItlwm for Sonoma is based on Preview2 and is still WIP, Will be updated once released
