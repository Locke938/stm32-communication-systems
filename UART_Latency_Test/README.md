# UART Latency Test using STM32

## Overview

This project measures the communication latency between a Windows PC and an STM32F103C8T6 microcontroller using UART communication.

The objective is to evaluate the response time of serial communication under continuous data transmission.

---

## Hardware

- STM32F103C8T6 Blue Pill
- USB-UART Converter
- PC

---

## Software

- STM32CubeIDE
- STM32 HAL Driver
- Visual Studio
- UART Communication

---

## Test Procedure

1. PC sends a data packet through UART.
2. STM32 receives the packet.
3. STM32 sends a response packet.
4. PC records the transmission time.
5. Latency is calculated and stored.

---

## Metrics

The following metrics were collected:

- Minimum Latency
- Maximum Latency
- Average Latency
- Number of Errors

---

## Test Results

Example:

- Total Packets: 112,000
- Average Latency: 3.63 ms
- Maximum Latency: 207 ms
- Accuracy: 99.96%

---

## Conclusion

The UART communication system maintained high reliability during long-term operation with very low error rates.
