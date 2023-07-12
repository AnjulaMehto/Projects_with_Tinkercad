/* 
  This program blinks LED connection to the pin number 13, 12, and 11 
*/  
int red = 13;
int green =12;
int org = 11;
void setup()  
{  
  pinMode(red, OUTPUT);  
  pinMode(green, OUTPUT);  
  pinMode(org, OUTPUT);  
}  
void loop()  
{  
 // the first LED is made to blink one time  
  digitalWrite(red, HIGH);  
  delay(1000); // delay time in milliseconds  
  digitalWrite(red, LOW);  
  delay(1000);  
  // the second LED will blink two times  
  digitalWrite(green,  HIGH);  
  delay(500); // the duration is 0.5 seconds  
  digitalWrite(green, LOW);  
  delay(500);  
  digitalWrite(green, HIGH);  
  delay(500);   
  digitalWrite(green, LOW);  
  delay(500);  
   // the third LED will blink three times  
  for( int i = 0; i < 3; i = i +1 )  
  {  
  digitalWrite(org, HIGH);  
  delay(500);   
  digitalWrite(org, LOW);  
  delay(500);  
    // Adjust the delay time accordingly  
  }  
}  
