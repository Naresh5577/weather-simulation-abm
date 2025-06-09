#   Rename columns
weather_df = weather_df.rename(columns={
    't2m': 'Temperature', 
    'd2m': 'Dewpoint', 
    'msl': 'Mean Sea Level Pressure', 
    'sst': 'Sea Surface Temperature',
    'sp': 'Surface Pressure',
    'u100': 'East Wind Speed',
    'v100': 'North Wind Speed',
    'crr': 'Convective Rain Rate',
    'cvh': 'High Vegetation Cover',
    'cvl': 'Low Vegetation Cover',
    'tvh': 'Type of High Vegetation',
    'tvl': 'Type of Low Vegetation',
    'z': 'Geopotential',
    'tp': 'Total Precipitation',
    'cp': 'Convective Precipitation',
    'lsp': 'Large Scale Precipitation' })
