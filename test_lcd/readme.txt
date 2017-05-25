NodeMCU--LCDdisplay
1.การต่อ
   Arduino UNO => PIN 4 = SCL, PIN 5 = SDA
   NodeMCU Dev Kit => D1 = SCL, D2 = SDA
2.ตั้งค่าใน .ino
   LiquidCrystal_I2C lcd(0x27, 20, 4);  //for 16X2
   LiquidCrystal_I2C lcd(0x3F, 20, 4);    //for 20x4


***ต้องต่อกับช่องไฟ 5v เท่านั้น 3.3v ไม่ได้
