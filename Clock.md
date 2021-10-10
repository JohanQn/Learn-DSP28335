### 时钟
```c
InitSysCtrl();
  InitPLL(DSP28_PLLCR,DSP28_DIVSEL);    //PLLCR 10 倍频 300MHz; DIVSEL 2 分频 150MHz
```
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/OSC%20and%20PLL%20Block.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/SysCtrlRegs.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/PCLKCR0.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/PCLKCR1.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/PCLKCR3.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/HSPCLK.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/watchdog1.png"/>
<img src="https://github.com/JohanQn/Learn-DSP28335/blob/imags/imags/Clock/watchdog2.png"/>
