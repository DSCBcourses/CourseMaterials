# DSCB 225 Course Resources

## Folder structure

- `Code/`  
  Analysis scripts, notebooks, and reusable functions (R, Python, etc.).

- `Data/`  
  Small/processed data that can reasonably live in git (CSV, RDS, small TIFFs, etc.).  
  If you use a similar structure for your own work, **do not** put huge raw data here; use a separate `LargeFiles/` or external storage and then add that folder to .gitignore.

- `Results/`  
  Output from analyses: figures, tables, summary data, etc.

- DSCB_Rstats.rproj file