# Military-Rank-Web-Font-Icons
Font Icons That Include All US Armed Forces Ranks


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
![Chief Warrant Officer 2](http://puu.sh/hvWWQ/36978b4fdf.png) | Chief Warrant Officer 2 (CW2) | .rank-01-cw2
![Corporal](http://puu.sh/hvWYT/bee12f1922.png) | Coporal (Cpl) | .rank-01-e4
![Sergeant](http://puu.sh/hvXzi/68504c2d4f.png) | Sergeant (Sgt) | .rank-01-e5
![Staff Sergeant](http://puu.sh/hvXBN/d182ca352d.png) | Staff Sergeant (SSgt) | .rank-01-e6

- Warrant Officer                     =    .rank-01-w1
- Chief Warrant Officer 2             =    .rank-01-cw2
- Chief Warrant Officer 3             =    .rank-01-w1
- Chief Warrant Officer 4             =    .rank-01-cw2
- Chief Warrant Officer 5             =    .rank-01-cw5

> Note:
> Because W-1 and CWO3 are the same design but gold and silver, and CWO2 and CWO4 are the same design, I used the same SVG.  If you wish to distinguish between the two, you can use .rank-inverse along with the rank class.

### USMC - Officers

- 2nd Lieutenant                      =    .rank-01-o1
- 1st Lieutenant                      =    .rank-01-o2
- Captain                             =    .rank-01-o3
- Major                               =    .rank-01-o4
- Lieutenant Colonel                  =    .rank-01-o5
- Colonel                             =    .rank-01-o6
- Brigadier General                   =    .rank-01-o7
- Major General                       =    .rank-01-o8
- Lieutenant General                  =    .rank-01-o9
- General                             =    .rank-01-o10 

