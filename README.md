Why do people like electronic music?

...

Emotional range. I feel that electronic music has a far broader emotional range than most traditional genres, though its expression is often much more nuanced. (The closest competitors I would offer are probably jazz and symphonic classical.) The types of feelings that electronic music can evoke are rarely as obvious or direct as the lyrically and melodically driven messages of most pop music. I feel that traditional genres typically offer consciously accessible narratives (particularly those with lyrical forms), whereas electronic music brings about more complex, subtle emotions that don't necessarily evolve in a linear or easily describable way.
...

E' proprio da qui che vorrei cominciare. Non potevo trovare una descrizone migliore per farti capire che la musica elettronica cerca di trasmettere delle emozioni senza parlarti. Come primo brano ho scelto una canzone che meglio di tutte riesce a toccare le emozioni:


1.Paul Kalkbrenner - Azure	
	Ho casualmente trovato un video per questa canzone e penso che sia perfetto per esprimere le emozioni che la 			canzone vuole trasmettere.
	https://www.youtube.com/watch?v=v6qP7iKUaSs
	




















#include <stdio.h>
#include <math.h>

int main () {
	int scelta;
	float a,b,c;
	float x, y;
	int inp, i;
	do{
		
		printf("Choose the part to execute:\n\t1 \t: Part 1 (equation zeros)\n\t2 \t: Part 2 (Fibonacci sequence)\n\t3 \t: Part 3 (42)\n\tother \t: Exit\n\n");
		scanf("%d",&scelta);
	if (scelta == 1) {

			printf("Insert the coefficient a b c separated by spaces\n");
			scanf("%f",&a);
			scanf("%f",&b);
			scanf("%f",&c);
			if ( (b*b - 4*a*c) > 0) {
				x = ( (-1*b) + (sqrt(b*b - 4*a*c)) ) / 2*a;
				y = ( (-1*b) - (sqrt(b*b - 4*a*c)) ) / 2*a;
				printf("The equation (%f x^2 + %f x + %f = 0) has ",a,b,c);
				printf("two zeros: %f, %f\n",x,y); }
			else { if ( (b*b - 4*a*c) == 0) {
					x = ( (-1*b) / 2*a);
					printf("The equation degree is less than two\n");
					printf("The equation (%f x^2 + %f x + %f = 0) has ",a,b,c);
					printf("only one zero: %f\n",x); }
					else { 
						printf("The equation degree is less than two\n");
						printf("The equation (%f x^2 + %f x + %f = 0) has ",a,b,c);
						printf("no real zeros.\n"); } }
	}
	else { if (scelta == 2) {
			float fib1=1.0, fib2=1.0, app=0.0;
			printf("Insert the index of Fibonacci element\n");
			scanf("%d",&inp);
			if (inp == 2 || inp == 1) { fib1 = 1; 
				printf("Fibonacci(%d) = %f\n", inp, fib1);}
			else { for(i=3; i<=inp; i++){
					app=fib1;
					fib1=fib1+fib2;
					fib2=app;
				}
				printf("Fibonacci(%d) = %f\n", inp, fib1);
			}
		}else {
		if(scelta == 3){
			int val1=0, val2=0, somma=0;
			printf("Enter an integer number\n");
			scanf("%d", &val1);
			while (somma != 42) {
				val2=val1;
				printf("Enter another integer number\n");
				scanf("%d", &val1);
				somma = val1 + val2;
				printf("Sum is %d\n", somma);}}
			
		}}
		}while(scelta >= 1 && scelta <=3);
				
	return 0;}
