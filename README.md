# 🍔 McDonald's Market Segmentation (Python)

**Python replication** of the McDonald's segmentation case study from *Market Segmentation Analysis* (Dolnicar et al., 2018). Uses survey data to identify consumer segments via:

- **PCA** (Perceptual Mapping)  
- **k-Means** & **Mixture Models**  
- **Descriptor Analysis** (Age/Gender/Like)  

## Data
**Dataset**: `mcdonalds.csv`  
**Variables**:
- **11 Binary Attributes**: `yummy`, `convenient`, ..., `disgusting` (Yes/No)
- **Descriptors**: `Like` (-5 to +5), `Age`, `Gender`, `VisitFrequency`

 ## Dependencies
- scikit-learn 1.0+  # PCA, k-Means, Mixture Models
- pandas 1.3+       # Data manipulation
- matplotlib 3.5+   # Plotting
- seaborn 0.11+     # Enhanced visuals
- statsmodels       # Mosaic plots
