#include <iostream>
#include <thread>

void displayName(int number) {
    std::cout << "Amirhossein Mirjalili " << number << std::endl;
}

int main() {
    for (int counter = 0; counter < 10; counter++) {
        std::thread t(displayName, counter);
        t.join();
    }

    return 0;
}
