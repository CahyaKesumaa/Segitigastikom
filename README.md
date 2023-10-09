# Segitigastikom
tugas segitiga stikom
#include <iostream>
using namespace std;
int main()
{
  //deklarasi
  int  datar, turun, baris;

  //input
  system("cls");
  cout << "Segitiga Siku Siku Terbalik "<<endl;
  cout << "input jumlah line: ";
  cin >> baris;

  //rumus
  for (datar = baris; datar >= 1; datar--)
  {
    for (turun = 1; turun <= datar; turun++)
    {
      if (1==turun || turun==11 || turun==21)
      {
        cout<<"S";
      }
      else if (2==turun || turun==12 || turun==22)
      {
        cout<<"T";
      }
      else if (3==turun || turun==13 || turun==23)
      {
        cout<<"I";
      }      
      else if (4==turun || turun==14 || turun==24)
      {
        cout<<"K";
      }
      else if (5==turun || turun==15 || turun==25)
      {
        cout<<"O";
      }
      else if (6==turun || turun==16 || turun==26)
      {
        cout<<"M";
      }
      else if (7==turun || turun==17 || turun==27)
      {
        cout<<"B";
      }
      else if (8==turun || turun==18 || turun==28)
      {
        cout<<"A";
      }
      else if (9==turun || turun==19 || turun==29)
      {
        cout<<"L";
      }         
      else
      {
        cout<<"I";
      }
        
    }
    cout << endl;
  }
  return 0;
}
