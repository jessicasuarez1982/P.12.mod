# P.12.mod
practica 12 modificada
// C++ code
//
int ACTIVO = 0;

int bucle = 0;

void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);//led en on 
  digitalWrite(12, LOW);//led en off
  digitalWrite(11, HIGH);// activase o rele e a lampara acende co pin 13
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);// a secuencia repitese en bucle 
  digitalWrite(12, HIGH);
  digitalWrite(11, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
