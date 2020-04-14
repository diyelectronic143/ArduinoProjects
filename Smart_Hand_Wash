#include <Servo.h>
int val = 0 ;
Servo s1;
void setup()
{
  Serial.begin(9600);
  pinMode(2,INPUT);   
   s1.attach(11);     
}
void loop() 
{
  val = digitalRead(2);  
  Serial.println(val);  
  delay(100);
  
  if(val == 0 )
  {
       s1.write(90);
       delay(500);
  }
  else
  {
    s1.write(1);
  }
  }
