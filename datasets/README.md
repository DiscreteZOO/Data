# Datasets

Each `.json` file describes a dataset with a dictionary containing three keys, `classes`, `include`, `objects`.

* `classes` lists the classes deriving from [`ZooObject`](https://github.com/DiscreteZOO/DiscreteZOO-spec/blob/master/ZooObject.json) which are described by this dataset.
* `include` lists the datasets whose objects will be included in the current dataset.
* `objects` lists the unique IDs of the objects which will be included in the current dataset.
