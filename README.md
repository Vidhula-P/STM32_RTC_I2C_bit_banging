# STM32_RTC_I2C_bit_banging
Code for DS32321 Real Time Clock (RTC) module with STM32 microcontroller connected using I2C protocol through bit banging

pin E12 acts as data line (SDA)
pin E11 acts as clock line (SCK) to DS3231 RTC module

STM32F107VCT6 has one pair of native port I2C peripherals at pins B6 and B7, but here pins E11 and E12 are configured as SCK and SDA respectively through software (bit banging).
This is useful when the native ports are connected to some other sensor.
