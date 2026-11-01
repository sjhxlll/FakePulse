# PPG 可视化模拟器 | PPG Visual Simulator

> 一个基于屏幕的假脉搏模拟器，可用于测试智能手环等可穿戴设备的光学心率传感器  
> A screen-based fake pulse generator for testing optical heart rate sensors in smart bands and wearables.
# [demo](https://fake-pulse.vercel.app)
---

## 📌 项目简介 | Overview

本项目通过模拟人类手腕的血液流动节律，在屏幕上以绿色光点的亮度变化来还原 PPG（光电容积脉搏波图）信号。将智能手环贴近屏幕，即可触发设备的心率检测功能。

This project simulates human blood flow rhythm visually using green brightness pulses on screen, mimicking PPG (photoplethysmography) signals. When a wearable device is placed against the screen, it can trigger heart rate detection.

---

## 🧠 原理说明 | How It Works

大多数智能手环使用绿色 LED 照射皮肤，并通过反射光强的周期变化计算心率。本项目通过屏幕模拟周期性绿光脉动，达到测试目的。

Most wrist-worn heart rate monitors use green LEDs and measure reflected light intensity to detect heartbeats. This tool emulates the periodic green light pulses using a screen display.

---

## 🎮 功能特点 | Features

- 💡 模拟近似真实 PPG 波动 | Simulates PPG-like signal (sine wave)
- 🎚 可调节心率频率（40～180 bpm）| Adjustable heart rate frequency (40–180 bpm)
- 🌑 黑底高对比，增强识别 | High contrast green-on-black for sensor clarity
- 📱 浏览器即可运行 | Runs directly in any modern browser

---

## 🖥 使用方法 | How to Use

1. 下载或克隆本项目 | Clone or download this repo
2. 使用浏览器打开 `ppg_simulator.html` | Open `ppg_simulator.html` in a browser
3. 将手环光电区域贴近绿色圆形区域 | Place the heart rate sensor of the device on the green circle
4. 调节滑块观察识别变化 | Adjust the slider to test different heart rate values

---

## 帮助 | help

- 1.心率检测和手环体质有关系。实测三个手环，其中有两个任何地方都可以检测到，但是另一个哪里都检测不到。
-2.亮度也有影响



---
