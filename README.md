# openvino_ai
Intel OpenVINO AI usage

## Environment
* OpenVINO R3 refer the [link](https://software.intel.com/en-us/openvino-toolkit)
* download [dll file](https://github.com/YaoxinShi/obs-binary/blob/master/obs_dist_2019R3.1_debug.7z)

## Run
* ocr usage
```
openvino_ai.exe -i 20180704_124659.png -m_td model/FP32/detection.xml -m_tr model/FP32/recognition.xml -dt image -l cpu_extension_avx2.dll
```











## comment
If you have any OpenVINO AI usage , please feel free to contribute this repo
