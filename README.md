# CAN_STM32f429i_discovery
This project is about activating two CAN modules on the board in order to send a massage from one to another.  
First the project is configured by the CubeMx. 
In CubeMX the two module of can is configured with these configurations
  - Can1 as transmitter and Can2 as reciever
  - The clock for each can is 
  - For time quantum in Can.... 
Two models of coding is proposed here. One is with the help of HAL ( Hardware Abstraction Layer) and another code is without HAL. 
