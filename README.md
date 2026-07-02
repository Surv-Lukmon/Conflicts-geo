# Title
Repository for the DSN Geospatial Community June Quarterly Session on 26 June 2026: "Mapping Armed Conflict Dynamics Using Geospatial Technologies"



![Graphical Abstract](Cover_Page_Readme.png "Geographic Pattern of Armed Clashes")


# How to Run
All dependencies and their versions are listed in `armed_geotech_env.yml` file.

## 1. Create the Conda environment

Open **Anaconda Prompt** and navigate to the folder containing `armed_geotech_env.yml`:

```bash
cd path\to\your\folder
```

Then create the environment (the name `armed-geotech26` is already defined inside the `.yml`):

```bash
 conda env create -f armed_geotech_env.yml
```

## 2. Activate the environment

Once installation completes successfully, activate it:

```bash
conda activate armed-geotech26
```

## 3. Activate the environment
It's recommended to have (login) credentials for **ACLED** and **Google Earth Engine (GEE)**.

Create a `.env` file in the project root folder (same location as the notebook) and add the following:

```
GEE_PROJECT_NAME="your-gee-project-name"
ACLED_EMAIL="your_acled_email@example.com"
ACLED_PASSWORD="your_acled_password"
```

- **GEE_PROJECT_NAME**: Your Google Earth Engine project name. Register at https://earthengine.google.com.
- **ACLED_EMAIL** and **ACLED_PASSWORD**: Register at https://acleddata.com.

Never share your `.env` file or commit it to version control. 


# Credits
This project includes code from:

-  Ujaval Ghandi: https://gee-community-catalog.org/tutorials/examples/glc_fcs30d_lulc/


# Copyright
&copy; 2026. All rights reserved.