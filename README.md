## Welcome to My GitHub Pages

This is my page for taking notes about my course-works during free time and study.


### The Newest Update

2017-01-09 Taking notes for all projects I'v finished before

***

### Projects

#### 1.FPV

This is the project for my graduation from my college. An equipment for dirve air-grone with VR-headset.

**Device Included**: 2 wifi dongles, a single-board like raspberry pi, air-drone, VR headset, PC

**Method**: Capture Video -> Send Stream through wifi dongles -> Show Video on PC

**Link**: [VR-DRONE](https://github.com/milkrong/VR-DRONE)


#### 2.Public Umbrella Rental Sys

The project considering the problem that student may meet *sudden rain* after class on campus.

**Device Included**: Arm board with core STM32, Card Reader, Umbrellas with eletronic lock

**Method**:

- Process the information and control the lock with Arm board(control software built by **C**)
- Information I/O conducted by NFC (io port spi)
- Human Interface with a touch screen (**The emOS based on QT**)
- Transfer the information through the Internet and build a sql on the service with *MySQL*

#### 3. FPGA-Snake-Game

This is snake running on a FPGA board with VerilogHDL

**Deivce Included**: FPGA, PS2 keyboard, VGA screen

**Method** :
- All pixel movement is controlled by the **status machine**
- Keyboard send serial signal to control the movement of snake
- The movement of  snake is judgemented by the cuurent position and commands from the keyboard.
- The position of snake's food is deployed by a random function.
-  The RGB signal is output through the VGA port finally.

**Link**: [snake-game](https://github.com/milkrong/FPGA-Snake-Game)          

***

### Jekyll Themes

This Page use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/milkrong/milkrong.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
