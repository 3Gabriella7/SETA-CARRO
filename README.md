# SETA-CARRO
tinkercad update
// C++ code<BR>
//<BR>
<BR>
const int BTN1 = 0;<BR>
int cond = 0;<BR>
<BR>
void setup()<BR>
{<BR>
pinMode(11, OUTPUT);<BR>
pinMode(10, OUTPUT);<BR>
pinMode(7, OUTPUT);<BR>
pinMode(6, OUTPUT);<BR>
pinMode(BTN1, INPUT);<BR>
}<BR>
<BR>
void loop()<BR>
{<BR>
  <BR>
  cond = digitalRead(BTN1);<BR>
   <BR>
  if (cond == LOW) {<BR>
    <BR>
digitalWrite(11,HIGH);<BR>
digitalWrite(10,HIGH);<BR>
digitalWrite(7, LOW);<BR>
digitalWrite(6, LOW);<BR>
delay(500); // Wait for 500 millisecond(s)<BR>
  }<BR>
  <BR>
    if (BTN1 == LOW) {<BR>
digitalWrite(11,LOW);<BR>
digitalWrite(10,LOW);<BR>
digitalWrite(7, HIGH);<BR>
digitalWrite(6, HIGH);<BR>
      delay(500); // Wait for 500 millisecond(s)}<BR>
    }<BR>
  }<BR>
