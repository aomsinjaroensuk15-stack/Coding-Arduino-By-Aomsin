# Coding-Arduino-By-Aomsin
นี่คืองานของโรงเรียนที่ชื่อว่า Arduino IDE ผมจะมีตัวอย่างโค้ตให้กันนะครับ

# Code Slide
ผมจะเริ่มมีไฟล์หลังจากนนี้แล้วนะครับ เราจะเริ่มจากไฟล์แรกของ หน้า Arduino IDE กันก่อนเลย

## 01-01.ino
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}

## 02-01.ino
void setup() {
  Serial.begin(9600);
  Serial.println("Hello, World!");
  Serial.println(14, BIN);
}
void loop() {
  
}

## 02-02.ino
 void setup() { 
  Serial.begin(9600); 
  int x, y;
  char c = 'A';
  float f;
  x = 10;
  y = 20;
  f = y/3.0; 
  Serial.print("Value x = ");
  Serial.println(x); 
  Serial.print("Value y = ");
  Serial.println(y); 
  Serial.print("Value c = ");
  Serial.println(c); 
  Serial.print("Value f = ");
  Serial.println(f); 
}
void loop() {
  
}

## 02-03.ino
 int salary;              //ประกาศตัวแปรโกลบอล 
 void setup() {
  Serial.begin(9600);
  salary = 15000;         //กำหนดค่าให้ตัวแปร salary มีค่า 15000 
  Serial.print("Salary is = ");
  Serial.println(salary); //แสดงค่าในตัวแปร salary 
}
void loop() {
  
}

## 02-04.ino
 void setup() {
  Serial.begin(9600);
  int age = 25, height = 180, weight = 75; 
  Serial.print("Age = "); 
  Serial.println(age);
  Serial.print("Height = "); 
  Serial.println(height); 
  Serial.print("Weight = ");
  Serial.print(weight);
}

void loop() {
  // put your main code here, to run repeatedly:

}

## 02-05.ino
int age = 25, height = 180, weight = 75; 
void setup() {
  Serial.begin(9600);
  int age, height, weight; 
  Serial.print("Age = "); 
  Serial.println(age); 
  Serial.print("Height = "); 
  Serial.println(height); 
  Serial.print("Weight = ");
  Serial.println(weight);
}
void loop() {
  // put your main code here, to run repeatedly:
}

## 02-06.ino
const double pi = 3.141593; 
void setup() {
  Serial.begin(9600);
  double r = 12.4; 
  double area, circum, diameter;
  diameter = r * 2;
  circum = 2 * pi * r;
  area = pi * pow(r,2); 
  Serial.print("Diameter = "); 
  Serial.println(diameter); 
  Serial.print("Circum = "); 
  Serial.println(circum); 
  Serial.print("Area = ");
  Serial.println(area); 
}
void loop() {
  
}

## 02-07.ino
#define pi 3.141593
void setup() {
  Serial.begin(9600);
  double r = 12.4;
  double area, circum, diameter;
  diameter = r * 2;
  circum = 2 * pi * r;
  area = pi * pow(r,2); 
  Serial.print("Diameter = "); 
  Serial.println(diameter); 
  Serial.print("Circum = "); 
  Serial.println(circum); 
  Serial.print("Area = ");
  Serial.println(area); 
}
void loop() {
  // put your main code here, to run repeatedly:
}

## 02-08-01.ino
void setup() { 
  Serial.begin(9600); 
  int decNum = 123;
  int octNum = 0123;
  int hexNum = 0xFF; 
  Serial.print("DEC = "); 
  Serial.println(decNum); 
  Serial.print("OCT = "); 
  Serial.println(octNum); 
  Serial.print("HEX = ");
  Serial.println(hexNum); 
} 
void loop() {

}

## 02-08-02.ino
void setup() { 
  Serial.begin(9600); 
  int decNum = 123;
  int octNum = 0123;
  int hexNum = 0xFF; 
  Serial.print("DEC = "); 
  Serial.println(decNum); 
  Serial.print("OCT = "); 
  Serial.println(octNum, OCT); 
  Serial.print("HEX = ");
  Serial.println(hexNum, HEX); 
} 
void loop() {

}

## 03-01.ino
int a, b, av;
void setup() {
  Serial.begin(9600);
  a = random(0,100);
  b = random(0,100); 
  Serial.print("a = "); 
  Serial.println(a); 
  Serial.print("b = "); 
  Serial.println(b);
  av = (a+b)/2; 
  Serial.print("Average = ");
  Serial.println(av); 
} 
void loop() {
  
}

## 03-02.ino
void setup() { 
  Serial.begin(9600); 
  int A = 12, B = 8; 
  Serial.print("A++ = "); 
  Serial.println(A++); 
  Serial.print("A = "); 
  Serial.println(A); 
  Serial.print("++B = "); 
  Serial.println(++B);
}
void loop() {

}

## 03-03.ino
void setup() { 
  Serial.begin(9600); 
  int A = -2; 
  Serial.print("+A = "); 
  Serial.println(+A); 
  Serial.print("-A = ");
  Serial.println(-A); 
}
void loop() {

}

# continue
เดี๋ยวผมมาทำต่อครับ รู้สึกว่าเดี๋ยวเพื่อนตามไม่ทัน 555+
