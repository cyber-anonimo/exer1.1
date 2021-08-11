# exer1.1
#include<iostream>
using namespace std;
int main(){
	int distancia = 0;
	int t = 0;
	int velocidade = 0;
	int litros_usados = 0;
	cout << "digite o tempo: ";
	cin >> t;

	cout << "digite a velocidade: ";
	cin >> velocidade;

	distancia = t * velocidade;
	cout << "a velocidade e: " << distancia;
	
	litros_usados = distancia / 12;
	
	cout << "foram gastos " << litros_usados << " litros.";	
	return 0;
}
//19	26	C:\Users\unicesumar\Desktop\exer1,1.cpp	[Error] expected ';' before 'litros_usados'
//12	2	C:\Users\unicesumar\Desktop\exer1,1.cpp	[Error] expected ';' before 'cin'
