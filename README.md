## Examples of MLFlow projects

Setting local environment
```shell
virtualenv -p python3 ./.env
source ./.env/bin/activate
pip install mlflow
```

Running with system python
```shell
cd ./system
mlflow run . -e download --no-conda
mlflow run . -e train --no-conda
```

Running with docker
```shell
cd ./docker
mlflow run . -e download
mlflow run . -e train
```