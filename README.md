Starting point is the cleaned ML-ready HydPARK database: HYDPARK_ML_ready.csv (from https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.9b02971)
Pre-extracted MP data is in ElementalH_Ef_MP.csv (to reproduce you will need your own API key)
Main jupyter notebook is metal_hydride_ML_v2.ipynb which contains:
- Models to reproduce the previous paper (note models need to be retrained from scratch due to file size limitations on free github)
- Models trained with augmented data (some new HEA data) and new features extracted from MP
- All subsequent analysis and plotting functions to reproduce HEA hydride paper (xxxxx)

