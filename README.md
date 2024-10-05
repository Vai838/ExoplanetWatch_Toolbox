---

# ExoplanetWatchToolbox

**Description:**

The ExoplanetWatchToolbox is a comprehensive Jupyter Notebook designed for citizen scientists and astronomy enthusiasts participating in the Exoplanet Watch program. This toolbox facilitates the analysis and visualization of astronomical data, allowing users to compare FITS files and star charts side by side. With functionalities to obtain star coordinates, clean images, and extract vital header information, this tool enhances the study and observation of exoplanets. This toolbox can be used along side [local EXOTIC pipeline](https://exoplanets.nasa.gov/exoplanet-watch/exotic/install-locally/#2-1) which is a part of the [Exoplanet Watch](https://exoplanets.nasa.gov/exoplanet-watch/exotic/welcome/) Citizen Science Programme. This toolbox have been modelled after [EXOTIC Standard](https://colab.research.google.com/drive/1CNRbMQC0FmiVC9Pxj_lUhThgXqgbrVB)

---

## Features

- **FITS File Visualization:** View FITS images with WCS overlays for accurate representation of celestial objects.
- **Star Chart Comparison:** Compare star charts with observed images to identify and locate exoplanet candidates.
- **Star Coordinate Extraction:** Easily obtain XY coordinates of stars within the field of view.
- **Image Cleaning:** Implement basic image processing techniques to enhance the clarity of astronomical images.
- **Header Information Retrieval:** Access and display important header information from FITS files, including observation dates and telescope parameters.

---

## Installation

To use this toolbox, ensure you have Python installed along with the required libraries. You can install the necessary dependencies using pip:

```bash
pip install notebook astropy matplotlib bokeh ipywidgets
```

---

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/ExoplanetWatchToolbox.git
    ```
   
2. Navigate to the directory:
    ```bash
    cd ExoplanetWatchToolbox
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Follow the instructions within the notebook to load FITS files, visualize data, and analyze star charts.

---

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, please feel free to open an issue or submit a pull request.

---

## License

This project is licensed under GPL-3

---

## Acknowledgments

Special thanks to the Exoplanet Watch program and the contributors of the EXOTIC tool for their valuable resources and support in advancing citizen science in astronomy.

---
