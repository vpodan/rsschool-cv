# Vladimir Poddubsky
---
## Contacts

   * Phone: +48 786 831 864
   * Email: vpod1242@gmail.com
   * GitHub:[vpodan](https://github.com)
   * Telegram: @vpod1212
## About myself
I'm a third-year student of mechatronics. And I would like to try out something new and interesting. And it is for this reason that I joined this course.
## Skills
   * Java (beginner)
   * C++ (beginner)

## Code examples
```
   int main(int argc, char** argv) {
 int i = 0, suma = 0, cyf_kontr, ean [13] = {};
 char znak;

 printf("Podaj kod EAN-13: ");
 while(scanf("%c", &znak) && (i < 12)) {
 ean[i] = znak - 48;
 i++;
 }

 for(i=1; i<12; i++) {
 if(i%2) {
 suma += ean[i];
 } else {
 suma += 3 * ean[i];
 }
 }

 suma %= 10;
 if(suma) {
 cyf_kontr = 0;
 } else {
 cyf_kontr = 10 - suma;
 }

 if(cyf_kontr = ean[13]) {
 printf("OK. Kod EAN-13 poprawny\n");
 } else {
 printf("Blad. Kod EAN-13 niepoprawny\n");
 }

 _getch();
 return (EXIT_SUCCESS);
 }
```
    

## Work experience:

## Education
  * Gdansk University of Technology
## Languages:
1. Russsian (native)
2. Belarussian
3. English (**B1**)
4. Polish (**B2**)



   
   
