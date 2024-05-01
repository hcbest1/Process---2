# Process---2

// active mode

size(500, 500);

fill(50, 100, 50);
rect(100, 100, 300, 300);

fill(200, 50, 100);
rect(200, 200, 300, 300);

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

// 스케치를 실행했을 때 최초 한 번만 그 내용이 실행된다.
void setup() {
   size(500, 500);
}

// 매 프레임마다 함수 내의 내용이 계속해서 실행이 된다.
void draw() {
   background(150, 0, 0);
   ellipse(mouseX, mouseY, 150, 150);
}

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

void setup() {

    size(200, 200);

    // 1. declare 선언
   // 2.initialize 최기화
    int life = 3;
    life = 3;

int d = 5.2

    int numpeople = 23;

    float temp = 23.5;
    float volume = 50.5;
    float brightness = 30.0;

    boolean raining = false;

char ch = '한' ;

String msg = "이 안에는 여러 문자들을 표현할 수 있습니다.";

String a = "3";
String b = "7";
println( a + b );

int x = 3;
int y = 7;
println( x + y );

color col #000000;

}

void draw() {

}

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

color c; // declare a global variable


void setup() {
   size(200, 200);
   c = color(0, 0, 200);
}

void draw() {
   background(c);


}

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

size(400, 400);

background( 255 );


//그리기 이전에 색을 설정해준다.

// stroke( 100 ); // 256 level (0 ~ 255) greyscale

stroke( #4FB98A ); // RGB color system
fill( 212, 240, 30 );
rect(50, 50, 200, 200);

stroke(0, 128); // alpha channel (0 ~ 255)
fill(255, 0, 0, 50);
rect(150, 150, 200, 200);


ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ


// HSB color mode

size(400, 400);

colorMode(HSB, 360, 100, 100, 100); // 0 ~ 255 => 256 level : 0 ~ 360 => 360 level

background(128);

blendMode(MULTIPLY);

fill(40, 70, 100);
ellipse(200, 200, 300, 300);

fill(210, 60, 100);
ellipse(300, 300, 300, 300);


ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ


void setup() {
    size(200, 200);
}

void draw() {
    background(234);


    strokeWeight(10);
    fill(200, 200, 100);
    beginShape();
    vertex(20, 20);
    vertex(80, 20);
    vertex(80, 40);
    vertex(40, 40);
    vertex(40, 60);
    vertex(60, 60);
    vertex(60, 80);
    vertex(40, 80);
    vertex(40, 120);
    vertex(20, 120);
    endShape(CLOSE);
}


ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ


void setup() {
    size(200, 200);
}

void draw() {
    background(234);
    
    stroke(255, 0, 0);
    noFill();
    strokeWeight(4);



    beginShape();
    vertex(20, 20);
    vertex(40, 20);
    vertex(40, 50);
    vertex(70, 50);
    vertex(70, 20);
    vertex(90, 20);
    vertex(90, 110);
    vertex(20, 110);

    beginContour();
    vertex(40, 70);
    vertex(40, 90);
    vertex(70, 90);
    vertex(70, 70);
    endContour();

    endShape(CLOSE);

}
