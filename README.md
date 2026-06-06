# ESP32-S3-NoWireless-board
## Description
This is a devboard built using just the ESP32-S3 chip.
## Reason for Creation
Given the ESP32-S3’s AI capabilities and high performance, I wanted to create a program that connects a camera and analyzes its footage using  
AI. However, most inexpensive development boards lack technical compliance certification, and without it, powering them on in Japan would be illegal, forcing me to use a more expensive model.  
This makes it difficult to popularize affordable AI cameras, which is why I decided to build this.  
## Pictures
### Schematic
![Schematic](./screenshots/schematic5.png)
### PCB
![PCB](./screenshots/pcb3.png)
### 3D
![3D-1](./screenshots/3d-1.png)
![3D-2](./screenshots/3d-2.png)
### Estimates
- JLCPCB  
![JLCPCB Estimate1](./screenshots/jlcpcb-estimate.png)  
**Shipping options**  
![JLCPCB Estimate2](./screenshots/jlcpcb-shipping.png)  
- LCSC  
![LCSC Estimate1](./screenshots/lcsc-estimate.png)  
**Shipping options**  
![LCSC Estimate2](./screenshots/lcsc-shipping-1.png)
![LCSC Estimate3](./screenshots/lcsc-shipping-2.png)  
- Aliexpress  
![Aliexpress Estimate1](./screenshots/aliexpress-1.png)  
![Aliexpress Estimate2](./screenshots/aliexpress-2.png)  

