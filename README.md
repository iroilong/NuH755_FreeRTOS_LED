# 🧠 NuH755_FreeRTOS_LED

FreeRTOS demo project for the **STM32H755ZI-Q** dual-core MCU, created using **STM32CubeIDE**.  
This example demonstrates multitasking on the **NUCLEO-H755ZI-Q** board by blinking three on-board LEDs at different frequencies.

---

## 🌟 Features

- **RTOS:** FreeRTOS CMSIS_V2  
- **Board:** NUCLEO-H755ZI-Q  
- **IDE:** STM32CubeIDE  
- **MCU:** STM32H755ZI-Q (Cortex-M7 / Cortex-M4)  
- **Tasks:** Three independent LED blink threads  
  - 🟢 **LED1 (Green):** Fast blink  
  - 🟡 **LED2 (Yellow):** Medium blink  
  - 🔴 **LED3 (Red):** Slow blink  

---

## 🧩 Project Structure
```
NuH755_FreeRTOS_LED/
├── CM7/ # Cortex-M7 application (main FreeRTOS logic)
│ ├── Core/
│ ├── Drivers/
│ └── Middlewares/
├── CM4/ # Cortex-M4 core (optional secondary core)
├── Common/ # Shared dual-core utilities
├── LED_Demo.ioc # STM32CubeMX configuration file
├── .gitignore
└── README.md
```
