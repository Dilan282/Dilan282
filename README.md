#include <iostream>
using namespace std;

int main() {
    float pruebas, talleres, deberes, laboratorio, total;

    // Pedir las notas
    cout << "Nota de pruebas: "; cin >> pruebas;
    cout << "Nota de talleres: "; cin >> talleres;
    cout << "Nota de deberes: "; cin >> deberes;
    cout << "Nota de laboratorio: "; cin >> laboratorio;

    // Calcular el total ponderado
    total = (pruebas * 7) + (talleres * 5) + (deberes * 3) + (laboratorio * 2);

    // Verificar si aprueba o reprueba
    cout << ((total >= 14) ? "Aprobado" : "Reprobado") << endl;

    return 0;
}
