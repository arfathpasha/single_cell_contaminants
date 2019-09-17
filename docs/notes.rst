Ticket: https://shahcompbio.atlassian.net/browse/SCDNA-239

Data: /juno/work/shah/data/dlp_contamination_dataset

stats:

  | paired end 
  | 1 pair per cell
  | A95623A: 3795 files, 68G
  | A95623B: 2727 files, 70G
  | A97318A: 3109 files, 49G


docker containers:
https://hub.docker.com/u/singlecellpipeline

docker files:
https://github.com/shahcompbio/docker_containers/tree/master/singlecellpipeline/fastq_screen

code to run fastq screen at:
https://github.com/shahcompbio/single_cell_pipeline/blob/master/single_cell/workflows/align/fastqscreen.py

code to run biobloom:
biobloom:
https://github.com/shahcompbio/single_cell_pipeline/blob/master/single_cell/utils/bamutils.py#L156

To run with singularity:

.. code-block:: console
  
  export SINGULARITY_CACHEDIR=/juno/work/shah/dgrewal/work/singularity/cache
  singularity run --bind /juno/work  docker://docker.io/singlecellpipeline/single_cell_pipeline:v0.4.0 <command>


TODOs:
======
- read fastqscreen and biobloom documentation
- get fastqscreen and biobloom working locally
