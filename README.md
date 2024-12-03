# Ovsiyenko_lab3

#include <iostream>

int main(){
    
    int a;
    int sum=0;
    int i=1;
    
    std::cout<<"Введіть число n:";
    std::cin>>a;
    
    do{
        sum+=i;
        ++i;
    }
    while(i<=a);
    
    std::cout<<"Сума чисел від 1 до "<<a<<": "<<sum<<std::endl;

    return 0;
}
