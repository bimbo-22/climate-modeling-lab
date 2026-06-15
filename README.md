# climate-modeling-lab
A world with no Montreal Protocol

## Setup and Excecution

### Requirements: 
This project is managed with uv

Install [uv](https://docs.astral.sh/uv/getting-started/installation/):
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```



### install the dpendencies
```bash
uv sync
```


### Here's our projedct structure

```bash
.
├── climate_model
├── icon_grid_G.nc
├── LessOzone_2000-2005_2d.nc
├── LessOzone_2000-2005_3d.nc
├── LessOzone_Real_2D_2000-2035.nc
├── LessOzone_Real_3D_2000-2035.nc
├── main.py
├── Ozone-manipulator.ipynb
├── plots
│   ....
├── PlottingRoutine_Global.ipynb
├── PlottingRoutine_VerticalProfile.ipynb
├── pyproject.toml
├── README.md
├── script_s2026.pdf
├── slabctr_2D_2000-2035.nc
├── slabctr_3D_REGRID_2000-2035.nc
└── uv.lock
```

### The path an the vsc where our data is
```
/gpfs/data/fs72044/icon06/experiments/LessOzone_Real_V1
```

### The path of Aikos slabt control run 
```
/gpfs/data/fs72044/avoigt_teach/experiments/s2026/slabctr
```


### TASKS FOR ANALYSIS (12.5.2026)
* Create difference-plots that visualize the deviations between our run & the slabctrl
* Variables we should check – global: 
    * 2m Temperature above ground (2D)
    * incoming SW radiation ground (2D)
    * Precipitation Patterns (2D)
* Variables we should check – vertical profile (zonal mean): 
    * temperature profile (3D)
    * zonal wind at 300 hPa(3D) – For the Jetstream 
* Make shure to run a statistical test on the significance of changes (p < 0.05)
* Compare the same months (Jan, Apr, Jul, Oct) for every year -> make GIFs out of that to visualize the evolution


### TIMELINE FOR ANALYSIS
