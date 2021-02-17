```python
import tensorrt as trt
import ctypes

pg = ctypes.CDLL(path_to_custom_plugin, mode=ctypes.RTLD_GLOBAL)
print('load customed plugin')
```