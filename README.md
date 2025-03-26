# RC_Car

## tutorial on setting up canbus: 
https://steinslab.io/archives/1712#1_%E5%90%AF%E7%94%A8CAN%E6%8E%A7%E5%88%B6%E5%99%A8

## cansend package (always send through can0)
https://github.com/JiaheXu/cansend/blob/main/src/cansend.cpp#L100
https://github.com/JiaheXu/cansend

## driver
https://github.com/JiaheXu/drivers

## custom motor driver (changed for canbus cmds) flashed the vesc if you start from scratch
https://github.com/JiaheXu/bldc

Data flow: joystick driver (joy_cmd) -> driver(mmpug_vesc_interface) send canbus cmd through 'cansend' -> motor

