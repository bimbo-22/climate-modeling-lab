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

### 
— TASKS FOR ANALYSIS (12.5.2026)
* Create difference-plots that visualize the deviations between our run & the slabctrl
* Variables we should check – global: 
    2m Temperature above ground (2D)
    incoming SW radiation ground (2D)
    total cloud cover (2D) 
* Variables we should check – vertical profile (zonal mean): 
    temperature profile (2D)
    zonal wind (3D) – For the Jetstream 
* Make shure to run a statistical test on the significance of changes (p < 0.05)
* Compare the same months (Jan, Apr, Jul, Oct) for every year -> make GIFs out of that to visualize the evolution
    
— TIMELINE FOR ANALYSIS
