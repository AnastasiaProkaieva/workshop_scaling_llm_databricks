# LLM Workshop on Databricks Lakehouse AI 

This repository was created as a supporting material around scaling your GenAI(LLM) workloads using Databricks Lakehouse AI Platform. 

## Structure 
The repository is divided into multiple folders:
- databricks_llm
> 
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
| AWS | A10 | - | - | - |
| AWS | 4*A10 | - | - | - |
| AWS | A100 | - | - | - |
| Azure | 4*A10 | - | - | - |
| Azure | A100 | - | - | - |
| Azure | V100 | - | - | Does not support low precision |


### Contributors: 
- Puneet Jain
- Michael Shtelma
- Anastasia Prokaieva

### Issues 
If you encounter any issues or have questions please raise an issue. 


