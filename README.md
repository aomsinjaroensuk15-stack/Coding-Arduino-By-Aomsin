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
