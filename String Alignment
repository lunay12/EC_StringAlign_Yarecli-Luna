#include <iostream>
#include <string>

using namespace std;

int main() {
    std::string str;
    int width;

    std::cout << "Enter a string: ";
    std::getline(std::cin, str);

    std::cout << "Enter width: ";
    std::cin >> width;
  
    int len = str.length();

    if (len >= width) {
        cout << str << endl;
    } else {
        int pad = (width - len) / 2;
        cout << string(pad, ' ') << str << string(pad, ' ') << endl;
    }

    return 0;
}
