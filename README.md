# SMART BUILDINGS, NEIGHBORHOODS, AND CITIES

## Milan: A Sensor-Based Study - Analyzing the Air Temperature Variation in Giardini Indro Montanelli and Surroundings

This project focuses on the analysis of various datasets related to smart cities. The goal is to utilize data analytics to derive insights and contribute towards the development of smarter urban areas.

This project was developed for the course *Smart Buildings, Neighborhoods and Cities – 057689* from Politecnico di Milano as part of the Academic Year of 2023/24. The group is composed by the students:

- Bagni, Felipe (MSc. in Computer Engineering) 
- Hüntemann, Lisa Marie (MSc. In Building Architecture) 
- F. Petrucci, Marcos V. (MSc. in Computer Engineering)

And the course is ministrated by Prof. Andrea Antonio Caragliu, Prof. Luca Mottola.

## Project Structure

The project is organized into several directories and Jupyter notebooks, each serving a specific purpose in the data analysis process.

### Directories

- **[raw](./raw/)**: Contains raw datasets used for analysis.
- **[filtered](./filtered/)**: Support directory which contains the filtered datasets.
- **[support-ipynbs](./support-ipynbs/)**: Includes supporting Jupyter notebooks for the analysis.
- **[maps](maps)**: Contains visualizations related to the points of data collection.
- **[temperature-maps](temperature-maps)**: Includes visualizations related to temperature data.
- **[path-maps](path-maps)**: Contains visualizations related to path taken during the data collection process.
- **[docs](docs)**: Report and supporting slides for class presentation.

### Jupyter Notebooks

- **[data_analysis.ipynb](data_analysis.ipynb)**: Main notebook for overall data analysis and insights.
- **[support-ipynbs/db1-analysis.ipynb](support-ipynbs/db1-analysis.ipynb)**: Support data analysis and insights from Database 1.
- **[support-ipynbs/db2-analysis.ipynb](support-ipynbs/db2-analysis.ipynb)**: Support data  analysis and insights from Database 2.
- **[support-ipynbs/db3-analysis.ipynb](support-ipynbs/db3-analysis.ipynb)**: Support data  analysis and insights from Database 3.
- **[support-ipynbs/db4-analysis.ipynb](support-ipynbs/db4-analysis.ipynb)**: Support data  analysis and insights from Database 4.

### Node-RED Flow

The Node-RED flow for this project is provided in the [`node_red_flow.json`](node_red_flow.json) file. This flow includes configurations for collecting and processing data from different sensors used in the project.

Additional palettes used in the flow:
- `node-red-contrib-grove-air-quality-sensor`
- `node-red-contrib-grove-base-hat`
- `node-red-node-serialport`

### Project Report

The [project report](./docs/Bagni_Huentemann_Petrucci.pdf) provides an in-depth analysis of the study, highlighting key findings and trends. The report also features the context of the project, explanations of the work developed, visualizations, insights and explanations. With this, it offers a comprehensive view of the factors influencing temperature in the park.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additional analyses.

## License

This project is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for details.
