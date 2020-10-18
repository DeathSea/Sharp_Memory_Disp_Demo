# A demo for Sharp Memory LCD 夏普memoryLCD的测试程序 #
A demonstration to display something in Sharp Memory LCD 
fit to : models :LS027B7DH01
输出图片到夏普memory LCD的程序，支持型号：LS027B7DH01

# External Circuit Connect LCD周边连线 #
according to the official document, we need two 0.1uf ceramic capacitor, one 1uf ceramic capacitor.
按照官方文档，需要两个0.1uf电容，一个1uf电容
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/external_circuit_schematic.jpg)<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/external_circuit_1.jpg)<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/external_circuit_2.jpg)<br/>

# stm 32 pin connect stm32的pin连线 #
Schematic:
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/Schematic_stm32.png)<br/>
connect:
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/stm32_connect.JPG)<br/>


# stm 32 cube MX config #
## GPIO config ##
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/CubeMX_GPIO.jpg)
## TIM config ##
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/CubeMX_TIM.jpg)
## SPI2 config ##
although the official document say the data SCLK should not over 2M hz,
i found it could handle 10M hz
尽管官方文档说时钟频率不应该超过2M hz，但我测试发现10M hz也是能轻松处理
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/CubeMX_SPI2.jpg)

# arduino pin connect arduino的pin连线#
schematic:

connect:
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/arduino_connect.JPG)<br/>

# result结果展示 #
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/result.JPG)
stm 32 result
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/stm32_result.JPG)
arduino result
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/arduino_result.JPG)

# picture source #
[長門](https://www.pixiv.net/artworks/81387746)
source: 
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/demo_source.png)
black and white:
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/demo_black_and_white.wbm)
