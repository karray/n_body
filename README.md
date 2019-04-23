### Parallel N-Body Simulations
This is a simple example of an all-Pairs N-Body algorithm using OpenCL for simulation.

![](examples/stars.gif)

### Prerequisites ###
- python3
- OpenCL 
- pyopencl, websockets and numpy packages
### Usage ###
Starting OpenCL server
```bash
cd server
python3 server.py ../data/htw.csv
```
Starting web server
```bash
cd web
python3 -m http.server
```
Browse to http://127.0.0.1:8000