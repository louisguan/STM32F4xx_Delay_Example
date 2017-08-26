# STM32F4xx_Delay_Example

使用STM32F4的内核定时器SysTick，来实现精确延时函数Delay。

## 开发环境

* 适用芯片：STM32F4全部芯片
* 固件库：STM32F4xx_DSP_StdPeriph_Lib_V1.8.0
* IDE：MDK517

## API

* void Delay_us(uint64_t nus)
* void Delay_ms(uint64_t nms)
* void Delay_s(uint64_t ns)

## 注意

为了保证程序的正常运行，HCLK时钟必须在1~250MHz之内。
