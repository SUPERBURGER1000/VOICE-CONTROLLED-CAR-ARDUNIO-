# VOICE-CONTROLLED-CAR-ARDUNIO-
This is the code for the voice controlled car using ardunio

string voice;

void setup()

{

  Serial.begin(9600);

  pinMode(3, OUTPUT);  

  pinMode(4, OUTPUT);  

  pinMode(5, OUTPUT); 

  pinMode(6, OUTPUT);  

}

void loop()

{ 

  while(Serial.available()>0)

  {

    delay(10);

    char c=Serial.read();

    if(c=='#')

    {

      break;

    }

    voice+=c;

    }

   if(voice=="forward"){

    digitalWrite(3, LOW);

    digitalWrite(4, HIGH);

    digitalWrite(5, LOW);

    digitalWrite(6, HIGH);

     delay(500);

    }

  else

    if(voice=="back"){

    digitalWrite(3, HIGH);

    digitalWrite(4, LOW);

    digitalWrite(5, HIGH);

    digitalWrite(6, LOW); 

    delay(500);}

  else

   if(voice=="right"){

    digitalWrite(3, LOW);

    digitalWrite(4, HIGH);

    digitalWrite(5, HIGH);

    digitalWrite(6, LOW);

    delay(200);

    }

  else

   if(voice=="left"){

    digitalWrite(3, HIGH);

    digitalWrite(4, LOW);

    digitalWrite(5, LOW);

    digitalWrite(6, HIGH);

    delay(200);   }

  else

   if(voice=="dance"){

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

   digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

  digitalWrite (3, LOW);

  digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

  digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, LOW);

   digitalWrite (6, LOW);

   delay (400);

      digitalWrite(3, HIGH);

    digitalWrite (4, HIGH);

    digitalWrite(5,LOW);

    digitalWrite(6,LOW);

    delay(600);

    digitalWrite (3, LOW);

   digitalWrite (4, HIGH);

   digitalWrite (5, HIGH);

   digitalWrite (6, LOW);

   delay (500);

   digitalWrite (3, HIGH);

   digitalWrite (4, LOW);

   digitalWrite (5, LOW);

   digitalWrite (6, HIGH);

   delay (500);

}

   if(voice.length()>0)

    {

      Serial.println(voice);

       voice="";

    digitalWrite(3, LOW);

    digitalWrite(4, LOW);

    digitalWrite(5, LOW);

    digitalWrite(6, LOW);

    }

    }
