# Parcelization-Land-Use-Infrastructure-Planning

These scripts were created for the California Public Utilities Commission Integrated Resource Plan for the 2024-2025 Transmission Planning Process as part of the resource-to-busbar mapping effort. They calculate parcelization, a measure of the average number of unique parcels in an area, for long-term electric system planning. They are stored here as supporting material for a report which describes the methodology and purpose of parcelization in greater detail (https://www.energy.ca.gov/publications/2023/calculating-parcelization-electric-system-planning).  

Parcelization_Part1_MergeCounties.ipynb performs a series of data preparation steps to create the foundational dataset that is needed to calculate parcelization. Raw parcel data is combined so that each county contains the necessary parcels needed to perform the parcelization calculation, including those parcels of adjacent counties that will impact the parcelization measure inside the county. The second script, Parcelization_Part2_MainSteps.ipynb, performs the main steps to calculate parcelization for each county. All counties are merged into a single map.   


We are grateful to the ICF, E&P GIS Team Lead and Staff, Eric Link and Greg Nichols, for their technical support and insight into this method. 
