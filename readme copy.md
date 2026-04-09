data_path: \\cabinet\derivatives\cheXpert\FVs_medsiglip
img_path: \\cabinet\data\Public_dataset\cheXpert\CXR8\images

dataset:CXR14

## data_structure of FVs_medsiglip(Chest X-ray)

```
data_dict
├── train_val
│   ├── feature_vectors   # 特征向量
│   ├── path_list         # 图像路径/文件名
│   └── remarks           # 备注信息
└── test
    ├── feature_vectors   # 特征向量
    ├── path_list         # 图像路径/文件名
    └── remarks           # 备注信息
```



```
{
  "type": "dict",
  "num_keys": 2,
  "keys": [
    "train_val",
    "test"
  ],
  "items": {
    "train_val": {
      "type": "dict",
      "num_keys": 3,
      "keys": [
        "feature_vectors",
        "path_list",
        "remarks"
      ],
      "items": {
        "feature_vectors": {
          "type": "numpy.ndarray",
          "shape": [
            86524,
            1152
          ],
          "dtype": "float32"
        },
        "path_list": {
          "type": "numpy.ndarray",
          "shape": [
            86524
          ],
          "dtype": "<U16"
        },
        "remarks": {
          "type": "dict",
          "num_keys": 4,
          "keys": [
            "findings",
            "follow_ups",
            "genders",
            "ages"
          ],
          "items": {
            "findings": {
              "type": "numpy.ndarray",
              "shape": [
                86524
              ],
              "dtype": "<U100"
            },
            "follow_ups": {
              "type": "numpy.ndarray",
              "shape": [
                86524
              ],
              "dtype": "int64"
            },
            "genders": {
              "type": "numpy.ndarray",
              "shape": [
                86524
              ],
              "dtype": "<U1"
            },
            "ages": {
              "type": "numpy.ndarray",
              "shape": [
                86524
              ],
              "dtype": "int64"
            }
          }
        }
      }
    },
    "test": {
      "type": "dict",
      "num_keys": 3,
      "keys": [
        "feature_vectors",
        "path_list",
        "remarks"
      ],
      "items": {
        "feature_vectors": {
          "type": "numpy.ndarray",
          "shape": [
            25596,
            1152
          ],
          "dtype": "float32"
        },
        "path_list": {
          "type": "numpy.ndarray",
          "shape": [
            25596
          ],
          "dtype": "<U16"
        },
        "remarks": {
          "type": "dict",
          "num_keys": 4,
          "keys": [
            "findings",
            "follow_ups",
            "genders",
            "ages"
          ],
          "items": {
            "findings": {
              "type": "numpy.ndarray",
              "shape": [
                25596
              ],
              "dtype": "<U86"
            },
            "follow_ups": {
              "type": "numpy.ndarray",
              "shape": [
                25596
              ],
              "dtype": "int64"
            },
            "genders": {
              "type": "numpy.ndarray",
              "shape": [
                25596
              ],
              "dtype": "<U1"
            },
            "ages": {
              "type": "numpy.ndarray",
              "shape": [
                25596
              ],
              "dtype": "int64"
            }
          }
        }
      }
    }
  }
}

```
