# Parcelization-Land-Use-Infrastructure-Planning

These scripts were created for the California Public Utilities Commission Integrated Resource Plan for the 2024-2025 Transmission Planning Process as part of the resource-to-busbar mapping effort. The scripts calculate parcelization, a measure of the average number of unique parcels in an area, for long-term electric system planning. 

Parcelization_Part1_MergeCounties.ipynb performs a series of data preparation steps to create the foundational dataset that is needed to calculate parcelization. Raw parcel data is combined so that each county contains the necessary parcels needed to perform the parcelization calculation, including those parcels of adjacent counties that will impact the parcelization measure inside the county. The second script, Parcelization_Part2_MainSteps.ipynb, performs the main steps to calculate parcelization for each county. All counties are merged into a single map.   

A report describing the methodology and purpose in greater detail is found at https://www.energy.ca.gov/publications/2023/calculating-parcelization-electric-system-planning. 

We are grateful to the ICF, E&P GIS Team Lead and Staff, Eric Link and Greg Nichols, for their support in supplying the overall method procedure. 