## BOM
| No. | リファレンス (Designators)                               | 部品名 / 値 (Value)             | フットプリント (Footprint)                                  | 数量 |URL           |
|-----|----------------------------------------------------|-----------------------------|------------------------------------------------------|----|-----
| 1   | C13, C15, C12                                      | 4.7uF                       | C_0603_1608Metric_Pad1.08x0.95mm_HandSolder          | 3  | https://www.lcsc.com/product-detail/C90057.html?spm=wm.gwc.xh.0.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 2   | C16, C14, C19, C20, C24, C7, C22, C21, C23, C6, C3 | 0.1uF                       | C_0603_1608Metric_Pad1.08x0.95mm_HandSolder          | 11 | https://www.lcsc.com/product-detail/C85864.html?spm=wm.gwc.xh.1.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 3   | R7, R12, R11, R9, R1, R10, R8                      | 10k                         | R_0603_1608Metric_Pad0.98x0.95mm_HandSolder          | 7  | https://www.lcsc.com/product-detail/C130232.html?spm=wm.gwc.xh.3.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 4   | C9, C8, C10, C17, C2, C18, C11, C1                 | 10uF                        | C_0603_1608Metric_Pad1.08x0.95mm_HandSolder          | 8  | https://www.lcsc.com/product-detail/C7307463.html?spm=wm.gwc.dh.2.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 5   | U6                                                 | NCP1117-1.5_SOT223          | SOT-223-3_TabPin2                                    | 1  | https://www.lcsc.com/product-detail/C5380421.html?spm=wm.gwc.xh.4.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 6   | RST_SW                                             | RST_SW                      | SW_Push_SPST_NO_Alps_SKRK                            | 1  | https://www.lcsc.com/product-detail/C202388.html?spm=wm.gwc.xh.5.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 7   | U7                                                 | MCP1700x-330xxTT            | SOT-23                                               | 1  | https://www.lcsc.com/product-detail/C7551026.html?spm=wm.gwc.xh.6.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 8   | Y1                                                 | 40MHz                       | Crystal_SMD_3225-4Pin_3.2x2.5mm_HandSoldering        | 1  | https://www.lcsc.com/product-detail/C255943.html?spm=wm.gwc.xh.7.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 9   | R13                                                | 50                          | R_0603_1608Metric_Pad0.98x0.95mm_HandSolder          | 1  | https://www.lcsc.com/product-detail/C849792.html?spm=wm.gwc.xh.8.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 10  | U1                                                 | ESP32-S3                    | QFN-56-1EP_7x7mm_P0.4mm_EP4x4mm                      | 1  | https://ja.aliexpress.com/item/1005012279323107.html?spm=a2g0o.cart.0.0.13f52e1aYLpvOE&mp=1&pdp_npi=6%40dis%21USD%21USD+10.40%21USD+8.22%21%21USD+7.81%21%21%21%40212e520f17803584957476551e54c5%2112000057974508459%21ct%21JP%216223408418%21%211%210%21&gatewayAdapt=glo2jpn
| 11  | R6                                                 | 1k                          | R_0603_1608Metric_Pad0.98x0.95mm_HandSolder          | 1  | https://www.lcsc.com/product-detail/C118155.html?spm=wm.gwc.xh.9.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 12  | C4, C5                                             | 15pF                        | C_0603_1608Metric_Pad1.08x0.95mm_HandSolder          | 2  | https://www.lcsc.com/product-detail/C71651.html?spm=wm.gwc.xh.10.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 13  | U2                                                 | MCP1700x-280xxTT            | SOT-23                                               | 1  | https://www.lcsc.com/product-detail/C236702.html?spm=wm.gwc.xh.11.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 14  | BOOT_SW                                            | BOOT_SW                     | SW_Push_SPST_NO_Alps_SKRK                            | 1  | https://www.lcsc.com/product-detail/C202388.html?spm=wm.gwc.xh.5.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 15  | J1                                                 | USB_C_Receptacle_USB2.0_14P | USB_C_Receptacle_HRO_TYPE-C-31-M-12                  | 1  | https://www.lcsc.com/product-detail/C165948.html?spm=wm.gwc.xh.12.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 16  | D7                                                 | Green power light           | LED_0805_2012Metric_Pad1.15x1.40mm_HandSolder        | 1  | https://www.lcsc.com/product-detail/C192319.html?spm=wm.gwc.xh.13.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 17  | R3, R2                                             | 5.1k                        | R_0603_1608Metric_Pad0.98x0.95mm_HandSolder          | 2  | https://www.lcsc.com/product-detail/C160048.html?spm=wm.gwc.xh.14.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 18  | U4                                                 | ESP-PSRAM64H                | SOIC-8_3.9x4.9mm_P1.27mm                             | 1  | https://ja.aliexpress.com/item/1005009178803030.html?spm=a2g0o.cart.0.0.13f52e1aYLpvOE&mp=1&pdp_npi=6%40dis%21USD%21USD+4.93%21USD+4.93%21%21USD+4.93%21%21%21%40212e520f17803584957476551e54c5%2112000048208912278%21ct%21JP%216223408418%21%211%210%21&gatewayAdapt=glo2jpn
| 19  | D6, D2, D4, D5, D1                                 | ESD9B3.3ST5G                | D_SOD-923                                            | 5  | https://www.lcsc.com/product-detail/C51898359.html?spm=wm.gwc.xh.16.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 20  | J3                                                 | Micro_SD_Card               | microSD_HC_Molex_104031-0811                         | 1  | https://www.lcsc.com/product-detail/C585350.html?spm=wm.gwc.xh.18.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 21  | R5, R4                                             | 23                          | R_0603_1608Metric_Pad0.98x0.95mm_HandSolder          | 2  | https://www.lcsc.com/product-detail/C2612468.html?spm=wm.gwc.xh.15.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 22  | U3                                                 | W25Q128JVS                  | SOIC-8_5.3x5.3mm_P1.27mm                             | 1  | https://www.lcsc.com/product-detail/C97521.html?spm=wm.gwc.xh.19.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 23  | J4                                                 | Conn_01x08                  | PinHeader_1x08_P2.54mm_Horizontal                    | 1  | https://www.lcsc.com/product-detail/C7501270.html?spm=wm.gwc.xh.20.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 24  | J2                                                 | OV2640                      | Amphenol_F32Q-1A7x1-11024_1x24-1MP_P0.5mm_Horizontal | 1  | https://www.lcsc.com/product-detail/C3168917.html?spm=wm.gwc.xh.21.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
| 25  | D3                                                 | ESD9B5.0ST5G                | D_SOD-923                                            | 1  | https://www.lcsc.com/product-detail/C82326.html?spm=wm.gwc.xh.17.cbm___wm.sy.ssl.gwc&lcsc_vid=QwBbVAVXQFcNVVcCQFkMUlFREQIMBFxQQ1YIUQIFR1MxVlNeR1JbUF1TQVhcVjtW
