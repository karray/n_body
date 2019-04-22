### Parallel N-Body Simulations
This is a simple example of an all-Pairs N-Body algorithm using OpenCL for simulation.
### Usage ###
Starting OpenCL server
```bash
cd server
python server.py ../data/solar.csv
```
Starting web server
```bash
cd web
# python 2
python -m SimpleHTTPServer
# python 3
python3 -m http.server
```
Browse to http://127.0.0.1:8000