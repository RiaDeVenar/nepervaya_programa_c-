# nepervaya_programa_c-
(Не)Перша програма на C++
#include <iostream>
#include <string>

int main() {
    std::string name;
    std::getline(std::cin, name);
    std::cout << "Привіт, " << name << "!" << std::endl;

    return 0;
}
