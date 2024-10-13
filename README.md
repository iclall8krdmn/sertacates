# sertacates
2023-2024 Eğitim ve Öğretim Yılı Bilişim Teknolojileri ve Yazılım Dersi Etkinlik Dosyaları (İFL2027)
![Grand Stantia-Fulffy](https://github.com/user-attachments/assets/a590a380-afb2-4175-8ecc-5afc1e9251e1)


// C++ code
//
void setup()
{
  pinMode(4, OUTPUT);
  pinMode(2, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(6, OUTPUT);
}

void loop()
{
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(3, LOW);
  digitalWrite(6, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4, LOW);
  digitalWrite(2, LOW);
  digitalWrite(7, LOW);
  digitalWrite(5, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(6, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
}
