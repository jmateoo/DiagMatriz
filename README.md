# DiagMatriz

#include <iostream>
#include <string.h>

void diagonal_1(int a[][3], int b);
 void diagonal_2( int a[][3], int b )
void recorrermatriz(void);
int main()
{



{
int matriz[3][3]={{1,2,3},{4,5,6},{7,8,9}};

int N=3;

    for(int i=0; i<3; i++)
{
    for(int j=0; j<N; j++)
    {
        std::cout<<"Matrix ["<<i<<"]["<<j<<"]: "<<matriz[i][j]<<std::endl;
    }
}

}

    void diagonal_1(int a[][3], int b);

        int suma = 0;
        for( int i=0; i<b; i++ ){
            for( int j=0; j<b; j++ ){
                if( i==j )
                    suma = suma + a[i][j];
            }
        }
        cout<<"Suma de elementos de la Diagonal 1 es: "<<suma<<endl;
    }

    void diagonal_2( int a[][3], int b );
        int suma = 0;
        for( int i=0; i<b; i++ ){
            for( int j=0; j<b; j++ ){
                if( i+j == b-1 )
                    suma = suma + a[i][j];
            }
        }
        cout<<"Suma de elementos de la Diagonal 2 es: "<<suma<<endl;
