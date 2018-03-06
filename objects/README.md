# Objects

Objects are stored as JSON files `ALGORITHM/XY/REST`, where `XY` are the first two nibbles of the unique ID, `REST` are the remaining nibbles, and `ALGORITHM` is the algorithm used to produce the unique ID.

Each file contains a dictionary with key corresponding to the names of the classes, and values being dictionaries of attribute names mapping to their values. Additionally, the key `_ref` maps to a list of unique IDs of objects referencing the current object.
