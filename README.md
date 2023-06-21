// Online C++ compiler to run C++ program online
#include <iostream>

int main() {
    // chieu cao
    float x;
    std::cout << "chieu cao cua ban la ";
    std::cin >> x;
  std::cout << std::endl;
    // can nang 
    float y;
    std::cout << "can nang cua ban la ";
    std::cin >> y;
    // chi so bmi
    float z =y/(x*x);
    std::cout << "chi so bmi cua ban la " << z << std::endl;
    std::string ketqua;
    if (z < 18,5){ 
        ketqua = "gay";
    }
    else if (z > 25) {
        ketqua = "thua can";
    }
    
    else {
        ketqua = "binh thuong";

    }
    std::cout << "the trang cua ban la " << ketqua;
    return 0;
}
