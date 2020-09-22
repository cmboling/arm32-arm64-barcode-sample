# Dynamsoft Barcode Reader Samples for ARM32 and ARM64
The `C++` and `Python` sample code can work on **ARM32** or **ARM64** embedded computing boards like **Raspberry Pi** and **Nvidia Jetson Nano**.

## License Key
Apply for a trial license from [Dynamsoft customer portal](https://www.dynamsoft.com/customer/license/trialLicense).


## C++ Usage

Search for `reader.InitLicense` in the C++ code and set your license key:

```cpp
reader.InitLicense("LICENSE-KEY");
```

### ARM32
Build a project:

```
make -f Makefile32
```

Clean a project:

```
make -f Makefile32 clean
```

### ARM64
Build a project:

```
make -f Makefile64
```

Clean a project:

```
make -f Makefile64 clean
```

## Python Usage

Search for `license_key` in the Python code and set your license key:

```python
license_key = "Input your own license"
```

### Supported Python Version
3.6, 3.7 and 3.8

### Installation

```
pip install dbr
```



## License Agreement
https://www.dynamsoft.com/Products/barcode-reader-license-agreement.aspx

## Blog
[Dynamsoft Barcode Reader ARM64 for Nvidia Jetson Nano](https://www.dynamsoft.com/codepool/jetson-nano-arm64-barcode-sdk.html)
