# Military-Rank-Web-Font-Icons
Font Icons That Include All US Armed Forces Ranks

![Miliary Rank Icons](http://puu.sh/hHF6r/d93350ae0c.jpg)


## Usage


```
        <i class="rank rank-01-e7"></i> GySgt Edward Jones
```

### Breakdown of class structure

- All ranks have a 'rank-' prefix

- Next two digits represent military branch
	- USMC - 01
	- Navy - 02 (Only Navy ranks have an additional 2 digits after branch to represent MOS)
		- General rank - 00
		- Hospital Corpsman - 01
		- Special Warfare Operator - 02
		- ...More to come!
	- Army - 03
	- Air Force - 04

- Last characters represent the paygrade of the rank you want to show

- If a seperate rank has the same paygrade, it's added with another dash and an additional number



### Reference guide for all Paygrade codes:
[Military Ranks List](http://www.militaryfactory.com/ranks/)

**Please let me know if you have any feedback or I've made an error for a specfic rank.**
**Thanks!**

## CSS classes of current icons


### USMC - Enlisted

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
 | Private (Pvt) | 'nothing'
![Private First Class](http://puu.sh/hvWN6/f2dc8530be.png) | Private First Class (PFC) | .rank-01-e2
![Lance Coporal](http://puu.sh/hvWWQ/36978b4fdf.png) | Lance Coporal (LCpl) | .rank-01-e3
![Corporal](http://puu.sh/hvWYT/bee12f1922.png) | Coporal (Cpl) | .rank-01-e4
![Sergeant](http://puu.sh/hvXzi/68504c2d4f.png) | Sergeant (Sgt) | .rank-01-e5
![Staff Sergeant](http://puu.sh/hvXBN/d182ca352d.png) | Staff Sergeant (SSgt) | .rank-01-e6
![Gunnery Sergeant](http://puu.sh/hvXG9/dd8b2af6cf.png) | Gunnery Sergeant (GySgt) | .rank-01-e7
![Master Sergeant](http://puu.sh/hvXK0/31070e0b38.png) | Master Sergeant (MSgt) | .rank-01-e8-1
![First Sergeant](http://puu.sh/hvXWs/80c3630d0c.png) | First Sergeant (1stSgt) | .rank-01-e8-2
![Master Gunnery Sergeant](http://puu.sh/hvZ8Q/1efa65a1b5.png) | Master Gunnery Sergeant (MGySgt) | .rank-01-e9-1
![Sergeant Major](http://puu.sh/hvZ7W/f901db13d0.png) | Sergeant Major (SgtMaj) | .rank-01-e9-2
![Sergeant Major of the Marine Corps](http://puu.sh/hvZ9A/68b234ddaf.png) | Sergeant Major of the Marine Corps (SgtMajMarCor) | .rank-01-e9-3


### USMC - Warrant Officers

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
![Warrant Officer](http://puu.sh/hw0aO/aff66baa15.png) | Warrant Officer (W1) | .rank-01-w1
![Chief Warrant Officer 2](http://puu.sh/hHFeB/8a25a48186.png) | Chief Warrant Officer 2 (CW2) | .rank-01-cw2
![Chief Warrant Officer 3](http://puu.sh/hw0aO/aff66baa15.png) | Chief Warrant Officer 3 (CW3) | .rank-01-w1 rank-inverse-warrant
![Chief Warrant Officer 4](http://puu.sh/hHFeB/8a25a48186.png) | Chief Warrant Officer 4 (CW4) | .rank-01-cw2 rank-inverse-warrant
![Chief Warrant Officer 5](http://puu.sh/hHAg6/1d127b0625.png) | Chief Warrant Officer 5 (CW5) | .rank-01-cw5

> Note:
> Because W-1 and CWO3 are the same design but gold and silver, and CWO2 and CWO4 are the same design, I used the same SVG.  If you wish to distinguish between the two, you can use .rank-inverse-warrant along with the rank class.

### USMC - Officers

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
![2nd Lieutenant](http://puu.sh/hHAnp/0dffb56b60.png) | 2nd Lieutenant (2ndLt) | .rank-01-o1
![1st Lieutenant](http://puu.sh/hHAnp/0dffb56b60.png) | 1st Lieutenant (1stLt) | .rank-01-o2
![Captain](http://puu.sh/hHAs0/44da26e8a3.png) | Captain (Capt) | .rank-01-o3
![Major](http://puu.sh/hHAu5/cdcc8b0e10.png) | Major (Maj) | .rank-01-o4
![Lieutenant Colonel](http://puu.sh/hHAu5/cdcc8b0e10.png) | Lieutenant Colonel (LtCol) | .rank-01-o5
![Colonel](http://puu.sh/hHAAm/d1e9a8c9e2.png) | Colonel (Col) | .rank-01-o6
![Brigadier General](http://puu.sh/hHAFo/b5e3a2dcc5.png) | Brigadier General (BGen) | .rank-01-o7
![Major General](http://puu.sh/hHAKY/9674063fc8.png) | Major General (MajGen) | .rank-01-o8
![Lieutenant General](http://puu.sh/hHAJV/2064ddabd7.png) | Lieutenant General (LtGen) | .rank-01-o9
![General](http://puu.sh/hHAQj/bee83931f4.png) | General (Gen) | .rank-01-o10

### Navy - Enlisted

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
 | Seaman Recruit (SR) | 'nothing'
![Seaman Apprentice](http://puu.sh/hHBjv/b1608db05b.png) | Seaman Apprentice (SA) | .rank-02-00-e2
![Seaman](http://puu.sh/hHBmL/10a270037f.png) | Seaman (SN) | .rank-02-00-e3
![Petty Officer 3rd Class](http://puu.sh/hHBpf/444cdfa4f0.png) | Petty Officer 3rd Class (PO3) | .rank-02-00-e4
![Petty Officer 2nd Class](http://puu.sh/hHBr5/90efcc1eb9.png) | Petty Officer 2nd Class (PO2) | .rank-02-00-e5
![Petty Officer 1st Class](http://puu.sh/hHBti/68ca4205b1.png) | Petty Officer 1st Class (PO1) | .rank-02-00-e6
![Chief Petty Officer](http://puu.sh/hHBvO/e10d70c5ec.png) | Chief Petty Officer (CPO) | .rank-02-00-e7
![Senior Chief Petty Officer](http://puu.sh/hHByL/db430a8ee2.png) | Senior Chief Petty Officer (SCPO) | .rank-02-00-e8
![Master Chief Petty Officer](http://puu.sh/hHBBf/db78e44f79.png) | Master Chief Petty Officer (MCPO) | .rank-02-00-e9-01
![Master Chief Petty Officer of the Navy](http://puu.sh/hHBGS/bd954e0d09.png) | Master Chief Petty Officer of the Navy (MCPON) | .rank-02-00-e9-01

### Navy - Enlisted - Hospital Corpsman

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
 | Hospitalman Recruit (HR) | 'nothing'
![Hospitalman Apprentice](http://puu.sh/hHBOX/025de1098d.png) | Hospitalman Apprentice (HA) | .rank-02-01-e2
![Hospitalman ](http://puu.sh/hHBRe/dd1d0329ea.png) | Hospitalman  (HN) | .rank-02-01-e3
![Hospital Corpsman 3rd Class](http://puu.sh/hHBUp/3d0315801f.png) | Hospital Corpsman 3rd Class (HM3) | .rank-02-01-e4
![Hospital Corpsman 2nd Class](http://puu.sh/hHBWX/d9e8b7628f.png) | Hospital Corpsman 2nd Class (HM2) | .rank-02-01-e5
![Hospital Corpsman 1st Class](http://puu.sh/hHC0b/7c1cfe4f1d.png) | Hospital Corpsman 1st Class (HM1) | .rank-02-01-e6
![Chief Hospital Corpsman](http://puu.sh/hHC2P/c40bcd8ada.png) | Chief Hospital Corpsman (HMC) | .rank-02-01-e7
![Senior Chief Hospital Corpsman](http://puu.sh/hHC6e/0a1a95ba49.png) | Senior Chief Hospital Corpsman (HMCS) | .rank-02-01-e8
![Master Chief Hospital Corpsman](http://puu.sh/hHC8U/17b9f71b66.png) | Master Chief Hospital Corpsman (HMCM) | .rank-02-00-e9


### Navy - Enlisted - Special Warfare Operator

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
![Special Warfare Operator, 3rd Class](http://puu.sh/hHCGo/4ec339c95d.png) | Special Warfare Operator, 3rd Class (SO3) | .rank-02-02-e4
![Special Warfare Operator, 2nd Class](http://puu.sh/hHCJD/0bae389565.png) | Special Warfare Operator, 2nd Class (SO2) | .rank-02-02-e5
![Special Warfare Operator, 1st Class](http://puu.sh/hHCN3/f52762020f.png) | Special Warfare Operator, 1st Class (SO1) | .rank-02-02-e6
![Chief Special Warfare Operator](http://puu.sh/hHCQi/fea5c604c6.png) | Chief Special Warfare Operator (SOC) | .rank-02-02-e7
![Senior Chief Special Warfare Operator](http://puu.sh/hHCXn/43d3519d21.png) | Senior Chief Special Warfare Operator (SOCS) | .rank-02-02-e9
![Master Chief Special Warfare Operator](http://puu.sh/hHD00/159d0283e1.png) | Master Chief Special Warfare Operator (SOCM) | .rank-02-02-e9-1

### Army - Enlisted

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
 | Private (PVT) | 'nothing'
![Private](http://puu.sh/hHDaA/c2eb611abb.png) | Private (PV2) | .rank-03-e2
![Private First Class](http://puu.sh/hHDd9/85b8a61623.png) | Private First Class (PFC) | .rank-03-e3
![Specialist](http://puu.sh/hHDfc/256110965f.png) | Specialist (SPC) | .rank-03-e4-2
![Corporal](http://puu.sh/hHDjL/6a4136bb17.png) | Corporal (CPL) | .rank-03-e4-1
![Sergeant](http://puu.sh/hHDmk/676175314c.png) | Sergeant (SGT) | .rank-03-e5
![Staff Sergeant](http://puu.sh/hHDp7/cbdf9cd107.png) | Staff Sergeant (SSG) | .rank-03-e6
![Sergeant First Class](http://puu.sh/hHDsQ/70071d9809.png) | Sergeant First Class (SFC) | .rank-03-e7
![Master Sergeant](http://puu.sh/hHDvz/0553f11f4b.png) | Master Sergeant (MSG) | .rank-03-e8-2
![First Sergeant](http://puu.sh/hHDxx/ed87ffff0a.png) | First Sergeant (1SG) | .rank-03-e8-1
![Sergeant Major](http://puu.sh/hvZ7W/f901db13d0.png) | Sergeant Major (SGM) | .rank-03-e9-3
![Command Sergeant Major](http://puu.sh/hHDCF/92a3f4f6a3.png) | Command Sergeant Major (CSM) | .rank-03-e9-2
![Sergeant Major of the Army](http://puu.sh/hHDEx/fc91add310.png) | Sergeant Major of the Army (SMA) | .rank-03-e9-1


### Air Force - Enlisted

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
 | Airman Basic (AB) | 'nothing'
![Airman](http://puu.sh/hHEpJ/3888b172eb.png) | Airman (Amn) | .rank-04-e3
![Airman First Class](http://puu.sh/hHEr8/66db600f07.png) | Airman First Class (A1C) | .rank-04-e2
![Senior Airman](http://puu.sh/hHEtd/6b948467ae.png) | Senior Airman (SrA) | .rank-04-e4
![Staff Sergeant](http://puu.sh/hHEvx/943557eda8.png) | Staff Sergeant (SSgt) | .rank-04-e5
![Technical Sergeant](http://puu.sh/hHEyb/8c9afae6a5.png) | Technical Sergeant (TSgt) | .rank-04-e6
![Master Sergeant](http://puu.sh/hHEAK/65e5a6342c.png) | Master Sergeant (MSgt) | .rank-04-e7
![Senior Master Sergeant](http://puu.sh/hHEEA/7f2c23ad5c.png) | Senior Master Sergeant (SMSgt) | .rank-04-e8
![Chief Master Sergeant](http://puu.sh/hHEJ8/b18b04a009.png) | Chief Master Sergeant (CMSgt) | .rank-04-e9-1
![Chief Master Sergeant](http://puu.sh/hHEPk/42ac21ee91.png) | Chief Master Sergeant (CMSgt) | .rank-04-e9-2
![Command Chief Master Sergeant](http://puu.sh/hHERc/cd2b5b0232.png) | Command Chief Master Sergeant (CCM) | .rank-04-e9-3
![Chief Master Sergeant of the Air Force](http://puu.sh/hHERF/452dff6280.png) | Chief Master Sergeant of the Air Force (CMSAF) | .rank-04-e9-4


## Additional Classes

### CSS Sizes

- .rank-2x -> .rank-14x

- .rank-fw
- .rank-border
- .rank-spin
- .rank-rotate-90
- .rank-rotate-180
- .rank-rotate-270
- .rank-flip-horizontal
- .rank-flip-vertical
- .rank-stack
- .rank-inverse
- .rank-inverse-warrant


# License 

MIT License
