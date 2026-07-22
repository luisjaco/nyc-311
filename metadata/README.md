In this folder is a file containing of the metadata of the Synthea command executed to generate the 
data contained in this directory. 

Running this command will result in a ~5.6GB folder of outputs. As such it has been excluded from 
this repository. 

You can read more about Synthea at [this](https://github.com/synthetichealth/synthea) link. 

Sample command (with `exporter.csv.export = true`):
```
./run_synthea -p 1000 "New York"
```