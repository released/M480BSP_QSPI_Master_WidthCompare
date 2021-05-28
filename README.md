# M480BSP_QSPI_Master_WidthCompare
 M480BSP_QSPI_Master_WidthCompare

update @ 2021/05/28

1. use QSPI0 , to comapre different data width

	PA0 : QSPI0_MOSI0 , PA1 : QSPI0_MISO0 , 
	
	PA2 : QSPI0_CLK , 
	
	PA3 : QSPI0_SS , 
	
	PA4 : QSPI0_MOSI1 , PA5 : QSPI0_MISO1 , 

2. when u32DataWidth set to 32 , in QSPI_Open

below is first data LA screen capture , 

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width32_num1.jpg)

below is second data LA screen capture , 

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width32_num2.jpg)

below is third data LA screen capture , 

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width32_num3.jpg)


3. when u32DataWidth set to 16 , in QSPI_Open

below is first data LA screen capture , 

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width16_num1.jpg)

below is second data LA screen capture , 

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width16_num2.jpg)

below is third data LA screen capture , so only the LSB data (16 bit) will be sent

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width16_num3.jpg)

4. when u32DataWidth set to 8 , in QSPI_Open

below is first data LA screen capture , so only the LSB data (8 bit) will be sent 

![image](https://github.com/released/M480BSP_QSPI_Master_WidthCompare/blob/main/LA_width8_num1_2_3.jpg)


