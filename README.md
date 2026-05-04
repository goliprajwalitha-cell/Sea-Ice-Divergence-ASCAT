# Sea-Ice-Divergence-ASCAT
Sea Ice divergence calculated from ASCAT (Metop-B/C) data

Sea ice divergence is calculated using drift vectors from the EUMETSAT OSISAF OSI-405-d dataset.
While the original dX and dY vectors are provided in the NSIDC grid, they must be transformed to the EASE grid to calculate divergence.

However, a methodological discrepancy exists: 
calculating divergence directly on the NSIDC grid before resampling to the EASE grid yields different results compared to transforming vectors first.

Therefore, the choice of processing order must be carefully considered.
