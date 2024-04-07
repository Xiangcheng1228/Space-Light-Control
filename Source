int ButtonState=0;
void setup() 
{
  // put your setup code here, to run once:
pinMode(INPUT,2);
pinMode(OUTPUT,3);
pinMode(OUTPUT,4);
pinMode(OUTPUT,5);
}

void loop()
{
  // put your main code here, to run repeatedly:
ButtonState = digitalRead(2);
if(ButtonState == LOW)
{
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
}
else
{
  digitalWrite(3,LOW);
    digitalWrite(4,HIGH);
    digitalWrite(5,HIGH);
    delay(1000);
    digitalWrite(4,HIGH);
    digitalWrite(5,LOW);
    delay(1000);
    digitalWrite(4,LOW);
    digitalWrite(5,HIGH);
    delay(1000);
    digitalWrite(4,LOW);
    digitalWrite(5,LOW);
    delay(1000);//按键按下时，绿灯不亮，4号引脚红灯以2秒间隔闪烁（亮2秒灭2秒），5号引脚红灯以1秒间隔闪烁（亮1秒灭1秒）。
}
delay(500);//休息500毫秒
}
