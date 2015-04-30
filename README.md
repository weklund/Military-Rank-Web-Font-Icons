# Military-Rank-Web-Font-Icons
Font Icons That Include All US Armed Forces Ranks


## Usage


```
        <i class="rank rank-01-e7"></i> Bob
```

### Breakdown of class structure

- All ranks have a 'rank-' prefix
- Next two digits represent military branch ( Currently just USMC(01) and hospital corpsman(02) )
- Last characters represent the paygrade of the rank you want to show

[Military Ranks List](http://www.militaryfactory.com/ranks/)

## CSS classes of current icons


### USMC - Enlisted

Icon | Rank | CSS Mapping
------------ | ------------- | -------------
![Private First Class](http://puu.sh/hvWN6/f2dc8530be.png) | Private First Class (PFC) | .rank-01-e2
![Lance Coporal](http://puu.sh/hvWWQ/36978b4fdf.png) | Lance Coporal (LCpl) | .rank-01-e3
![Corporal](http://puu.sh/hvWYT/bee12f1922.png) | Coporal (Cpl) | .rank-01-e4


- Private                             =    Nothing
-  Private First Class                 =    .rank-01-e2
- Lance Coporal                       =    .rank-01-e3
- Corporal                            =    .rank-01-e4
- Sergeant                            =    .rank-01-e5
- Staff Sergeant                      =    .rank-01-e6
- Gunnery Sergeant                    =    .rank-01-e7
- Master Sergeant                     =    .rank-01-e8-1
- First Sergeant                      =    .rank-01-e8-2
- Master Gunnery Sergeant             =    .rank-01-e9-1
- Sergeant Major                      =    .rank-01-e9-2
- Sergeant Major of the Marine Corps  =    .rank-01-e9-3


### USMC - Warrant Officers

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

