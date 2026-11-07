# Haolan Wang

I study Electronic Information Engineering. My research uses electrical measurements to answer three different questions. Where is a fault on a power line? How does skin admittance change after exercise? How can a fabric turn pressure into a visible response?

我是一名电子信息工程本科生。我的三段研究都从电信号测量出发，分别用电压差估计电网故障位置，用皮肤导纳观察运动前后的变化，以及用织物电阻的变化控制灯光。

### Power system fault location · 电力系统故障定位

I reproduced a fault-location method based on the numerical Laplace transform, then explored estimating the fault position from the minimum voltage difference. My analysis so far addresses feasibility. How much spectral leakage and transform errors affect the estimate remains an open question.

我复现了基于数值拉普拉斯变换的故障定位方法，并初步分析了以最小电压差估计故障位置的可行性。目前仍需研究频谱泄漏和变换误差对定位精度的影响。

### Skin admittance during exercise studies · 运动前后的皮肤导纳测量

I measured skin admittance before and after cycling and compared features extracted from the data with earlier findings. I also explored how the choice of electrode affects the measurements and whether AC could replace DC in the measurement setup.

我采集了骑行前后的皮肤导纳数据，提取特征并与已有研究结果对照。我还考察了不同电极对测量结果的影响，并探索了用交流测量替代直流测量的可行性。

### Pressure-sensitive textiles · 压敏织物的灯光反馈

I designed a voltage-divider circuit to read a fabric's changing resistance and mapped the readings to LED states. After circuit simulation and PCB layout, I used measured data to calibrate the switching thresholds for ADC quantization and variation in trigger pressure.

我设计了分压采集电路，把织物受压时的电阻变化映射为不同的 LED 状态。我完成了电路仿真和 PCB 布局，并用实测数据校准切换阈值，以应对模数转换的量化误差和实际触发压力的偏差。

**Programming · 编程**　C · C++ · Python · MATLAB
