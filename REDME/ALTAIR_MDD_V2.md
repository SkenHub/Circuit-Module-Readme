# ALTAIR_MDD_V2
[ALTAIR_MDD_V2](https://github.com/Altairu/ALTAIR_MDD_V2)

![image](https://github.com/user-attachments/assets/8f2e0aaf-9ab4-401e-84b1-836afa1ff9af)


> encoder
 * A0 A1 TIMER5
 * B3 A5 TIMER2
 * B6 B7 TIMER4
 * C6 C7 TIMER3

> MD
 * B14(TIMER8  CH2)     B15(TIMER8  CH3)  もしくは B14(TIMER12 CH1) B15(TIMER12 CH2)
 * A8(TIMER1  CH1)     A11(TIMER1  CH4)
 * A6(TIMER13 CH1)     A7(TIMER14 CH1)
 * B8(TIMER10 CH1)     B9(TIMER11 CH1)

> Serial
* tx:C10  rx:C11  SERIAL3  baudrate 115200
* tx:A9  rx:A10  SERIAL1

## 回路図
![alt text](image/MDD1.png)

## PCB
![alt text](image/MDD2.png)
