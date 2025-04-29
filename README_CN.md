# DC Power Efficiency Measurement Software
直流功率效率测量软件

 A fully automated software that measures power efficiency among other things for various input voltages and output load currents for your circuit using a programmable power supply and a dc electronic load. This software supports Window 10, 8, 8.1, and 7.
#### [Download](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/releases)
**Features:**

- Fully automated, the user only need to set the input parameters and click start, the software will do the rest.
- 全自动化，用户只需要设置输入参数并点击开始，软件就会完成剩下的工作。
- Automatically save all the measured and calculated data to text files.
- 自动将所有测量的和计算的数据保存到文本文件中。
- Graphs and the measurement table are automatically updated as the software finishes each test.
- 测量表和图表在软件完成每个测试时都会自动更新。
- Graphs are highly interactive and customizable. Add vertical and or horizontal markers as well as set color themes. Use mouse tracker to easily see x and y values on the graph.
- 交互性和可定制。可以添加垂直或水平标记，并设置颜色主题。使用鼠标跟踪器可以轻松查看图表上的x和y值。
- Users may open up to 9 live updating graphs to display their data on.
- 9个实时更新图表可以显示数据。
- Save graph as an image, and save table's content manually as .CSV or text file. You may also edit the table's content or delete them.
- 保存图表为图像，手动保存表格的内容为.CSV或文本文件。您还可以编辑表格的内容或删除它们。
- Supports most HP/Agilent/Keysight power supplies that have a serial port.
- 支持大多数具有串行端口的HP/Agilent/Keysight电源。
- Supports SCPI commands by default for controlling power supplies.
- 支持默认情况下通过SCPI命令控制电源。
- Software has safety checks preventing users from setting invalid parameters that may result in instruments showing errors.
- 软件具有防止用户设置无效参数（可能导致仪器显示错误）的安全检查。
- Every test is saved in its own custom folder with date time stamp.
- 测试保存在其自己的自定义文件夹中，带有日期和时间戳。

**Supported Power Supplies**: Any programmable power supply with a serial interface that allows you to set voltage, set current, measure voltage, and     measure current should work with this software. Output on and output off commands are optional. Your power supply must operate in constant voltage mode (CV) while performing tests.
支持串口电源，具有串口接口的编程式电源。测试必须在常量电压模式（CV）下运行。

###### Currently tested power supplies: HP/Agilent/Keysight 66312A, 66332A, 6631B, 6632B, 6633B, 6634B, 6611C, 6612C, 6613C, and 6614C
已测试的电源：HP/Agilent/Keysight 66312A, 66332A, 6631B, 6632B, 6633B, 6634B, 6611C, 6612C, 6613C, and 6614C

**Supported DC Electronic Loads**: Any programmable dc electronic load or 2/4 quadrant power supply (must have programmable sink capability) with a serial interface that allows you to set the sink current value, measure voltage, and measure current should work with this software. Output on, output off, set voltage commands are optional. Your dc electronic load must operate in constant current sink mode (CC) while performing tests.
已测试的dc电子负载或2/4象限电源：HP/Agilent/Keysight 6631B, 6632B, 6633B, 6634B，<br>直流负载必须在常量电流模式（CC）下运行。</br>
###### Currently tested dc electronic loads or 2/4 quadrant power supplies: HP/Agilent/Keysight 6631B, 6632B, 6633B, 6634B
已测试的dc电子负载或2/4象限电源：HP/Agilent/Keysight 6631B, 6632B, 6633B, 6634B

![Test Fixture](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Test_Fixture.PNG)

The basic concept is that you connect your power supply to the input terminals of your device that you want to test. And connect your dc electronic load to the output terminals of your device. The power supply will provide power to your device and the dc electronic load will consume power from your device. The power supply will measure voltage and current on the input side of your device while the dc electronic load will measure voltage and current on the output side. **Please refer to the user manual for more info: 
[User manual](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/User%20Manual.pdf)**
将电源连接到您的设备的输入端，并将dc电子负载连接到您的设备的输出端。电源将为您的设备提供电源，dc电子负载将消耗设备的电力。电源将在您的设备的输入侧测量电压和电流，而dc电子负载将在您的设备的输出侧测量电压和电流。**请参考用户手册以获取更多信息：[用户手册](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/User%20Manual.pdf)**

![Main Window](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_1.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_3.PNG)

![Table](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_2.PNG)

![COM select window](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/COM%20Port%20Window.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_4.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_5.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_6.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_7.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_8.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_9.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_10.PNG)

![Graph](https://github.com/Niravk1997/DC-Power-Efficiency-Measurement-Software/blob/main/Pictures/Picture_11.PNG)

