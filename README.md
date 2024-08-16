# Topic network graphs
Computer assisted methods for creating topic network graphs and their applications in bibliometrics

```
git clone git@github.com:aot29/topic_network_graphs.git
```

## Using Conda
```
conda create -n topic_network_graphs  python=3.12.2
conda activate topic_network_graphs
cd topic_network_graphs/
pip install -r requirements.txt
```

```
conda activate topic_network_graphs
jupyter lab
```

## Using plain Python
```
python -m venv topic_network_graphs
source topic_network_graphs/bin/activate
cd topic_network_graphs/
pip install -r requirements.txt
```

```
source topic_network_graphs/bin/activate
cd topic_network_graphs/
jupyter lab
```
## Data
Create a data folder (will not be committed)

Use the OpenAlex Web interface to select and downloade the data: 
https://openalex.org/works?page=1&filter=default.search%3Atopic%20network%20graph%20and%20bibliometrics,type%3Atypes%2Farticle
(72MB), put it in the data folder

## Notebooks
