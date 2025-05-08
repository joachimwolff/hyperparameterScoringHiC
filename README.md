## Scoring Matrices
Run the “scoreMatrices.ipynb” notebook on a folder with predicted Hi-C matrices in .cool format. The data is available on zenodo

## Human Ranking
Use image-ranker (https://github.com/QuentinWach/image-ranker) to rank the matrices, then import the results into the same notebook. To rank the matrices, the predicted Hi-C matrices must be plotted, we used pyGenomeTracks for this, but any other tool is fine too.

## Regression Models
Create regression models by running “regressionModels.ipynb.”

## Dependencies
The main dependency is the  Hi-cGAN repository (https://github.com/joachimwolff/Hi-cGAN) repo, with additional requirements detailed in the notebooks.

## Testing
Run the “hicOptimize” tool from the Hi-cGAN repository to test the models.

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


## Evaluations
The notebooks “50kb_vs_elo” and “100kb_vs_elo” evaluate the model performance on 50kb and 100kb resolution matrices, respectively.