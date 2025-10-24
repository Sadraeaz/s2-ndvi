# Sentinel-2 NDVI (GEE)

Quick Google Earth Engine script to compute and visualize NDVI over an AOI.  
Time-series chart + median NDVI layer.

## How to use
1. Open the [GEE Code Editor](https://code.earthengine.google.com/).
2. Create a new script and paste the contents of `s2-ndvi.js`.
3. Make sure you have a `geometry` in your workspace (draw or import).  
4. Tweak the **Editable params** block at the top:
   - `AOI_NAME`, `START_DATE`, `END_DATE`, `CLOUD_MAX`, etc.
5. Run the script:
   - Check the time-series in the Console.
   - View the NDVI map + legend in the Map view.
6. (Optional) Uncomment the `Export.image.toDrive` block to save a GeoTIFF.

## Why this repo
- Keeps the script versioned and shareable.
- Minimal, not over-engineered, and keeps my original style.

## License
MIT (or anything you prefer)
