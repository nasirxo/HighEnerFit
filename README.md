<p align="center">
  <img src="https://github.com/nasirxo/HighEnerFit/blob/main/HighEnerFit_Logo.png" alt="HighEnerFit Logo" width="200"/>
</p>

# HighEnerFit: A Tool for Particle Physics Data Analysis

HighEnerFit is a powerful graphical user interface (GUI) application designed to assist researchers in fitting particle physics data, with a particular focus on analyzing transverse momentum spectra. Whether you're studying particle production in high-energy collisions or exploring theoretical models, HighEnerFit offers an intuitive and feature-rich environment to load data, apply fitting models, tune parameters, visualize results, and manage your analysis—all through a user-friendly interface.

## What HighEnerFit Does

HighEnerFit simplifies the process of fitting experimental data to theoretical models commonly used in particle physics. Here's a breakdown of its core capabilities:

### Load and Analyze Data
- **Data Import**: Easily bring in your particle physics measurements from files like CSV or DAT formats. For example, you can load datasets containing transverse momentum (pT) values and yields, along with optional error measurements.
- **Flexible Formats**: Works with standard column-based data (e.g., pT, yield, statistical errors) and adapts to custom headers or metadata-rich files.

### Fit Data with Theoretical Models
HighEnerFit comes equipped with a variety of built-in fitting equations tailored for particle physics research, including:
- **Tsallis Equation**: Models transverse momentum spectra using parameters like normalization (N), non-extensivity (q), and temperature (T), with variants like N-q-T and N-q-T-Bt.
- **Hagedorn Equation**: Incorporates blast-wave terms (Bt) for particle production analysis, available in forms like N-n-T-Bt and A-n-Po.
- **Gaussian Fit**: A general-purpose option for fitting bell-shaped distributions.
- **Fokker-Planck**: A model with parameters (A, b, c, d, T) for specific physics scenarios.
- **Blast Wave Models**: Includes Tsallis Blast Wave (TBW) and Boltzmann Blast Wave (BGBW) for advanced spectral analysis.
- **Custom Fits**: Define your own equations to suit unique research needs.

### Interactive Parameter Tuning
- Adjust fit parameters in real-time using sliders or input fields. For instance, tweak the temperature (T) or normalization (N) and instantly see how it affects the fit.
- Set bounds or fix parameters like particle mass to refine your analysis.

### Visualize Results
- Generate high-quality plots showing your data and fitted curves.
- Customize plot styles with options like logarithmic scales, error bars, and color schemes to highlight key features of your analysis.

### Manage Multiple Fits
- Compare different fits and datasets side-by-side in a tabular view.
- Keep track of parameters, results, and visualizations for multiple runs within a single session.

### Save and Share Your Work
- Export fit results, parameter tables, and plots in formats like CSV or LaTeX, making it easy to integrate into reports or publications.

## How to Use HighEnerFit

Using HighEnerFit is straightforward with its clean GUI layout:
1. **Start the Application**: Launch the provided executable file to open the interface.
2. **Load Data**: Use the "Choose CSV File" or "Files Browse" option to import your dataset.
3. **Select a Model**: Pick a fitting equation (e.g., Tsallis or Hagedorn) from a dropdown menu.
4. **Set Parameters**: Choose a particle mass or adjust other settings like extrapolation ranges.
5. **Fit and Visualize**: Click "Fit" to process the data, then "Plot" to see the results.
6. **Save Output**: Export your plots and results with a single click.

The interface is split into:
- **Left Panel**: Tools for data loading, model selection, and parameter adjustments.
- **Right Panel**: Displays fit outcomes and detailed parameter info.
- **Header**: Shows version details and credits.

## Why Use HighEnerFit?

HighEnerFit is built for researchers who need a reliable, interactive tool to explore particle physics data without getting bogged down in technical setup. It’s ideal for:
- Analyzing transverse momentum spectra from high-energy experiments.
- Testing theoretical models against experimental data.
- Quickly iterating on fits with real-time feedback.
- Producing publication-ready visualizations and results.

Whether you're a physicist studying particle production or a student learning about data fitting, HighEnerFit provides the functionality you need in an accessible package. With its focus on usability and flexibility, it’s a valuable addition to any particle physics toolkit.
