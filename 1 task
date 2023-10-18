#include <iostream>
#include <cmath>

int discr(double a, double b, double c) {
    return b*b - 4*a*c;
}

int root1(double a, double b, double c) {
    return (sqrt(discr(a, b, c)) - b)/(2*a);
}

int root2(double a, double b, double c) {
    return (-sqrt(discr(a, b, c)) - b)/(2*a);
}

int main() {
    double a;
    double b;
    double c;
    std::cin >> a;
    std::cin >> b;
    std::cin >> c;
    if (discr(a, b, c) < 0) {
        std::cout << "No roots";
    } else if (discr(a, b, c) > 0){
        std::cout << root1(a, b, c) << " " << root2(a, b, c);
    } else if(discr(a, b, c) == 0) {
        std::cout << root1(a, b, c);
    }
}
