mEDI measurements and mEDI calculations using ALFA simulations for a period of 10 days in a typical office in Copenhagen Denmark.

In total there are 1600 measurements and 1600 calculations with ALFA.

Parameters include:
- **Day &amp; Time**, 
- **Daylight / Electrical lighting**,
- **Direction of view**,
- **Position (distance from window)**,
- **Sky Type**.

Spectrometer used: **GL SPECTIS 1.0 Touch + Flicker** (mEDI was measured 120cm above the floor on a vertical plane)

Columns in dataset:
- **DAY**: Values 1 to 10
- **TIME**: 9 or 11 or 13 or 15 or 17 (each number corresponds to time eg 09.00am or 11.00am)
- **LIGHT**: DL or DL+EL (daylight or daylight+electrical light)
- **POSITION**: 1,8 or 4 (1,8m or 4m distance from the window)
- **DIRECTION**: window or task (towards window or towards the task desk)
- **mEDI**: the value of the measured melanopic Equivalent Daylight Illuminance
- **RECOMMENDATION**: measured mEDI value above or below the threshold (mEDI >= 250)
- **SKY TYPE**: the sky type during the measurement - the same sky type was used for the simulation
  
- ALFA mEDI: the calculated value of melanopic Equivalent Daylight Illuminance using ALFA simulation
- ALFA RECOMMENDATION: calculated mEDI value above or below the threshold (mEDI >= 250)
