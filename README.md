POI Clustering and Visualization in Cologne, Germany

This project focuses on clustering Points of Interest (POIs) in Cologne, Germany, using OpenStreetMap (OSM) data and K-means clustering. The goal is to analyze and visualize various POIs, categorized into different amenity types, and identify spatial clusters.

Features
- Fetches POI data from OpenStreetMap for various amenities like restaurants, parks, libraries, cinemas, etc.
- Applies K-means clustering to categorize POIs based on geographic coordinates (latitude and longitude).
- Visualizes the clustered POIs with scatter plots.
- Saves clustered data to CSV for further analysis.
- Combines POI visualizations with custom images (e.g., logos or annotations).

Tools & Libraries Used
- osmnx: For retrieving geographic data from OpenStreetMap.
- scikit-learn: For implementing K-means clustering.
- matplotlib: For visualization of clustered data.
- Pillow: For overlaying external images onto plots.
- pandas: For data manipulation and storage.
- geopandas: For geographic data handling.
  
How to Run
1. Clone this repository:
git clone https://github.com/your-username/poi-clustering-cologne.git
cd poi-clustering-cologne
2. Install dependencies:
pip install -r requirements.txt
3. Run the script:
python poi_clustering.py
4. View the output:
Clustered POI data is saved to a CSV file: clustered_poi_data.csv
A scatter plot showing the clusters is displayed.

Project Structure

poi-clustering-cologne/
│
├── poi_clustering.py      # Main script for fetching, clustering, and visualizing POIs
├── requirements.txt       # List of required Python libraries
├── README.md              # Project documentation
├── images/                # Folder for storing external images for plots
└── output/                # Folder for saving results (e.g., clustered data CSV)

Visualization Example
- Scatter Plot of Clusters
- POI Map with Custom Image

Customization

You can customize the script by modifying:
- place_name: Change the city or location to analyze POIs in different areas.
- tags_poi: Add or remove amenity types to include specific POIs of interest.
- num_clusters: Adjust the number of clusters for K-means.


License

This project is licensed under the MIT License.
