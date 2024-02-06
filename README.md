# Setup
- Prepare the `graphdb.properties`:

```sh
cp graphdb.properties.sample graphdb.properties
```

- Start GraphDB with the following script executed from this folder

```sh
docker build --tag graphdb .
docker compose up -d graphdb
```

- If you use conda, create and activate a new conda env (e.g. `conda create -n graph_ontotext_graphdb_qa python=3.9.18`). Install the following libraries:

```sh
pip install jupyter==1.0.0
pip install openai==1.6.1
pip install rdflib==7.0.0
pip install langchain-openai==0.0.2
pip install langchain
```

- Run Jupyter with 

```sh
jupyter notebook
```

# Specifying the Ontology
