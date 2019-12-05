How to run and visualize graph in D3JS:
- Go to D3-Graph-Visualization folder from cloned repo
- Run this command to start simple HTTP server in that dir: python -m SimpleHTTPServer 8080
- Open ProcessDataSet.ipynb and run the cell with generate_d3js_json() function
- Take above func's json output and update D3-Graph-Visualization/graphFile.json with this 
- Open http://0.0.0.0:8080/ in browser to see the graph (You will need to disable cache using InspectElement->NetworkTab to see updated graph in browser)
