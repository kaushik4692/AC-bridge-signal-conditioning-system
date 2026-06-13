# AC-Excited Wheatstone Bridge Measurement System Using LTspice

## Overview

This project presents the design and simulation of an AC-excited Wheatstone bridge measurement system for precision temperature measurement and signal conditioning. The system combines an AD8221 instrumentation amplifier, AD630 synchronous demodulator, and a multi-stage low-pass filter to recover low-level sensor signals while minimizing the effects of drift, thermoelectric offsets, and low-frequency noise.

## Objectives

* Design an AC-excited Wheatstone bridge measurement system.
* Implement instrumentation amplification using AD8221.
* Perform synchronous demodulation using AD630.
* Recover measurement information through low-pass filtering.
* Integrate experimental PID temperature-control data with a Pt100 RTD model.

## System Architecture

Pt100 RTD → AC Wheatstone Bridge → AD8221 Instrumentation Amplifier → AD630 Synchronous Demodulator → RC Low-Pass Filter → Conditioned Output

## Methodology

Experimental temperature-control-loop error data obtained under PID control were converted into equivalent Pt100 RTD resistance variations. These resistance values were applied to the Wheatstone bridge model to evaluate the complete signal-conditioning chain under realistic process conditions.

## Key Features

* AC-excited bridge measurement
* Pt100 RTD modeling
* Instrumentation amplification
* Synchronous demodulation
* Low-pass filtering
* PID experimental data integration
* LTspice simulation

## Results

The simulation demonstrates successful amplification of low-level bridge signals, synchronous recovery of the measurement signal, and extraction of a stable output proportional to temperature variation.

## Tools Used

* LTspice
* AD8221 Instrumentation Amplifier Model
* AD630 Synchronous Demodulator Model

## Author

Kaushik Das
Applied Electronics and Instrumentation Engineering
University of Burdwan
