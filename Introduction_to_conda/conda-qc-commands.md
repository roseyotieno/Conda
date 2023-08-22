commands for installing packages fastqc and multiqc
---

(base) roselyne@rosey:~$ conda create -n qc

(base) roselyne@rosey:~$ conda activate qc

(qc) roselyne@rosey:~$ conda search fastqc

(qc) roselyne@rosey:~$ conda install fastqc

(qc) roselyne@rosey:~$ fastqc -v

FastQC v0.12.1

(qc) roselyne@rosey:~$ conda search multiqc

(qc) roselyne@rosey:~$ conda install multiqc

(qc) roselyne@rosey:~$ multiqc -v

This is MultiQC v1.15
