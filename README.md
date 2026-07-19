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
