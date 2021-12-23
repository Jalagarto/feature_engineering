# feature_engineering

Basic repo for automating some feature engineering operations.

### TODOES:
1. Filtering  
    1 Null numbers  
    2 Empty rows  
    3 Corrupted data  
    4 etc.  
2. EDA: Basic Explanatory Data Analysis
3. Normalization (options use skicit)

Structure considerations:
1. Use an instructions file to tell main.py what to do (too many options otherwise).  
2. Add an argparse option as well, so we can decide to use instructions file or argparse.  
If we use argparse, default values will be the ones in the instructions file (so maybe use both?).  
So use either instructions or instructions and argparse on top.  
3. built it for multiple purposes: Start with Feat_Eng. for Tabular Data, then expand to time series Datasets.
