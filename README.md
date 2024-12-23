# 全模拟电路实现的电子秤设计电路图（包含AD完整工程）

## 项目简介

本资源文件提供了一个全模拟电路实现的电子秤设计电路图，包含完整的AD工程文件。该项目是基于传感器设计制作的一款高精度电子秤，要求传感器具有大小两个量程，量程之间可自动或手动切换。小量程的量程为0-200g，误差范围控制在1%以内；大量程的量程为0-2000g，误差范围同样控制在1%以内。整个系统的设计完全采用模拟电路实现，不使用单片机等控制芯片。

## 设计原理

本系统主要电路部分均采用模拟电路完成，前端信号采集采用悬臂梁式电阻应变片式压力传感器完成。传感器采集的信号送入信号放大电路，信号放大电路采用仪用放大器 INA128 芯片完成。由于 INA128 需要精准的零电压作为参考电压，因此采用 OP07 芯片输出零值电压给 INA128 作为精准的参考电压。

传感器采集的信号经 INA128 放大后，送入信号处理电路完成信号的模数转换及数码管信号译码。本部分采用 ICL7107 芯片完成。ICL7107 芯片完成信号的模数转换后，将译出的数据送入显示电路完成用户终端的显示，本部分采用三位半数码管完成。

## 资源内容

- **电路图文件**：包含完整的电路设计图，详细展示了各个模块的连接方式和元器件参数。
- **AD工程文件**：包含完整的Altium Designer工程文件，方便用户进行电路的仿真和调试。
- **元器件清单**：列出了设计中使用的所有元器件及其规格参数，方便用户进行采购和制作。

## 使用说明

1. **下载资源**：下载本资源文件，解压后可获得电路图文件和AD工程文件。
2. **查看电路图**：使用电路图查看软件（如Altium Designer、Eagle等）打开电路图文件，查看电路设计细节。
3. **仿真与调试**：使用Altium Designer打开工程文件，进行电路的仿真和调试，确保电路设计的正确性。
4. **制作与测试**：根据电路图和元器件清单，采购所需元器件并进行电路的制作。完成制作后，进行实际测试，验证电子秤的性能。

## 注意事项

- 本设计采用全模拟电路实现，不涉及单片机等数字电路部分，适合对模拟电路设计感兴趣的用户。
- 在进行电路制作时，请确保元器件的参数符合设计要求，避免因元器件误差导致系统性能下降。
- 在测试过程中，请注意传感器的安装和校准，确保测量结果的准确性。

## 联系我们

如有任何问题或建议，欢迎通过电子邮件与我们联系。我们将尽快回复您的咨询。

## 下载链接

[全模拟电路实现的电子秤设计电路图包含AD完整工程](https://pan.quark.cn/s/42a5658b9146)