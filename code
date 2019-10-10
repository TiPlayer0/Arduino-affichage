#include <Wire.h>
#include "rgb_lcd.h"

rgb_lcd lcd;

const int colorR = 0;
const int colorG = 0;
const int colorB = 255;

void setup() 
{
lcd.begin(16, 2);
}

void loop() 
{
//Mode nuit (pour voir dans le noir)
if (digitalRead(0) = HIGH) {
night = 4; //afficher un cycle de 4 données)
}

//Affichage des variable:

//Afficher la temperature:
lcd.setCursor(0, 1);
lcd.print("Temperature");
lcd.setCursor(1, 1);
lcd.print(temp);
lcd.setCursor(1, 4);
lcd.print("C");
delay(2000); //rester 2 seconde sur l'affichage
if (night != 0) {
night = night - 1;
}
if (digitalRead(0) = HIGH) {
night = 4; //afficher un cycle de 4 données)
}

//Afficher l'humidite
lcd.setCursor(0, 1);
lcd.print("Humidite");
lcd.setCursor(1, 1);
lcd.print(hum);
delay(2000);
if (night != 0) {
night = night - 1;
}
if (digitalRead(0) = HIGH) {
night = 4; //afficher un cycle de 4 données)
}

//Afficher la vitesse du vent
lcd.setCursor(0, 1);
lcd.print("Vitesse du vent");
lcd.setCursor(1, 1);
lcd.print(wind);
lcd.setCursor(1, 7);
lcd.print("Km.h");
delay(2000);
if (night != 0) {
night = night - 1;
}
if (digitalRead(0) = HIGH) {
night = 4; //afficher un cycle de 4 données)
}

//Afficher le sens du vent
lcd.setCursor(0, 1);
lcd.print(sens);
lcd.setCursor(1, 1);
lcd.print(gir);
lcd.setCursor(1, 4);
lcd.print("degre");
delay(2000);
if (night != 0) {
night = night - 1;
}
if (digitalRead(0) = HIGH) {
night = 4; //afficher un cycle de 4 données)
}
}
