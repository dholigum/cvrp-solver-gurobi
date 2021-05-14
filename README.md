# CVRP Solver with Gurobi + Folium and OpenRouteServices
Capacitated Vehicle Routing Problem (CVRP) solver using Gurobi and Real World Map visualization using Folium and OpenRouteService

## Objective

1.	Calculate route travel
2.	Calculate how much transport cargo needed
3.	Solver map visualization
4.	Real-world map integration

## Mathematical Model

<p align="center">
  <img alt="CVRP Mathematical Model" src="https://github.com/dholigum/cvrp-solver-gurobi/blob/master/cvrp-math-model.png?raw=true" width="60%">
</p>

## How to use

1. Clone this repo
2. Install depedencies `pip install -r requirements.txt`
3. Import your dataset into this project directory
4. Open `CVRP-Gurobi.ipynb` files
5. Edit cells 4 and 5 with your dataset
6. Add your own OpenRouteServices API Key


## Result

Matplotlib solver map visualization & Folium Real-world visualization
<p align="center">
  <img alt="Matplotlib solver map visualization" src="https://github.com/dholigum/cvrp-solver-gurobi/blob/master/result/matplotlib-result.jpeg?raw=true" width="35%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Folium Real-world visualization" src="https://github.com/dholigum/cvrp-solver-gurobi/blob/master/result/folium-map.png?raw=true" width="55%">
</p>

Detail how much transport cargo needed and its route path
![rpute path](https://github.com/dholigum/cvrp-solver-gurobi/blob/master/result/detail-rute.png?raw=true)

Detail how much distance for each route and Total distance
![distance for each route](https://github.com/dholigum/cvrp-solver-gurobi/blob/master/result/panjang-rute.png?raw=true)
![Total distance](https://github.com/dholigum/cvrp-solver-gurobi/blob/master/result/total-distance.png?raw=true)
