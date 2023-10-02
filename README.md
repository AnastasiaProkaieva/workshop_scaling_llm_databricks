# LLM Workshop on Databricks Lakehouse AI 

This repository was created as a supporting material around scaling your GenAI(LLM) workloads using Databricks Lakehouse AI Platform. 

## Structure 
The repository is divided into multiple folders:
- databricks_llm (utils and scripts used) 
- ds_configs (configuration files for Deep Speed (for distributed training))
- notebooks
  - data_prep 
  - composer_library 
  - optimized_inference
  - prompt_engineering
  - vectordb_rag
  - gpu_serving
  - mlflow_gateway
  - ds_fine_tuning
- old_notebooks

## Important Notes 
This code has been tested on the following cloud provider's instances: 
| Cloud Provider | Instance Type | GPU's RAM | Multi Node | Comments |
| --- | --- | --- | --- | --- |
| AWS | A10 | 24 Gb | - | - |
| AWS | A10(4GPU) | 4*24 Gb | - | - |
| AWS | A100(8GPU) | 320 Gb | - | - |
| Azure | A10(1 GPU) | 24 Gb | - | - |
| Azure | A10(2 GPU) | 48 Gb | - | - |
| Azure | A100(1 GPU) | 40 Gb | - | - |
| Azure | V100(1 GPU) | 16 Gb | - | Does not support low precision |


### Contributors: 
- Puneet Jain
- Michael Shtelma
- Anastasia Prokaieva

### Issues 
If you encounter any issues or have questions please raise an issue. 


