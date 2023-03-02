# tej3m-2-04-Arduino
// C++ code
//
void setup()

{

  pinMode(11, OUTPUT);

  pinMode(12, OUTPUT);

  pinMode(13, OUTPUT);

}



void loop()

{

  digitalWrite(11, HIGH);

  digitalWrite(12, LOW);

  digitalWrite(13, LOW);

  delay(1000); // Wait for 1000 millisecond(s)

  digitalWrite(11, LOW);

  digitalWrite(12, HIGH);

  digitalWrite(13, LOW);

  delay(1000); // Wait for 1000 millisecond(s)

  digitalWrite(11, LOW);

  digitalWrite(12, LOW);

  digitalWrite(13, HIGH);

  delay(1000); // Wait for 1000 millisecond(s)

  

  digitalWrite(11, HIGH);

  digitalWrite(12, HIGH);

  digitalWrite(13, LOW);

  delay(1000); // Wait for 1000 millisecond(s)

  digitalWrite(11, LOW);

  digitalWrite(12, HIGH);

  digitalWrite(13, HIGH);

  delay(1000); // Wait for 1000 millisecond(s)

  digitalWrite(11, HIGH);

  digitalWrite(12, HIGH);

  digitalWrite(13, HIGH);

  delay(1000); // Wait for 1000 millisecond(s)

}
