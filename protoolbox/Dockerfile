FROM continuumio/miniconda3:latest

RUN conda config --add channels conda-forge && conda config --remove channels defaults
RUN conda install openmm==7.7.0 cudatoolkit=11.4
RUN conda install openmm-setup==1.3 openmmforcefields==0.10.0

RUN conda install numpy scipy matplotlib nglview
RUN conda install notebook jupyterhub jupyterlab && jupyter notebook --generate-config
RUN conda install prody==2.0.1 mdtraj==1.9.7 rdkit==2021.09.4 pymol-open-source==2.5.0 propka==3.4.0
RUN conda install -c salilab modeller==10.2

