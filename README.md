# Embedded-Systems-Project

This repository contains an embedded C program for the LPC1768 microcontroller, which demonstrates Nokia keypad-style text input using a 4x4 matrix keypad and displays the decoded text on an LCD screen. The code is designed to scan the keypad for input, store the pressed keys in a queue, and then convert the multi-press Nokia-style input into readable text, which is then displayed on the LCD.

# Features

4x4 matrix keypad input
Nokia-style multi-press text input decoding
Queue implementation for storing pressed keys
LCD screen integration for displaying the decoded text
GPIO pin configuration for keypad input and LCD output

# Prerequisites

LPC1768 microcontroller
4x4 matrix keypad
LCD screen (compatible with the provided code)
Keil uVision IDE (or any other suitable ARM Cortex-M3 compatible IDE)
