# digital_switch

void setup() {
  // put your setup code here, to run once:
  pinMode(2, OUTPUT);
  pinMode(3, INPUT);

}

void loop() {
  // put your main code here, to run repeatedly:
  if (digitalRead(3) == HIGH) {
  //B of morse 
    digitalWrite(2, HIGH);
    delay(250);
    digitalWrite(2, LOW);
    delay(50);

    digitalWrite(2, HIGH);
    delay(100);
    digitalWrite(2, LOW);
    delay(50);

    digitalWrite(2, HIGH);
    delay(100);
    digitalWrite(2, LOW);
    delay(50);

    digitalWrite(2, HIGH);
    delay(100);
    digitalWrite(2, LOW);
    delay(500);

    digitalWrite(2, HIGH);
    delay(250);
    digitalWrite(2, LOW);
    delay(35);
    digitalWrite(2, HIGH);
    delay(250);
    digitalWrite(2, LOW);
    delay(35);
    digitalWrite(2, HIGH);
    delay(250);
    digitalWrite(2, LOW);
    delay(500);

    digitalWrite(2, HIGH);
    delay(250);
    digitalWrite(2, LOW);
    delay(50);
    digitalWrite(2, HIGH);
    delay(100);
    digitalWrite(2, LOW);
    delay(50);
    digitalWrite(2, HIGH);
    delay(100);
    digitalWrite(2, LOW);
    delay(50);
    digitalWrite(2, HIGH);
    delay(250);
    digitalWrite(2, LOW);
    delay(500);

  } else {
    digitalWrite(2, LOW);
  }
}
