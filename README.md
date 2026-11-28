# M463AC Master Module · Summing

Ward-Beck Systems M463AC, 1986|19. Wiki page: [M463AC on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.SUMMING.M463AC-Master-Module/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 56 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 10 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 217 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 13 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 35 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1986 - M463AC - P003 - 1-1.jpg](MANUALS/1986%20-%20M463AC%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 18 dB +/ -0.5 cB. (with fader &quot;in-hand&quot; position). |
| **Frequency response** | +/_ 0.25 dB irom 20 Hz |
| **Noise** | dB below dBm nominal output level Hz kHz). |
| **Harmonic distortion** | Less than 0.25% from Hz kHz +28 dBm less Typically less than 0.05% across most bandwidth) |
| **Source impedances** |  |
| &nbsp;&nbsp;Summing | 30,000 ohms balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing | Less than ohms |
| **Output impedance** | Less than 100 ohms (at 8-1094 output and DIRECT ou: tput Less tnan 200 ohms MONITOR output. |
| **Load impedance** | 600 ohms balanced (at insertion point and DIRECT output) |
| **Output level** | -10 dBm nominal dBm nominal +30 dBm maximum insertion DIRECT output |
| **Phasing** | Input and output terminals designated by numbers are phase |
| **Power requirements** | +/-25 volts dc_ 200 MA maximum. mA nominal |
| **Ambient temperature** | degrees Celsius |
| **Dimensions** | wide 7.0&quot; high 6.5&quot; deep (41 mm 178 mm 165 mim) |

## Circuit description

From [1986 - M463AC - Master Module (2).pdf](MANUALS/1986%20-%20M463AC%20-%20Master%20Module%20(2).pdf) pages 4-6 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**M4 6 3AC MASTER MOOUL E**

The M4 6 3AC IS d esl g n&quot;,d 10 accept combined or mh.ed feeds fl&quot;Otl'l previously a u lgned ml&quot; lng channel in pu lS. Thea s signed m i &quot; ln g channel In p u l S.... arn¢l lit ied and rou led to Ih e a p proprla l e poi nlS w il hint he consoles y. t..&quot;.

Input and Summing Amp H t i....

Tn e signal or lg lnal lng fl&quot;Otl'l the e&quot;lern al m i&quot; ing ne lwork is applied 10 lhe.unvn lng cu.... en l nodes of the input amp litier via edge conne&lt;; lor pin. 1 and A.

01 through 08 form a.unvning amplifie.. comprising a bal.nced Input and a n unbalanced OUlpUI. to eeeeee e fOf' small sySl..&quot; level var i a ti on., trim COl R7 i. In COl&quot;'i=lOf'a led asp arI of I n e pree mp lit i.... The d lfferenl ia l baLance adjuSt men l control R6 serves 10 minimize common mode type signals orlg ln. lin g ahead of m e. mp l ifi e r. CI Z couples Ih e OUlpul of l he.u&quot;&quot;&quot;ing amplifier to a lo w-pa s stiller &lt;;QnsiSl ing o f R22, R23, R24, CU, C I 4, CIS and Z l. The 3 e e rol1-off poin l I. loca leda l appro&quot;ima lely 40 kHz.

Tn&quot;, OUlpUI of ZI Is coup led through C18 to th. outp ul amplifier 8 -I09A.

8 -I09A OUl p...1 Amplitler and INSERT

The 8-10 9A amplifier raises the nominal signal level 100 dBm. The:::rUsl. I. active l y b.l.nced and fed 10 lhe ~ in s&quot;&quot; l poi nt&quot; atp ins I S

Pin. 15 and S........ ua ll y con ne&lt;; led to a no......all edsel of In se&quot; l jacks, wi l n t n e ou tpu l. Ide connected 10 Ine maSler fader.

The f. d er output Is r e t...rn e d 10 the module on pins 9 and K. The feed for Ihe PR EF AO£ o u l pUI SIs normally picked u pal Ih e ml &quot; ing f.deri n p u l.nd i...e lu r ned 10 In e module via pins 14 and R.

B_l09F BOOSl er &quot;&quot;'?!.!..!!.Z:

Th l. a mpl i f i... oper. tes with again o f 33 d B. It r-ecov ers tne 15 d B

&quot; in. han d&quot; lou incurred b y l h e f.der and provides additional gain

top ro duc e. no min. l leve! o f +8 dBm a l Its ou l put.

The DIRECT outp u lap pears atp ins 16 and T.

Auxiliary OulP ut s

In !Iddl lion, a SOLO output is ava liable via SW7, 10 allows elect i v emo nit orin !l of I hep art ic ula r ma Sler channel. Other feeds originating from the 8_109F amplifier are $u p plied tome POSTF AOE RS, FB and PAc han n e ls.

PRE/ POST Se l eClor Switches and Level Controls

PRE / POSTs e le Clio n of the RS, ' F Band P A channels 1$ f aci l ll ated by switches SW2, SW3 and SW4 respect i vely; each switch Is followed b y its a.. s oci ate d level control. Theoutp ulS of the level con lrol s !Ire fed to Ih e summing ou lput s via individual &quot;$$Ignme nt switches. Following the lI$s ig n men t switch e s, Ih e s e outputs are fed to their app r op r i ate mixing buses vIa summing resistors.

Control Functions

Power Supply Decou pllng

An eeuve power $u p ply decouplln g network consisting o f 09 through 014 provides Iso la l lon between the module and Ihe +/ _ 25 volt supply rails. TranSistors 013 and 014 monitor Ih e supply current. In thee vent of excessive power supply demands, such a s from component failure ora mp l ifie r overdrive, the current flowing Ihro ugh 0 1 1 and 012 will b e limited. a

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHpUSEtXNmZvV0U/view?resourcekey=0-eArlgHsNDE3ktPPa_vIZKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHpUSEtXNmZvV0U&resourcekey=0-eArlgHsNDE3ktPPa_vIZKA" width="240" alt="1986 - M463AC - 463-04-104 - HNEN AEPRESSCO CNE POSTFADE.jpg"></a><br><sub>1986|19 · 463-04-104 - HNEN AEPRESSCO CNE POSTFADE · <a href="MECHANICAL/1986%20-%20M463AC%20-%20463-04-104%20-%20HNEN%20AEPRESSCO%20CNE%20POSTFADE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M463AC.stl`](MECHANICAL/M463AC.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M463AC)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: wide 7.0" high 6.5" deep (41 mm 178 mm 165 mim))
- **From the drawing:** 7 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M463AC - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M463AC.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlNDUXR5czM5Tlk/view?resourcekey=0-lUCnGxW_wnkZT-agpeg5wA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlNDUXR5czM5Tlk&resourcekey=0-lUCnGxW_wnkZT-agpeg5wA" width="240" alt="1986 - M463AC - 463-01-020 - INPUT FADER.jpg"></a><br><sub>1986|19 · 463-01-020 - INPUT FADER · <a href="SCHEMATICS/1986%20-%20M463AC%20-%20463-01-020%20-%20INPUT%20FADER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUp1MFRleWthRU0/view?resourcekey=0-yLONvv45Om9CyKiBVzuNig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUp1MFRleWthRU0&resourcekey=0-yLONvv45Om9CyKiBVzuNig" width="240" alt="1986 - M463AC - 463-01-020 - MASTER MODULE.jpg"></a><br><sub>1986|19 · 463-01-020 - MASTER MODULE · <a href="SCHEMATICS/1986%20-%20M463AC%20-%20463-01-020%20-%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjVONERwMTJxd3c/view?resourcekey=0-he0CzOXGnqnQnIalEl4l_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjVONERwMTJxd3c&resourcekey=0-he0CzOXGnqnQnIalEl4l_g" width="240" alt="1986 - M463AC - 463-02-020 - LALL RESISTO ISK.jpg"></a><br><sub>1986|19 · 463-02-020 - LALL RESISTO ISK · <a href="SCHEMATICS/1986%20-%20M463AC%20-%20463-02-020%20-%20LALL%20RESISTO%20ISK%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWUJaV1I2ZDB4Vnc/view?resourcekey=0-jg9ZtDSw1dCBMpwAzCk-nA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWUJaV1I2ZDB4Vnc&resourcekey=0-jg9ZtDSw1dCBMpwAzCk-nA" width="240" alt="1986 - M463AC - 463-02-020 - MASTER MODULE SCHEMATIC FONU.jpg"></a><br><sub>1986|19 · 463-02-020 - MASTER MODULE SCHEMATIC FONU · <a href="SCHEMATICS/1986%20-%20M463AC%20-%20463-02-020%20-%20MASTER%20MODULE%20SCHEMATIC%20FONU%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR19UeVY4OFpLWGc/view?resourcekey=0-vWdGRlFoOvb-_aeyjH06uQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR19UeVY4OFpLWGc&resourcekey=0-vWdGRlFoOvb-_aeyjH06uQ" width="240" alt="1986 - M463AC - 463-06-028 - SOLDER SIDE ENG.jpg"></a><br><sub>1986|19 · 463-06-028 - SOLDER SIDE ENG · <a href="SCHEMATICS/1986%20-%20M463AC%20-%20463-06-028%20-%20SOLDER%20SIDE%20ENG%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR09lRk5UTEc4dms/view?resourcekey=0-qAy1uTXnwqBJzoHUJ_W1Fg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR09lRk5UTEc4dms&resourcekey=0-qAy1uTXnwqBJzoHUJ_W1Fg" width="240" alt="1986 - M463AC - 463-06-028 - TES COMPONENT SIDE NOIES PINS IEI.jpg"></a><br><sub>1986|19 · 463-06-028 - TES COMPONENT SIDE NOIES PINS IEI · <a href="SCHEMATICS/1986%20-%20M463AC%20-%20463-06-028%20-%20TES%20COMPONENT%20SIDE%20NOIES%20PINS%20IEI%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbXFiaFZveVN5bXM/view?resourcekey=0-YQNID-9y8KD0x2AEMG7RuA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbXFiaFZveVN5bXM&resourcekey=0-YQNID-9y8KD0x2AEMG7RuA" width="240" alt="1986 - M463AC - 8-109-02-002 - OUTPUT AMPLIFIER CKDEAL SCHEMATIC.jpg"></a><br><sub>1986|19 · 8-109-02-002 - OUTPUT AMPLIFIER CKDEAL SCHEMATIC · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20CKDEAL%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0hXNjd0OEQ1Skk/view?resourcekey=0-zsrHFUcVVVil8_2DqAMbbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0hXNjd0OEQ1Skk&resourcekey=0-zsrHFUcVVVil8_2DqAMbbw" width="240" alt="1986 - M463AC - 8-109-02-002 - RII RIZ.jpg"></a><br><sub>1986|19 · 8-109-02-002 - RII RIZ · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-02-002%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDZ5NWtaYzV3cFU/view?resourcekey=0-AQcEH8XxTiwHxqdu0TCqCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDZ5NWtaYzV3cFU&resourcekey=0-AQcEH8XxTiwHxqdu0TCqCQ" width="240" alt="1986 - M463AC - 8-109-02-007 - NDMINAL VALUE.jpg"></a><br><sub>1986|19 · 8-109-02-007 - NDMINAL VALUE · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-02-007%20-%20NDMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFhPTDFvcjU5c2s/view?resourcekey=0-u5lMfI9zUOafFzORTD5joA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFhPTDFvcjU5c2s&resourcekey=0-u5lMfI9zUOafFzORTD5joA" width="240" alt="1986 - M463AC - 8-109-02-007 - RII RIZ.jpg"></a><br><sub>1986|19 · 8-109-02-007 - RII RIZ · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-02-007%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1daZFlKU1RRSGM/view?resourcekey=0-08ggQSH3dVT3rM-bvaofKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1daZFlKU1RRSGM&resourcekey=0-08ggQSH3dVT3rM-bvaofKg" width="240" alt="1986 - M463AC - 8-109-06-002 - RAS COMPONENT LAYOUT.jpg"></a><br><sub>1986|19 · 8-109-06-002 - RAS COMPONENT LAYOUT · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-06-002%20-%20RAS%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXlOMTNjSHNmMVk/view?resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXlOMTNjSHNmMVk&resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" width="240" alt="1986 - M463AC - 8-109-06-002.jpg"></a><br><sub>1986|19 · 8-109-06-002 · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-06-002%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcmFlZnFNeG4yN1E/view?resourcekey=0-Vta-_GHsSOhVtN6wyMBVSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcmFlZnFNeG4yN1E&resourcekey=0-Vta-_GHsSOhVtN6wyMBVSQ" width="240" alt="1986 - M463AC - 8-109-06-007 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1986|19 · 8-109-06-007 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-06-007%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMThKY01DNWllZTQ/view?resourcekey=0-BTOPlySjq4iBtzjxHToZsw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMThKY01DNWllZTQ&resourcekey=0-BTOPlySjq4iBtzjxHToZsw" width="240" alt="1986 - M463AC - 8-109-06-007 - DRI ENG.jpg"></a><br><sub>1986|19 · 8-109-06-007 - DRI ENG · <a href="SCHEMATICS/1986%20-%20M463AC%20-%208-109-06-007%20-%20DRI%20ENG%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOElpbVp3TXZHV0k/view?resourcekey=0-urGLoZg182p8hE-CKBWhWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOElpbVp3TXZHV0k&resourcekey=0-urGLoZg182p8hE-CKBWhWg" width="240" alt="1986 - M463AC - 463-04-009 - CONNECTOR REAR VIEW.jpg"></a><br><sub>1986|19 · 463-04-009 - CONNECTOR REAR VIEW · <a href="PINOUTS/1986%20-%20M463AC%20-%20463-04-009%20-%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

22 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | INPUT | in |  | medium |
| 2 | OUT | out |  | medium |
| 3 | OUT | out |  | medium |
| 4 | FB OUT | out |  | medium |
| 5 | OUT | out |  | medium |
| 6 | IN | in |  | medium |
| 7 | IN | in |  | medium |
| 8 | OUT | out |  | medium |
| 9 | CTL | control |  | medium |
| 10 | IN | in |  | medium |
| 13 | SHIELD | ground |  | medium |
| 14 | PREFADE IN | in |  | medium |
| 15 | FADER IN | in |  | medium |
| 16 | DIRECT OUT | out |  | medium |
| 17 | MONITOR OUT | out |  | medium |
| 18 | CTL COM | ground |  | medium |
| 19 | 25V | other |  | medium |
| 20 | ±COMMON | ground |  | medium |
| 21 | +25V | power |  | medium |
| 22 | CHASS/S GND | ground |  | medium |
| A | FB | other |  | medium |
| B | RS | other |  | medium |
| L | MI/M2 | other |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeFFEVjNBQ1NhcVE/view?resourcekey=0-8oemuXaawI6cPLvdb7zuCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeFFEVjNBQ1NhcVE&resourcekey=0-8oemuXaawI6cPLvdb7zuCA" width="240" alt="1986 - M463AC - Master Module (2).pdf"></a><br><sub>1986|19 · Master Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHVzSmk1UnRzODg/view?resourcekey=0-MFNDrGPjd-syKyFzMKE5Cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHVzSmk1UnRzODg&resourcekey=0-MFNDrGPjd-syKyFzMKE5Cg" width="240" alt="1986 - M463AC - Master Module.pdf"></a><br><sub>1986|19 · Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGtXQVVGZHJYVmM/view?resourcekey=0-vRXP85EfdV9EdJSqQNSeoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGtXQVVGZHJYVmM&resourcekey=0-vRXP85EfdV9EdJSqQNSeoA" width="240" alt="1986 - M463AC - P001 - Title Page.jpg"></a><br><sub>1986|19 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmlDZ0RBY0cwUWs/view?resourcekey=0-9TM3f2QVgEoJjs1KV0izwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmlDZ0RBY0cwUWs&resourcekey=0-9TM3f2QVgEoJjs1KV0izwQ" width="240" alt="1986 - M463AC - P002.jpg"></a><br><sub>1986|19 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVDY0TWRhTldFc1E/view?resourcekey=0-mXkZkM7iOthOlPbhBIiG8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVDY0TWRhTldFc1E&resourcekey=0-mXkZkM7iOthOlPbhBIiG8Q" width="240" alt="1986 - M463AC - P003 - 1-1.jpg"></a><br><sub>1986|19 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWW9EQnFkWUJGYmc/view?resourcekey=0-CCLMfxcwtRDqLv9pF62HPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWW9EQnFkWUJGYmc&resourcekey=0-CCLMfxcwtRDqLv9pF62HPw" width="240" alt="1986 - M463AC - P004 - 2-1.jpg"></a><br><sub>1986|19 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNmk3eHdQOS1NRVE/view?resourcekey=0-hTSMajF522K1ER0EgPN1dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNmk3eHdQOS1NRVE&resourcekey=0-hTSMajF522K1ER0EgPN1dg" width="240" alt="1986 - M463AC - P005 - 2-2.jpg"></a><br><sub>1986|19 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRVRONlBxOHR6aTQ/view?resourcekey=0-VwLzzEoDVdl0zvPVNxtm2Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRVRONlBxOHR6aTQ&resourcekey=0-VwLzzEoDVdl0zvPVNxtm2Q" width="240" alt="1986 - M463AC - P006 - 3-1.jpg"></a><br><sub>1986|19 · P006 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnMzSzUxM1FSRGs/view?resourcekey=0-WemArSMYbzVQkSKPUPjH2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnMzSzUxM1FSRGs&resourcekey=0-WemArSMYbzVQkSKPUPjH2g" width="240" alt="1986 - M463AC - P007 - 3-2.jpg"></a><br><sub>1986|19 · P007 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmJMeE9yaFhqczg/view?resourcekey=0-8WD5ECaHqWtwpT7HmP_cvw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmJMeE9yaFhqczg&resourcekey=0-8WD5ECaHqWtwpT7HmP_cvw" width="240" alt="1986 - M463AC - P008 - 3-3.jpg"></a><br><sub>1986|19 · P008 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSVBrcHFsdS1MNzQ/view?resourcekey=0-qLA8sdx97k2-CkICtUjifQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSVBrcHFsdS1MNzQ&resourcekey=0-qLA8sdx97k2-CkICtUjifQ" width="240" alt="1986 - M463AC - P009 - 3-4.jpg"></a><br><sub>1986|19 · P009 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0t2VEJZSUhzVXM/view?resourcekey=0-7q_c0kZEjqIEU1plruiYlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0t2VEJZSUhzVXM&resourcekey=0-7q_c0kZEjqIEU1plruiYlA" width="240" alt="1986 - M463AC - P010 8-109.jpg"></a><br><sub>1986|19 · P010 8-109</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1986 - M463AC - P011 - 8-109-1-1.jpg"></a><br><sub>1986|19 · P011 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1986 - M463AC - P012 - 8-109-1-2.jpg"></a><br><sub>1986|19 · P012 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1986 - M463AC - P013 - 8-109-2-1.jpg"></a><br><sub>1986|19 · P013 - 8-109-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1986 - M463AC - P014 - 8-109-2-2.jpg"></a><br><sub>1986|19 · P014 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1986 - M463AC - P015 - 8-109-2-3.jpg"></a><br><sub>1986|19 · P015 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1986 - M463AC - P016 - 8-109-2-4.jpg"></a><br><sub>1986|19 · P016 - 8-109-2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1986 - M463AC - P017 - 8-109-2-5.jpg"></a><br><sub>1986|19 · P017 - 8-109-2-5</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1986 - M463AC - 463-01-020 - INPUT FADER.kicad_sch](KICAD/1986%20-%20M463AC%20-%20463-01-020%20-%20INPUT%20FADER.kicad_sch)
- [1986 - M463AC - 463-01-020 - MASTER MODULE.kicad_sch](KICAD/1986%20-%20M463AC%20-%20463-01-020%20-%20MASTER%20MODULE.kicad_sch)
- [1986 - M463AC - 463-02-020 - LALL RESISTO ISK.kicad_sch](KICAD/1986%20-%20M463AC%20-%20463-02-020%20-%20LALL%20RESISTO%20ISK.kicad_sch)
- [1986 - M463AC - 463-02-020 - MASTER MODULE SCHEMATIC FONU.kicad_sch](KICAD/1986%20-%20M463AC%20-%20463-02-020%20-%20MASTER%20MODULE%20SCHEMATIC%20FONU.kicad_sch)
- [1986 - M463AC - 8-109-02-002 - OUTPUT AMPLIFIER CKDEAL SCHEMATIC.kicad_sch](KICAD/1986%20-%20M463AC%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20CKDEAL%20SCHEMATIC.kicad_sch)
- [1986 - M463AC - 8-109-02-002 - RII RIZ.kicad_sch](KICAD/1986%20-%20M463AC%20-%208-109-02-002%20-%20RII%20RIZ.kicad_sch)
- [1986 - M463AC - 8-109-02-007 - NDMINAL VALUE.kicad_sch](KICAD/1986%20-%20M463AC%20-%208-109-02-007%20-%20NDMINAL%20VALUE.kicad_sch)
- [1986 - M463AC - 8-109-02-007 - RII RIZ.kicad_sch](KICAD/1986%20-%20M463AC%20-%208-109-02-007%20-%20RII%20RIZ.kicad_sch)
- [1986 - M463AC - Master Module (2) p27.kicad_sch](KICAD/1986%20-%20M463AC%20-%20Master%20Module%20(2)%20p27.kicad_sch)
- [1986 - M463AC - Master Module p20.kicad_sch](KICAD/1986%20-%20M463AC%20-%20Master%20Module%20p20.kicad_sch)
- [1986 - M463AC - Master Module p27.kicad_sch](KICAD/1986%20-%20M463AC%20-%20Master%20Module%20p27.kicad_sch)
- [1986 - M463AC - Master Module p31.kicad_sch](KICAD/1986%20-%20M463AC%20-%20Master%20Module%20p31.kicad_sch)
- [M463AC.kicad_sym](KICAD/M463AC.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
