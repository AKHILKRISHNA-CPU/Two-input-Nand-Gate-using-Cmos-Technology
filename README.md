# Two-input-Nand-Gate-using-Cmos-Technology
This repository presents the design of Two Input Nand Gate Using Cmos Technology implemented using Synopsis Custom Compiler on 28nm CMOS Technology.


# Table of Contents
 * [Introduction](#Introduction)
 * [Tools Used](#Tools-Used)
 * [Pre-Layout Schematics and Simulations](#Pre-Layout-Schematics-and-Simulations)
 * [Netlist of the Circuit](#Netlist-of-the-Circuit)
 * [Observations](#Observations)
 * [Author](#Author)
 * [Acknowledgements](#Acknowledgements)
 * [References](#References)


# Introduction:

In VLSI System Design, Phase Locked Loop (PLL) is an essential building block for many timing generator applications. It comprises of five essential blocks which are Phase Frequency detector, Charge Pump, Low pass filter, Voltage controlled oscillator and Frequency Divider. Among many different oscillators, LC and ring oscillators are the most commonly used ones. The LC VCO occupies more area, and the tuning range is very narrow. Ring VCO provides a wide tuning range, less power consumption with less area. Among many types of Ring oscillators, Current starved VCO offers a balance between the power, area, phase noise with wide tuning range. In PLL, VCO is the most sensitive block to leakage power, and it will affect the performance of PLL to a more considerable extent.The scope of this work is to present a low power Current Starved Voltage Controlled Oscillator with Differential cross-coupled inverters as delay stages instead of regular inverters. Couple of benefits of using this Differential Cross coupled inverter is that: one, leakage power can be reduced thereby reducing overall power consumption and two, phase noise is reduced making this circuit stable; Hence can be used in space applications such as Radiation hardening of PLL.
