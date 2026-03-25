### *Prerequisites*

* Install ArcGIS Pro Desktop in the local disk.<br/>

    - After installing ArcGIS Pro, check "arcgispro-py3" in the Path.<br/>
        ```Path: C:\Program Files\ArcGIS\Pro\bin\Python\envs\arcgispro-py3.```<br/>

* Create new virtual environment in Anaconda with Arcpy package.<br/>

    - Create an environment with Arcpy package first, do not create environment with python==version<br/>
    - You need to know the path of "arcgispro-py3" in your local disk, mostly you can find it here C:\Program Files\ArcGIS\Pro\bin\Python\envs\arcgispro-py3<br/>
    - Example<br/>
        `conda create --clone "C:\Program Files\ArcGIS\Pro\bin\Python\envs\arcgispro-py3" -n GIS`<br/>
        `conda activate GIS`<br/>
        `conda install -c esri arcpy`<br/>

    - Checking ArcPy installation<br/>
    `Run Python`<br/>
    `Type import arcpy`<br/>
    `If no error message appears, Arcpy is working correctly`<br/>
