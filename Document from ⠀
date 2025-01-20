#include<iostream>
using namespace std;
class complex{
    private:
            int real;
            int imag;
    public:
           void print(){
               cout<<this->real<<" "<<" + "<<this->imag<<" i "<<endl;
           }
           void setvalues(int x,int y){
               this->real=x;
               this->imag=y;
           }
           complex(){
               real=0;
               imag=0;
               
           }
           complex(int a){
               real=imag=a;
           }
           complex(int a,int b){
               real=a;
               imag=b;
           }
           complex add(complex t){
               complex temp;   
               temp.real=real+t.real;
               temp.imag=imag+t.imag;
           }
};
int main(){

complex c1,c2,c3;
c1.setvalues(2,4);
c2.setvalues(3,5);
c3=c2.add(c1);
c3.print();

return 0;

    
}
