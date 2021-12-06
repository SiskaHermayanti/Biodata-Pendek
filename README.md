#include <iostream>
using namespace std;

int main(){
	string Nama;
	string Jurusan;
	string Alamat;
	string NPM;
	
	cout<<"==================== INPUT ===================="<<endl;
	cout<<"Nama :";
	getline(cin,Nama);
	cout<<"Jurusan :";
	getline(cin,Jurusan);
	cout<<"Alamat :";
	getline(cin,Alamat);
	cout<<"NPM :";
	getline(cin,NPM);
	
	cout<<endl;
	
	cout<<"==================== OUTPUT ===================="<<endl;
	cout<<"Nama : "<<Nama<<endl;
	cout<<"Jurusan : "<<Jurusan<<endl;
	cout<<"NPM : "<<NPM<<endl;
	cout<<"Alamat : "<<Alamat<<endl;
	
	return 0;
}
