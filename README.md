Why do people like electronic music?

...

Emotional range. I feel that electronic music has a far broader emotional range than most traditional genres, though its expression is often much more nuanced. (The closest competitors I would offer are probably jazz and symphonic classical.) The types of feelings that electronic music can evoke are rarely as obvious or direct as the lyrically and melodically driven messages of most pop music. I feel that traditional genres typically offer consciously accessible narratives (particularly those with lyrical forms), whereas electronic music brings about more complex, subtle emotions that don't necessarily evolve in a linear or easily describable way.
...

E' proprio da qui che vorrei cominciare. Non potevo trovare una descrizone migliore per farti capire che la musica elettronica cerca di trasmettere delle emozioni senza parlarti. Come primo brano ho scelto una canzone che meglio di tutte riesce a toccare le emozioni:


1.Paul Kalkbrenner - Azure	
	Ho casualmente trovato un video per questa canzone e penso che sia perfetto per esprimere le emozioni che la 			canzone vuole trasmettere.
	https://www.youtube.com/watch?v=v6qP7iKUaSs
	




















#include <stdio.h>
#include <math.h> /* es -lm // chmod +x */ 


/* Esercizio 1:

Realizzare una funzione che, presi in input i tre coefficienti di un'equazione di secondo grado del tipo ax2 + bx + c = 0 letti tramite scanf, restituisca le soluzioni reali di tale equazione. Il programma dovrà controllare che tali soluzioni esistano, e distinguere i casi di due zeri reali coincidenti e due zeri reali distinti, stampando l'output opportunamente a seconda del caso. */
int main () {
	int scelta;
	printf("Choose the part to execute:\n\t1 \t: Part 1 (equation zeros)\n\t2 \t: Part 2 (Fibonacci sequence)\n\t3 \t: Part 3 (42)\n\tother \t: Exit\n\n");
	scanf("%d",&scelta);
	if (scelta == 1) {
		float a,b,c;
		float x, y;
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
			int inp, b;
			printf("Insert the index of Fibonacci element\n");
			scanf("%d",&inp);
			if (inp == 2 || inp == 1) { b = 1 }
			else {
				
	return 0; }






