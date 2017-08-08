# 8-8-MAX7219-Matrix-Module
code 9 to 0
#include "LedControl.h"
LedControl lc = LedControl(12, 11, 10, 1);
int m = 9;
void setup() {
  lc.shutdown(0,false);  // 關閉省電模式
  lc.setIntensity(0,8);  // 設定亮度為 8 (介於0~15之間)
  lc.clearDisplay(0);    // 清除螢幕
}
void loop() 
{
  num(m);
}
void num(int a)
{
  switch(a)
  {
    case 9:
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,4,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,4,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 8:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,2,1);lc.setLed(0,2,3,1);lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,4,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,4,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 7:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,7,1);
    lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 6:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,2,1);lc.setLed(0,2,3,1);lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,4,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,4,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 5:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,4,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,4,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 4:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,4,1);
    lc.setLed(0,4,4,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 3:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,4,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,4,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,4,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 2:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,2,1);lc.setLed(0,2,3,1);lc.setLed(0,2,4,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,4,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,4,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    m--;
    break;
    case 1:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,6,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,2,1);lc.setLed(0,3,3,1);lc.setLed(0,3,4,1);lc.setLed(0,3,5,1);lc.setLed(0,3,6,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,2,1);lc.setLed(0,4,3,1);lc.setLed(0,4,4,1);lc.setLed(0,4,5,1);lc.setLed(0,4,6,1);lc.setLed(0,4,7,1);
    m--;
    break;
    case 0:
    delay(1000);
    lc.clearDisplay(0);
    lc.setLed(0,2,1,1);lc.setLed(0,2,2,1);lc.setLed(0,2,3,1);lc.setLed(0,2,4,1);lc.setLed(0,2,5,1);lc.setLed(0,2,6,1);lc.setLed(0,2,7,1);
    lc.setLed(0,3,1,1);lc.setLed(0,3,7,1);
    lc.setLed(0,4,1,1);lc.setLed(0,4,7,1);
    lc.setLed(0,5,1,1);lc.setLed(0,5,2,1);lc.setLed(0,5,3,1);lc.setLed(0,5,4,1);lc.setLed(0,5,5,1);lc.setLed(0,5,6,1);lc.setLed(0,5,7,1);
    delay(1000);
    m = 9;
    break;
  }
}
