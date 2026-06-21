# embedded-firmware

A structured embedded firmware journey built on the STM32 platform — 14 progressive projects from bare-metal GPIO to a full RTOS-based system.

> Build alongside learning. Learn alongside building.

---

## Platform

- **MCU:** STM32 (Cortex-M series)
- **IDE:** STM32CubeIDE / STM32CubeMX
- **HAL:** STM32 HAL / LL drivers
- **RTOS:** FreeRTOS (Level 11 onwards)
- **Language:** C

---

## Project Map

| Level | Folder | Project | Core Concepts |
|-------|--------|---------|---------------|
| 00 | `00-environment-setup` | Environment Setup | Toolchain, CubeMX, ST-Link |
| 01 | `01-gpio` | Traffic Light | GPIO, digital I/O, timing delays |
| 02 | `02-uart` | Mini Serial Console | USART, interrupts, printf |
| 03 | `03-timers` | Digital Stopwatch | TIM peripherals, input capture |
| 04 | `04-interrupts` | Reaction Timer Game | EXTI, NVIC, debounce |
| 05 | `05-adc` | Digital Voltmeter | ADC, voltage scaling, calibration |
| 06 | `06-pwm` | LED Brightness Controller | PWM, TIM compare, duty cycle |
| 07 | `07-spi` | Display Sensor Values | SPI, OLED/LCD drivers |
| 08 | `08-i2c` | Weather Station | I2C, BME280/SHT31, sensor fusion |
| 09 | `09-dma` | Fast Sensor Logger | DMA, circular buffer, UART TX DMA |
| 10 | `10-rtc` | Digital Clock | RTC, backup registers, low power |
| 11 | `11-freertos` | Multi-Sensor Logger | FreeRTOS tasks, queues, semaphores |
| 12 | `12-drivers` | Environment Monitoring Station | Custom drivers, abstraction layers |
| 13 | `13-pcb` | PCB — My STM32 Board | KiCad/Altium, schematic, layout, BOM |

---

## Author

Anishka J
