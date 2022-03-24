# MyTube
#include <iostream>

using namespace std;
int main() {
    //for(int i=1;i<4;i++){
    
    
        for(int j=1;j<8;j++){
            if((j%2)!=0){
                for(int k=5;k>=j;k--){
                    cout<<" ";
                }
                for(int k=1;k<=j;k++){
                    cout<<" *";
                }
            }
            cout<<endl;
        }
        
        for(int j=7;j>=1;j--){
            if((j%2)!=0){
                for(int k=5;k>=j;k--){
                    cout<<" ";
                }
                for(int k=1;k<=j;k++){
                    cout<<" *";
                }
            }
            cout<<endl;
        }
        
        for(int j=2;j<8;j++){
            if((j%2)!=0){
                for(int k=5;k>=j;k--){
                    cout<<" ";
                }
                for(int k=1;k<=j;k++){
                    cout<<" *";
                }
            }
            cout<<endl;
        }
    //}

    return 0;
}
