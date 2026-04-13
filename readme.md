### Base info

dataset:DeepDRiD
data_path: \\cabinet\derivatives\DeepDR\FVs_medsiglip
img_path: \\cabinet\data\Public_dataset\DeepDR

data_after_clean:./DR_dict_clean(56,77,164,167).pt
4 items has been removed cuz they had diffrent format


## data_structure

```text
data_dict
├── 1_l1
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 1_l2
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 1_r1
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 1_r2
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 2_l1
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 2_l2
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 2_r1
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── 2_r2
│   └── numpy.ndarray
│       ├── shape: (1152,)
│       └── dtype: float32
├── ...
└── 330_r2
    └── numpy.ndarray
        ├── shape: (1152,)
        └── dtype: float32

```

```
{ 
  "type": "dict",
  "num_keys": 1200,
  "keys": [
    "1_l1", 
    "1_l2", 
    "1_r1", 
    "1_r2", 
    "2_l1", 
    "2_l2", 
    "2_r1", 
    "2_r2", 
    ..., 
    "330_l1",
    "330_l2",
    "330_r1",
    "330_r2"
    ], 
  "items": { 
    "1_l1": { 
      "type": "numpy.ndarray", 
      "shape": [ 1152 ], 
      "dtype": "float32" 
    }, 
    "1_l2": { 
      "type": "numpy.ndarray", 
      "shape": [ 1152 ], 
      "dtype": "float32" 
    },
    "1_r1": {
      "type": "numpy.ndarray",
      "shape": [
        1152
      ],
      "dtype": "float32"
    },
    "1_r2": {
      "type": "numpy.ndarray",
      "shape": [
        1152
      ],
      "dtype": "float32"
    },
    ...,
    "330_l1": {
      "type": "numpy.ndarray",
      "shape": [
        1152
      ],
      "dtype": "float32"
    },
    "330_l2": {
      "type": "numpy.ndarray",
      "shape": [
        1152
      ],
      "dtype": "float32"
    },
    "330_r1": {
      "type": "numpy.ndarray",
      "shape": [
        1152
      ],
      "dtype": "float32"
    },
    "330_r2": {
      "type": "numpy.ndarray",
      "shape": [
        1152
      ],
      "dtype": "float32"
    }
  }
}

```
