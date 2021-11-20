#include "iostream"

using namespace std;

int main(){
   	
	
	float  jumlah_bitcoin , harga_pembelian , harga_saat_ini, rumus_persen ;
	long rumus_total; 

	
	//input//
	cin>>jumlah_bitcoin;
	cin>>harga_pembelian;
	cin>>harga_saat_ini;
	cout<< " "<< endl;
	
	
	rumus_total = (harga_saat_ini - harga_pembelian);
	rumus_persen = ((harga_saat_ini - harga_pembelian)/harga_pembelian)*100;
	
	
	
	
	//output//
	cout<< "kenaikan/penurunan  : "<< rumus_persen << " " << "%"   << endl;
	cout<< "keuntungan/kerugian : "<< rumus_total  << " " << "juta" << endl;
	
}
