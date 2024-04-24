## CNN Configuration
The general parameter setting for CNN model can be found in "CNN_config.ini".

## Training
```
python train.py --BENCHMARKS_DIR=data/ --benchmark_name=oglcnac --site=S,T --w=8 --PLM=ProtALBERT --config_file=CNN_config.ini --model_save_path=models/
```
For help, run:
```
python train.py --help
```
## Prediction
```
python predict.py --BENCHMARKS_DIR=data/ --benchmark_name=oglcnac --site=S,T --w=8 --PLM=ProtBert  --model_path=./models/my_PTG-PLM_ProtALBERT/
```
For help, run:
```
python predit.py --help
```
## For Original Methodology of Predicting PTM sites, Cite this paper:
Alkuhlani A, Gad W, Roushdy M, Voskoglou MG, Salem A-bM. PTG-PLM: Predicting Post-Translational Glycosylation and Glycation Sites Using Protein Language Models and Deep Learning. Axioms. 2022; 11(9):469. https://doi.org/10.3390/axioms11090469

