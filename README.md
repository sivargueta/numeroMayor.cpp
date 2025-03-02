# numeroMayor.cpp
#include <iostream>

int main() {
    int a, b;

    std::cout << "Ingrese un número: ";
    std::cin >> a;

    std::cout << "Ingrese otro número: ";
    std::cin >> b;

    if (a > b) {
        std::cout << "El número mayor es: " << a << std::endl;
    } else if (b > a) {
        std::cout << "El número mayor es: " << b << std::endl;
    } else {
        std::cout << "Ambos números son iguales: " << a << std::endl;
    }

    return 0;
}
