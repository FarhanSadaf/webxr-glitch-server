# WebXR sensor data collection server 
Server-side code of [webxr-vr](https://github.com/FarhanSadaf/webxr-vr), hosted on `Glitch`.

## Endpoints
- WebSocket: `wss://[project_name].glitch.me/`
- get `/download`: Downloads *sensor_data.csv* file, and clears the buffer
- get `/clear`: Clears the data buffer

![Glitch](/public/glitch-1.png)
![Glitch /download](/public/glitch-2.png)