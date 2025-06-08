# README


### Overview

The dataset is derived from the open-source Bookinfo microservices system by stress testing, which primarily reflects the end-to-end response time of the Bookinfo system's three entry points (product page, reviews-v3, and ratings) under different resource interferences.
This dataset contains a total of 3,675 graphs.  These graphs are divided into three categories, representing microservice call chains with 7 microservices, 3 microservices, and 2 microservices, respectively.
Each node in the graph incorporates both the resource monitoring metrics of the microservice itself and the environmental metrics of the host where the microservice is deployed. 
  
### Dataset Link
[http://restic.gwusun.top/papers/2025rignn/ri-gnn-dataset.zip](http://restic.gwusun.top/papers/2025rignn/ri-gnn-dataset.zip)


### Directory Structrue

```
├── v1_bc_product_page_cpu_c1_10s_d1800s_cpu0_mem0
│   ├── benchmark_conf.json
│   ├── benchmark_res.json
│   ├── benchmark_res_human_readable.json
│   ├── logs
│   ├── meta
│   ├── metrics
│   └── traces
├── v1_bc_product_page_cpu_c1_10s_d1800s_cpu20_mem0
├── v1_bc_product_page_cpu_c1_10s_d1800s_cpu50_mem0
├── v1_bc_product_page_cpu_c1_10s_d1800s_cpu80_mem0
├── v1_bc_product_page_mem_c1_10s_d1800s_cpu0_mem20
├── v1_bc_product_page_mem_c1_10s_d1800s_cpu0_mem50
├── v1_bc_product_page_mem_c1_10s_d1800s_cpu0_mem80
├── v1_bc_rating_cpu_c1_10s_d1800s_cpu0_mem0
├── v1_bc_rating_cpu_c1_10s_d1800s_cpu20_mem0
├── v1_bc_rating_cpu_c1_10s_d1800s_cpu50_mem0
├── v1_bc_rating_cpu_c1_10s_d1800s_cpu80_mem0
├── v1_bc_rating_mem_c1_10s_d1800s_cpu0_mem20
├── v1_bc_rating_mem_c1_10s_d1800s_cpu0_mem50
├── v1_bc_rating_mem_c1_10s_d1800s_cpu0_mem80
├── v1_bc_reviews_cpu_c1_10s_d1800s_cpu0_mem0
├── v1_bc_reviews_cpu_c1_10s_d1800s_cpu20_mem0
├── v1_bc_reviews_cpu_c1_10s_d1800s_cpu50_mem0
├── v1_bc_reviews_cpu_c1_10s_d1800s_cpu80_mem0
├── v1_bc_reviews_mem_c1_10s_d1800s_cpu0_mem20
├── v1_bc_reviews_mem_c1_10s_d1800s_cpu0_mem50
├── v1_bc_reviews_mem_c1_10s_d1800s_cpu0_mem80
```

### Directory Descriptions

- `v1_bc_<entry-ms>_<component>_c1_10s_<duration>_<cpu_percent>_<mem_percent>: Data under different stress testing conditions. It provides three types of data for analysis: logs, metrics, and traces.
  




 
