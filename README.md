# A demo for Sharp Memory LCD 夏普memoryLCD的测试程序 #
A demonstration to display something in Sharp Memory LCD 
fit to : models :LS027B7DH01<br/>
输出图片到夏普memory LCD的程序，支持型号：LS027B7DH01

# External Circuit Connect LCD周边连线 #
according to the official document, we need two 0.1uf ceramic capacitor, one 1uf ceramic capacitor.<br/>
按照官方文档，需要两个0.1uf电容，一个1uf电容<br/>
schematic:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/external_circuit_schematic.jpg)<br/>
connect1:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/external_circuit_1.JPG)<br/>
connect2:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/external_circuit_2.JPG)<br/>

# stm 32 pin connect stm32的pin连线 #
Schematic:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/Schematic_stm32.png)<br/>
connect:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/stm32_connect.JPG)<br/>


# stm 32 cube MX config #
## GPIO config ##
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/CubeMX_GPIO.jpg)
## TIM config ##
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/CubeMX_TIM.jpg)
## SPI2 config ##
although the official document say the data SCLK should not over 2M hz,
i found it could handle 10M hz<br/>
尽管官方文档说时钟频率不应该超过2M hz，但我测试发现10M hz也是能轻松处理<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/CubeMX_SPI2.jpg)

# arduino pin connect arduino的pin连线#
schematic:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/Schematic_arduino.png)<br/>
connect:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/arduino_connect.JPG)<br/>

# result结果展示 #
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/result.JPG)<br/>
stm 32 result<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/stm32_result.jpg)<br/>
arduino result<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/arduino_result.JPG)<br/>

# picture source #
## link ##
[長門](https://www.pixiv.net/artworks/81387746)<br/>
## origin ##
source: <br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/demo_source.png)<br/>
## black and white ##
black and white:<br/>
![](https://github.com/DeathSea/Sharp_Memory_Disp_Demo/raw/master/picture/demo_black_and_white.jpg)<br/>
