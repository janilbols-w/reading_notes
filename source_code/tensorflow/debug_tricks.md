# tensorflow environment variables
- adding environment before running your tensorflow code (TF2.4)
  - search `getenv("TF_` to see more
 
| env_name | notes|
| -------- | ---- |
| TF_LOG_XLA_ACTIVITY | |
| TF_DUMP_GRAPH_PREFIX  | |
| TF_XRT_COMPILATION_CACHE_SIZE | |
| TF_XLA_DEBUG_OPTIONS_PASSTHROUGH | |
| TF_BFC_MEMORY_DUMP | |
| TF_DUMP_GRAPH_PREFIX | |
| TF_NUM_INTEROP_THREADS | |
| TF_FORCE_GPU_ALLOW_GROWTH | |
| TF_ENABLE_GPU_GARBAGE_COLLECTION | |
| TF_MIN_GPU_MULTIPROCESSOR_COUNT | |
| TF_GPU_ALLOCATOR | |
| TF_GPU_HOST_MEM_LIMIT_IN_MB | |


```

## CPP code Logging
add the following env to see more logs
```bash
TF_CPP_MIN_LOG_LEVEL=0
TF_CPP_MIN_VLOG_LEVEL=3 
```
