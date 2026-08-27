THIS IS INAV 7.1 Firmware which supports Older hardware 
This firmware specially made for STM33F411 blackpill board 


*********** SUPPORTED MODULES ***********
GYROSCOPES & ACCELEROMETERS
- MPU6050
- MPU6500
- MPU9250
- ICM20602
- ICM20689
- ICM42688P
- BMI160
- BMI270
- LSM6DS33
- LSM6DSO

BAROMETERS
- BMP280 <-------- FIXED ERROR 
- BMP085
- BMP180
- MS5611
- DPS310
- SPL06
- LPS22HB
- LPS25H

MAGNETOMETERS
- HMC5883
- QMC5883
- QMC5883P <------ MAINLY ADDED 
- MAG3110
- LIS3MDL
- IST8310
- IST8308
- AK8975
- AK8963
- RM3100

  ******* PINOUT ********

  =================================================================================
                 STM32F411 BLACK PILL PIN ASSIGNMENTS (CLEANFLIGHT/INAV)
=================================================================================

// Power, Status & Diagnostics
LED0                   : PC13  // Onboard Status LED
BEEPER                 : PB1   // Active 5V Beeper (Inverted)
VBAT_ADC               : PB0   // Battery Voltage Sense (ADC1)

// Hardware UARTs & SoftSerial
UART1_TX               : PA15
UART1_RX               : PB3

UART2_TX               : PA2
UART2_RX               : PA3

SOFTSERIAL1_TX         : PA9
SOFTSERIAL1_RX         : PA10

// I2C Bus 1 (Shared Sensors: MPU6050, BMP280, HMC5883, VL53L1X)
I2C1_SCL               : PB8
I2C1_SDA               : PB9

// SPI Bus 1 (Shared: MicroSD Card & ADNS3080 Optical Flow)
SPI1_SCK               : PA5
SPI1_MISO              : PA6
SPI1_MOSI              : PA7

SDCARD_CS              : PA4   // MicroSD Blackbox Chip Select
OPFLOW_CS              : PB10  // ADNS3080 Chip Select
OPFLOW_RST             : PB2   // ADNS3080 Reset Pin

// Peripherals
WS2811_LED             : PA8   // WS2812B RGB LED Strip Data
=================================================================================

  

