# HIGH PSRR BANDGAP REFERENCE (BGR) DESIGN

**Authors:** Trong Hieu Tran (Hira) 

**Organization:** Viettel High Tech Company

![Logo](figure/viettel_semicon_logo.jpg)

**Date (last upadated):** 26th June 2025  

## Abstract
This report details the design, implementation, and verification of a high-performance CMOS Bandgap Reference (BGR) circuit targeting a stable 1.2V output. The architecture incorporates advanced techniques to achieve stringent performance goals, including higher-order temperature curvature correction to achieve a low temperature coefficient...

![Logo](viettel_semicon_logo.jpg)

## Design Specifications

![Design Specs](spec1.jpg)

![PVT Corner Table](spec2.jpg)

## Circuit Architecture

![Block Diagram](blockDia.PNG)

### Error Amplifier

![Error Amp](error_amp.PNG)

![Amp Comparison](amp_compare.jpg)

### Curvature Correction

![VBE Calculation](VBE.PNG)

![Curvature Correction Principle](curvature.PNG)

### High PSRR Techniques

![Gain Boosting](IMPboosting.PNG)

![Feedforward Cancellation](noise.PNG)

### Start-Up Circuit

![Startup Circuit](startup.png)

![DC Response](DCres.jpg)

### Output LPF

![Lowpass Filter](LPF.PNG)

### Power-Down Switch

![Power Down Schematic](PWD.PNG)

![Vref when ON](PWDON.jpg)

![Vref when OFF](PWDOFF.jpg)

## Simulation Results

![Vref vs Temp](DC_temp.PNG)

![DC Table](DC_temp_table.PNG)

![PSRR and STB](psrr_stb.PNG)

![PSRR Table](psrr_stb_1.PNG)

## Monte Carlo Analysis

![MC Sensitivity](monte1.PNG)

![MC Summary](monte2.PNG)

![3 Sigma Deviation](monte3.jpg)

## Trimming Result

![Trim Result Graph](trim_res.png)

![1-Bit Trim Result](trim_result_1.jpg)

