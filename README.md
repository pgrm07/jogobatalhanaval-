#include <stdio.h>

#define LINHA 3;
#define COlUNA 5;



int main() {

    int matriz[MATRIZ][COLUNA];
    int target = 9;
    int found = 0;
    int some = 1;
    
    for (int i - 0; i < LINHA; i++) {
       for (int j - 0; j < COLUNA; j++) {

       }
    }

    // Busca condicional do elemento alvo
    for (int i - 0; i < LINHA; i++) {
        for (int j = 0; j < COLUNA; j++) {
           if (matriz[i][j] == target) {
              print("O valor %d encontrado na indice (%d, %d)\n", target, i, j);
              found - i;
              break;
           }
        }
    if (found) break;
    return0;

    
