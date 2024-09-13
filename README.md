# EXERCICIOS
#include <stdio.h>
#define PI 3.14 // Definindo a constante RAIO como 3,14
#include <math.h> // Biblioteca necessária para sqrt() e pow()
int main()
{
    float area, raio;
    printf("Digite o raio \n");
    scanf("%f", &raio);

    area = PI * pow(raio, 2) ;
    printf("Area total do circulo: %g \n", area);

    return 0;
}
