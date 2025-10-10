
## Human Ranking
Use image-ranker (https://github.com/QuentinWach/image-ranker) to rank the matrices, then import the results into the same notebook. To rank the matrices, the predicted Hi-C matrices must be plotted, we used pyGenomeTracks for this, but any other tool is fine too.

## Hi-C matrices similarity scores
Run 3DChromatin Replicate (GenomeDISCO, HiCSpectrum, QuASAR-Rep), HiCRep (Python version), ENT3C, Hi-cGAN (Pearson AUC) and HiCExplorer hicFindTADs for the three TAD scores: TAD fraction, TAD fraction exact match and TAD score MSE

## Regression Models
Create regression models by running “regressionModels.ipynb.”

## Dependencies
The main dependency is the  Hi-cGAN repository (https://github.com/joachimwolff/Hi-cGAN) repo, with additional requirements detailed in the notebooks.


### Additional Dependencies

- numpy  
- pandas  
- scikit-learn  
- matplotlib  
- joblib  
- tabpfn  
- xgboost  
- catboost  
- pyGenomeTracks  
- hicrep  
- hicexplorer  
- cooler  
- scipy  
