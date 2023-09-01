#include <stdio.h>

int longitud_cadena(char *cadena);

int main() {
	char cadena[100];
	printf("Ingrese una cadena: ");
	scanf("%s", cadena);
	int longitud = longitud_cadena(cadena);
	printf("La longitud de la cadena es %d.\n", longitud);
	return 0;
}

int longitud_cadena(char *cadena) {
	int longitud = 0;
	while (*cadena != '\0') {
		longitud++;
		cadena++;
	}
	return longitud;
}
