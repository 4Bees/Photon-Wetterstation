  This sketch prints the temperature, humidity, barometric pressure, altitude,
  soil moisture, and soil temperature to the Seril port. This sketch also
  incorporates the Weather Meters avaialbe from SparkFun (SEN-08942), which allow
  you to measure Wind Speed, Wind Direction, and Rainfall. Upload this sketch
  after attaching a soil moisture and or soil temperature sensor and Wetaher
  Meters to test your connections.

  Hardware Connections:
	This sketch was written specifically for the Photon Weather Shield,
	which connects the HTU21D and MPL3115A2 to the I2C bus by default.
  If you have an HTU21D and/or an MPL3115A2 breakout,	use the following
  hardware setup:
      HTU21D ------------- Photon
      (-) ------------------- GND
      (+) ------------------- 3.3V (VCC)
       CL ------------------- D1/SCL
       DA ------------------- D0/SDA

    MPL3115A2 ------------- Photon
      GND ------------------- GND
      VCC ------------------- 3.3V (VCC)
      SCL ------------------ D1/SCL
      SDA ------------------ D0/SDA

    Soil Moisture Sensor ----- Photon
        GND ------------------- GND
        VCC ------------------- D5
        SIG ------------------- A1

    DS18B20 Temp Sensor ------ Photon
        VCC (Red) ------------- 3.3V (VCC)
        GND (Black) ----------- GND
        SIG (White) ----------- D4
