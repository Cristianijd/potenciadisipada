using namespace std;

int main() {
    float Potencia;
    float Voltaje;
    float Resistencia = 10;
    float I;//Resistencia;

    cout << "Indica el valor de Voltaje: ";
    cin >> Voltaje;

    I = Voltaje / Resistencia;
    Potencia = I * I * Resistencia;


    cout << "El valor de la potencia es: " << Potencia << endl;

    if (Potencia > 22.4) {
        cout << "Hubo un cortocircuito.\n" << endl;

    } else {
        cout << "El circuito funciona normalmente.\n" << endl;

    }

    return 0;
}
