# API Description of OSAL-Like

## Introduction
**OSAL-Like** is a rebuild scheduler from OSAL of z-stack(TI ZigBee stack). Following features are realised:
- Basic scheduler;
- Multi-task with priority;
- Event driven.
- Software Timer.
- Messages.
- Queue operation for general use.
- And so on....   

This document contains all description of OSAL-Like API, and help user for task coding.

## Description
To be done...
### OSAL Basic
To be done...
#### void Osal_Init()
To be done...
#### void Osal_Reg_Tasks(PF_TASK_PROCESS pfTaskFn)
To be done...
#### voidOsal_Run_System()
To be done...
#### uint8 Osal_Event_Set(uint8 u8TaskID, uint16 u16Evt)
To be done...
#### uint8Osal_Event_Clr(uint8 u8TaskID, uint16 u16Evt)
To be done...
#### uint8Osal_Memset(uint8* pDes, uint8 u8Val, uint8 u8Len)
To be done...
#### uint8 Osal_Get_Acktive_Task()
To be done...
#### void Osal_Reg_Malloc_Free()
To be done...
#### void* Osal_Malloc(uint32 u32Size)
To be done...
#### void Osal_Free(void *p)
To be done...   

------------   

### OSAL Timer
To be done...   

------------   

### OSAL Message
To be done...   

------------   

### OSAL Queue
To be done...   

-------------   

### OSAL Link List
To be done...