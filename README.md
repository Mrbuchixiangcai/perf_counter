# perf_counter
A dedicated performance counter for Cortex-M systick. It shares the SysTick with users' original SysTick function without interfere it. This library will bring new functionalities, such as performance counter, delay_us and clock() service defined in time.h

perf_counter库使用方式
https://mp.weixin.qq.com/s/vOmJO9Wd8p1ctVUK-QPwdw
裸机思维大佬的代码：
SysTick第一吃：微秒级精确延时
SysTick第二吃：精确测量代码的时钟周期
SysTick第三吃：系统时间戳

