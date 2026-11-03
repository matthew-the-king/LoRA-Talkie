# LoRA-Talkie

<img width="530" height="569" alt="image" src="https://github.com/user-attachments/assets/f21416f9-172d-48bb-a257-a688488ba8b5" />
<img width="415" height="650" alt="image" src="https://github.com/user-attachments/assets/f5ce1561-2d39-43b9-beb7-978eb588cad6" />


# FEATURES
Some features of the LoRA talkie are:<br>
1. Long Range Messaging
2. 5 keyboard switches for navigating the UI
3. Emergency switch that will sound an Alarm on the receiving end

# Parts
## Bill of Materials (BOM)

| Reference | Footprint | Quantity | Value | Links | Price |
|:---|:---|:---:|:---|:---|:---|
| B1 | BAT_BH-18650-PC_MPD | 1 | Holder | [Link](https://www.digikey.com/en/products/detail/mpd-memory-protection-devices/BH-18650-PC/3029216?s=N4IgTCBcDaIEIAkC0BGAHANgKwAYkAUBhEAXQF8g) | $3.35 |
| C1 | 0402 | 1 | 1uF | [Link](https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL05A105KO5NNNC/3886725) | $0.10 |
| C10, C11, C12, C13, C14, C15, C18, C19, C21, C3, C5, C9 | 0402 | 12 | 0.1uF | [Link](https://www.digikey.com/en/products/detail/yageo/CC0402KRX5R8BB104/5195106) | $0.56 |
| C16, C2, C20, C24, C4, C6, C7 | 0402 | 7 | 10uF | [Link](https://www.digikey.com/en/products/detail/murata-electronics/GRM155R60J106ME15D/5877401) |$0.95(buying 10 is cheaper than buying 7) |
| C17 | WCAP-PSHP_8X8.7_DXL_ | 1 | 470uF | [Link](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/875115252003/5147615) | $1.32 |
| C22, C23 | 0603 | 2 | 22uF | [Link](https://www.digikey.com/en/products/detail/holy-stone-enterprise-co-ltd/C0603B226M010T/16895513) | $0.68 |
| C8 | 0603 | 1 | 330nF | [Link](https://www.digikey.com/en/products/detail/tdk/CGA3E3X7R1H334K080AB/4931465) | $0.26 |
| D1 | D_SMA | 1 | 100V | [Link](https://www.digikey.com/en/products/detail/mcc-micro-commercial-components/SK310A-LTP/2642015) | $0.49 |
| FB1 | 0603 | 1 | 120R | [Link](https://www.digikey.com/en/products/detail/pulse-electronics/PE-0603PFB121ST/5050544) | $0.10 |
| J1 | SAMESKY_UJ20-C-H-G-SMT-1-P16-TR | 1 | USB_Charging | [Link](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/UJ20-C-H-G-SMT-P16-TR/24818595) | $0.65 |
| J2 | PinHeader_1x06_P2.54mm_Vertical | 1 | Conn_01x06_Pin | [Link](https://www.amazon.com/OCR-2-54mm-Breakaway-Connector-Arduino/dp/B0774VBJ3J/ref=sr_1_2_sspa?crid=3J6H8LMHZ3SS7&dib=eyJ2IjoiMSJ9.35ltPefTPqBOnQt_Ox_TI26xwO1SUs2D77_fY3-RewSFTh-Cg8mBGlhuQxJwY89Mr4AgBN51BE7EsK02txVfVMnuuAjss-PjZL7qeSK4j40VJrMjoEril4qtKCOSjhfoPAH9JvUulpll43v0f4zjy2FrXDKvMc4G_wxu7sPNflaKCRbgrA9vVlxch59x1EZD3Y7EnoJa7C-2_ka6BTX_5JUtUE_swCo9AXBNMqk3MVs.SY4UzEpKVAgJBn7IC6m1spKX7Eiw372FChIrKJbkStU&dib_tag=se&keywords=pin+headers&qid=1793638701&sprefix=pin+headers%2Caps%2C236&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) | $10 for a kit |
| J3 | CON_5051104091_MOL | 1 | 5051104091 | [Link](https://www.digikey.com/en/products/detail/molex/5051104091/5254662?s=N4IgTCBcDaIKwAY4EZkICwIJzJAXQF8g) | $2.25 |
| L1 | 1008 | 1 | 1.5uH | [Link](https://www.digikey.com/en/products/detail/murata-electronics/DFE252012P-1R5M-P2/5247259) | $0.22 |
| LS1 | CUI_CEM-1203_42_ | 1 | CEM-1203_42_ | [Link](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CEM-1203-42/412412) | $1.04 |
| Q1 | SOT-23 | 1 | MMBT3904 | [Link](https://www.digikey.com/en/products/detail/mcc-micro-commercial-components/MMBT3904-TP/717280) | $0.11 |
| R1, R2 | 0402 | 2 | 5.1kΩ | [Link](https://www.digikey.com/en/products/detail/yageo/RC0402FR-075K1L/726624?s=N4IgTCBcDaIEoGEAMAWJYBicC0SDsArANICMAMiALoC%2BQA) | $0.20 |
| R10 | 0402 | 1 | 31.6kΩ | [Link](https://www.digikey.com/en/products/detail/panasonic-industry/ERA-2AEB3162X/2026187) | $0.11 |
| R11, R20, R21, R22, R3, R4, R5, R6, R7, R8 | 0402 | 10 | 10kΩ | [Link](https://www.digikey.com/en/products/detail/yageo/RC0402JR-0710KL/726418?s=N4IgTCBcDaIEoGEAMAWJYBScC0SDsAjEgNIAyIAugL5A) | $0.19 |
| R12 | 0402 | 1 | 100kΩ | [Link](https://www.digikey.com/en/products/detail/yageo/RC0402FR-07100KL/726526) | $0.10 |
| R13 | 0603 | 1 | 300Ω | [Link](https://www.digikey.com/en/products/detail/yageo/RC0603FR-07300RL/724356) | $0.10 |
| R14 | 0805 | 1 | 20Ω | [Link](https://www.digikey.com/en/products/detail/koa-speer-electronics-inc/RK73H2ATTD20R0F/10233961) | $0.10 |
| R15 | 2010 | 1 | 100Ω | [Link](https://www.digikey.com/en/products/detail/yageo/RT2010FKE07100RL/5945596) | $0.16 |
| R16, R17 | 0402 | 2 | 4.7kΩ | [Link](https://www.digikey.com/en/products/detail/yageo/RC0402JR-074K7L/726477) | $0.19(Cheaper to buy 10 than 2)|
| R18 | 2512 | 1 | 3.74Ω | [Link](https://www.digikey.com/en/products/detail/koa-speer-electronics-inc/RK73H3ATTE3R74F/10423886) | $0.34 |
| R19 | 0402 | 1 | 1kΩ | [Link](https://www.digikey.com/en/products/detail/panasonic-industry/ERJ-2RKF1001X/79729) | $0.10 |
| R9 | MSRSF3920P1L00D2P0 | 1 | 0.001Ω | [Link](https://www.digikey.com/en/products/detail/susumu/MSRSF3920P-1L00-D2P0/24396792) | $1.74 |
| S1 | SW_800SP9B6M6RE | 1 | Emergency_Button | [Link](https://www.digikey.com/en/products/detail/e-switch/800SP9B6M6RE/502079) | $3.34 |
| SW1, SW2, SW3, SW4, SW5 | SW-TH_MX1A-E1NW | 5 | MX1A-E1NW | [Link](https://www.digikey.com/en/products/detail/cherry-americas-llc/MX1A-C1NW/280855) | $6.25 |
| U1 | COMM-SMD_12P-L11.6-W11.0-P1.27_114993390 | 1 | WIO-SX1262_C9900174795 | [Link](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/114993390/25835823) | $5.95 |
| U2 | LQFP-48_7x7mm_P0.5mm | 1 | STM32L051C8Tx | [Link](https://www.digikey.com/en/products/detail/stmicroelectronics/STM32L010K4T6/9770447) | $1.96 |
| U3 | DSBGA8_YCK_TEX | 1 | BQ25188YBGR | [Link](https://www.digikey.com/en/products/detail/texas-instruments/BQ25188YBGR/25796454) | $2.55 |
| U4 | X2QFN08_1P5X1P5_TEX | 1 | BQ298215RUGR | [Link](https://www.digikey.com/en/products/detail/texas-instruments/BQ298218RUGR/24420965) | $0.76 |
| U5 | PSON50P145X100X60-6N | 1 | TPD4S012DRYR | [Link](https://www.digikey.com/en/products/detail/texas-instruments/TPD4S012DRYR/2037539) | $1.19 |
| U6 | IC_MCP16362T-E_NMX | 1 | MCP16362T-E_NMX | [Link](https://www.digikey.com/en/products/detail/microchip-technology/MCP16362T-E-NMXVAO/14291783) | $2.33 |
| U7 | TRANS_UT6J3_ROM | 1 | UT6K3TCR | [Link](https://www.digikey.com/en/products/detail/rohm-semiconductor/UT6K3TCR/6573277) | $1.23 |

Battery:[Link](https://www.digikey.com/en/products/detail/jauch-quartz/LIINR18650JD-26E-2-6AH/26408508),$10.02<br>
LCD Screen:[Link](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-2-4-240320AF-CSXP/22204988), $13.94<br>
Use JLCPCB for the cheapest board cost; it is around $8 for 5 boards, plus $15 for shipping. 
# FIRMWARE

Not much here; I have not got the boards yet.

# PURPOSE OF PROJECT
The purpose of making the LoRA talkie was to deepen my understanding of LoRA devices, and in the Future I would really like to use a Non-module IC.
Also, I really wanted to make something that I could share with others, so a walkie-talkie seemed like an awesome choice. 
