# 滑面识别\Sliding-surface-identification

> 滑面识别程序
> 
> Sliding surface identification program

该程序是用 python 及其 OpenCV、Alpha shapes 库编写的，能够基于总位移云图识别滑动面。

The program is written by python and its OpenCV,alpha shape library, which can identify the sliding surface recognition based on the total displacement contour map.

下载此项目后，在根据需要配置python环境后，可直接运行 *Sliding_IDENTIFICATION_Program.ipynb* 文件。

After downloading this project, you can directly run *Sliding_identification_program.ipynb* file after configuring the python environment as required.

所需要的文件在 *example_TDCM* 中，其中：

The required files are in *example_TDCM*, where:

- maximum_shear_strain.jpg
- total_displacement.jpg
- total_displacement_.jpg

是从 *Phase2* 软件导出的，剩余的文件则是在软件运行过程中生成的。

It is exported from the *Phase2* software, and the remaining files are generated during the operation of the software.

**运行代码的要求如下：**
**The requirements for running the code are as follows:**

| Package               | Version  |
| --------------------- | -------- |
| alphashape            | 1.3.1    |
| colorama              | 0.4.6    |
| contourpy             | 1.0.7    |
| Cython                | 0.29.34  |
| ipykernel             | 6.22.0   |
| matplotlib            | 3.7.1    |
| matplotlib-inline     | 0.1.6    |
| mdit-py-plugins       | 0.3.3    |
| mdurl                 | 0.1.2    |
| numpy                 | 1.24.3   |
| opencv-contrib-python | 4.6.0.66 |
| opencv-python         | 4.1.2.30 |
| openpyxl              | 3.1.2    |
| paddleocr             | 2.6.1.3  |
| paddlepaddle          | 2.4.2    |
| pandas                | 2.0.0    |
| pykeyboard            | 0.1.5    |
| PyMouse               | 1.0      |
| pypiwin32             | 223      |
| PyUserInput           | 0.1.10   |
| scikit-image          | 0.17.2   |
| scikit-learn          | 1.2.2    |
| scipy                 | 1.10.1   |
