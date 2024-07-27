conda create -p env python=3.10
conda activate F:\AI\yolov8-cam\env
conda install -c conda-forge jupyterlab
conda install ipykernel
python -m ipykernel install --user --name=env --display-name "yolov8-cam"
