# jointCallingMdifywdl
## modify broad jointgenotype wdl pipeline
## this project modify by warp jointGenotypeing v1.6.8 by gatk 4.3.0
## The purpose is to use the burden testing  case sample with control joint, because the quality control of VQSR is stricter than  Hard Filter, so the VQSR part is removed and only HF is used




## use:
```
cromwell run wdl json option zip 
```
