<h1 align="center">
  <br>
  <img src="https://github.com/ItsAkshatSh/iPlayer/blob/main/assets/Iplayer_banner.png?raw=true" width=90%>
  <br>
  <br>
  iPlayer
  <br>
</h1>
<div align="center">

![EasyEDA](https://img.shields.io/badge/Made%20with-EasyEDA-07162A)

iPlayer is the re-engineered version of the iPod Gen 5 Video, running on a Seeed Studio Xiao nRF52840, using a replacement apple click wheel with an 2.4" LCD Screen
</div>

### Why?
Cause lowkey I wanted a music player of my own, and the iPod is a classic, so why not recreate it

## Parts!
- Uses a ***Seeed Studio XIAO nRF52840***, using it's charging module!
- ***2.4" LCD Screen***, great price!
- ***4x SMD Tactile switches***, buttons for the click wheel
- ***White Click Wheel**, I didn't know wheels were clicky?!
- ***CUI SJ-3523-SMT-TR***, the headphone jack connector!
- ***TI PCM5102APW***, Audio DAC
- ***TI TPA6132A2RTER***, Headphone amplifier (the last two parts make me feel fancy)
- ***XUNPU SD-106M***, SD Card Connector
- ***2000 mAH Lipo Battery***, Humongous battery
- ***MCP23017***, extraaa pins!

## Hardware

want to work on this? head to [/hardware](https://github.com/ItsAkshatSh/iPlayer/tree/main/Hardware)

- Refer to the BOM [here](https://github.com/ItsAkshatSh/iPlayer/blob/main/BOM.csv)
- Download the PCB Project file [here](https://github.com/ItsAkshatSh/iPlayer/tree/main/Hardware/Project%20File)
- Order the PCB and parts using the Gerber Files, BOM and Pick&Place (Refer [here](https://github.com/ItsAkshatSh/iPlayer/tree/main/Hardware))
- Solder all the components according to the schematic!
- Download CircuitPython for Seeed Studio XIAO nRF52840
- Hold the BOOT button and plug in the MCU
- It should appear as a CIRCUITPY drive
- Download the firmware
- Copy all the file to the CIRCUITPY drive
- and, you're done!

<div align='center'>

## Schematic
<div align="Center">
<img width="60%" height="60%" alt="image" src="https://github.com/ItsAkshatSh/iPlayer/blob/main/Hardware/SCH.png?raw=true" />
</div>

## PCB
<div align="Center">
<img width="60%" height="60%" alt="image" src="https://github.com/ItsAkshatSh/iPlayer/blob/main/Hardware/PCB.png?raw=true" />
</div>

</div>

<div align='center'>

## CAD (Case)

<table align="center">
  <tr>
    <th>Front</th>
    <th>Back</th>
  </tr>
  <tr>
    <td><img src="https://github.com/ItsAkshatSh/iPlayer/blob/main/assets/front.png?raw=true" width=300px></td>
    <td><img src="https://github.com/ItsAkshatSh/iPlayer/blob/main/assets/back.png?raw=true" width=300px></td>
  </tr>
</table>
<table align="center">
  <tr>
    <th>Top</th>
    <th>Bottom</th>
  </tr>
  <tr>
    <td><img src="https://github.com/ItsAkshatSh/iPlayer/blob/main/assets/top.png?raw=true" width=300px></td>
    <td><img src="https://github.com/ItsAkshatSh/iPlayer/blob/main/assets/bottom.png?raw=true" width=300px></td>
  </tr>
</table>


[link to tinkercad](https://www.tinkercad.com/things/7QSXqnSlcvx-dazzling-waasa-migelo/edit?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=juyttt5uGTzu_SM2p95USCvhYnbcEyoNm93AeGJV7iI) / [link to onshape](https://cad.onshape.com/documents/dec4665ff2cc214070525b64/w/0dcda68e76d1402d44254b29/e/47c8bf74dd594df05ecc1ae9?renderMode=0&uiState=6a6f5126a4b76ae515814d74)
</div>


<div align='center'>

## BOM

| S. No. | Part | Link | Qty | Cost | Notes |
|---:|:---|:---:|---:|---:|:---|
| 1 | SMD Tactile switches | [link](https://www.lcsc.com/product-detail/C720477.html?lcsc_vid=EwNcAgVQT1NWVAEHE1RdAwICFlINAV1STwJeAgYEQwAxVlNeQ1NWV11eQlBWVzsOAxUeFF5JWBYZEEoBGA4JCwFIFA4DSA%3D%3D) | 10 | $0.00 | Included in PCB |
| 2 | White Click Wheel + Case + Center Button | [link](https://ar.aliexpress.com/item/1005010414463958.html?spm=a2g0o.productlist.main.12.43264fceE3681f&aem_p4p_detail=2026071702430411650887511787680000661319&algo_pvid=8a94c164-613d-4e73-8bad-20aef1cfacc3&algo_exp_id=8a94c164-613d-4e73-8bad-20aef1cfacc3-11&pdp_ext_f=%7B%22order%22%3A%22123%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21AED%21120.76%2163.10%21%21%21216.30%21113.01%21%4021413b0b17842813846227003e0e42%2112000052331730334%21sea%21AE%216546026290%21ABX%211%210%21n_tag%3A-29910%3Bd%3A8a094002%3Bm03_new_user%3A-29895&curPageLogUid=XYLC6iHSTEP6&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010414463958%7C_p_origin_prod%3A&search_p4p_id=2026071702430411650887511787680000661319_3) | 1 | $17 | |
| 3 | Connectors - Click Wheel | [link](https://www.lcsc.com/product-detail/C2889266.html) | 1 | $0 | Included in PCB |
| 4 | 2.4" LCD Screen | [link](https://eu.mouser.com/en/ProductDetail/Microtips-Technology/MTD0240PZG?qs=EU6FO9ffTweWddz2VS6TQQ%3D%3D) | 1 | $7 | |
| 5 | Headphone Jack | [link](https://www.lcsc.com/product-detail/C4991872.html?s_z=s_p_SJ-3523-SMT-TR&lcsc_vid=T1QPA1JQRFhZAwAHFlkPUQUEQVdcAgcCEgNcVVcCElYxVlNeQ1JYU1ZXR1JdVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) | 1 | $0 | Included in PCB |
| 6 | Audio DAC | [link](https://www.lcsc.com/product-detail/C1520792.html?s_z=n_q_PCM5102A&lcsc_vid=T1QPA1JQRFhZAwAHFlkPUQUEQVdcAgcCEgNcVVcCElYxVlNeQ1JYVFJRQFdWXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktfRFFADxALGw%3D%3D) | 1 | $0 | Included in PCB |
| 7 | Headphone Amplifier | [link](https://www.lcsc.com/product-detail/C69901.html?s_z=n_q_l_tpa6132a2&lcsc_vid=T1QPA1JQRFhZAwAHFlkPUQUEQVdcAgcCEgNcVVcCElYxVlNeQ1JYU1RVQFldUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVFYVFZIHxUDCw%3D%3D) | 1 | $0 | Included in PCB |
| 8 | SD Card Connector | [link](https://www.lcsc.com/product-detail/C266603.html?s_z=n_q_sd%2520card%2520connector&lcsc_vid=T1QPA1JQRFhZAwAHFlkPUQUEQVdcAgcCEgNcVVcCElYxVlNeQ1JYU1xeT1BeUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQFReVlRQQU8GEwkK) | 1 | $0 | Included in PCB |
| 9 | Seeed Studio nRF52840 | [link](https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html) | 1 | $10 | |
| 10 | 2000 mAH Lipo Battery | [link](https://www.amazon.ae/KBT-KEEP-BETTER-TECH-Li-Polymer/dp/B09SV3CJBY/ref=sr_1_18?crid=2FJIUR03O6XB2&dib=eyJ2IjoiMSJ9.bSX1ZnR1G-f1voL2Yt1enitAx-s-K4rBc-ujjLJpbwNWgXOCdm2EiSeVOzg3152poS51zSFX3ZCi8Bjd-eaIaOX5JQJ2HA8OrOIm3tPUA10x_iqbzWh_WPGOak3AbV55qyOON-MdpaS8kb5obR9TmUiWtHKSd1mI2o3nZmfxiJ0l0LMng3lv6dbZVuvntB4-DnkPs9OflIzBUIy4_nekTO4BAiBETTNQRmfTb3qY_ntuFfpF0ZZt9_iaODjEcQWXIL9imDoE5QPzaGr8k_TgZYAlVMctApM7o-Jjw9R4GS4.dVGVPsGo0GHtMaNtAm5uSeg2pixjL1Hh9xgbZpw7G30&dib_tag=se&keywords=2000mah+lipo+battery&qid=1784375029&sprefix=2000mah+lip,aps,299&sr=8-18&th=1) | 1 | $37.03 | |
| 11 | MICROCHIP MCP23017-E/ML | [link](https://www.lcsc.com/product-detail/C639770.html?s_z=n_q_MCP23017&lcsc_vid=T1QPA1JQRFhZAwAHFlkPUQUEQVdcAgcCEgNcVVcCElYxVlNeQ1JZUlVfT1NXXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktRQlZADxALGw%3D%3D) | 1 | $0 | Included in PCB |
| 12 | PCB (JLCPCB) | - | 5 | $73.44 | |
| | **Total** | - | - | **$144.47** | |

</div>

<div align='center'>

## Zine


<img src="https://github.com/ItsAkshatSh/iPlayer/blob/main/assets/iPlayer_zin.png?raw=true" width=50% height=50%>


### Thank you HackClub!
