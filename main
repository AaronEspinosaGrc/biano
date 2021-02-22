//original code by: jack michaelson
//http://www.cplusplus.com/forum/beginner/17579/
 
#include <cstdlib>
#include <iostream>
#include <conio.h>
#include <windows.h>
using namespace std;
bool arp;
char arpon;
int b3 = 246; // si
int cb4 = 246; // dob
int c4 = 261; //do4
int cs4 = 277; //do#
int db4 = 277; //reb
int d4 = 293; //re
int ds4 = 311; //re#
int eb4 = 311; //mib
int e4 = 329; //mi
int es4 = 349; //mi#
int fb4 = 329; // fab
int f4 = 349; //fa
int fs4 = 370; //fa#
int gb4 = 370; // solb
int g4 = 392; //sol
int gs4 = 415; //sol#
int ab4 = 415; //lab
int a4 = 440; //la 
int as4 = 466; //la#
int bb4 = 466; //sib
int b4 = 493; //si
int bs4 = 523; //si#
int cb5 = 493; //dob5
int c5 = 523; //do5
int cs5 = 554; // do#5
int db5 = 554; // reb5
int d5 = 587; // re5
int ds5 = 622 ; // re#5
int eb5 = 622; //mib5
int e5 = 659; //mi5
int es5 = 698; //mi#5
int fb5 = 659; //mib5
int f5 = 698; //fa5
int fs5 = 740; //fa#5
int main(int argc, char *argv[])
{
    
    int speed;
    cout << "Initial speed: ";
    cin >> speed;
    
  while(true){
              cout << "****************************************" << endl;   
              cout << "*Options** [z]: Speed [x]: Arpeggio"<< endl;
              cout << "Speed["<< speed << "] " "Arpegio[" << arpon << "]" << endl;
              cout << "****************************************" << endl;   
              cout << " º#w###e#######t###y###u#######o###p###º" << endl;
              cout << "  [#] [#]  |  [#] [#] [#]  |  [#] [#] " <<endl;
              cout << "  [#] [#]  |  [#] [#] [#]  |  [#] [#] " <<endl;
              cout << "  [#] [#]  |  [#] [#] [#]  |  [#] [#] " <<endl;
              cout << "   |   |   |   |   |   |   |   |   |  " <<endl;
              cout << " a | s | d | f | g | h | j | k | l |  " <<endl;
              cout << "º######################################º" <<endl;
              
              if(arp == 1){
                arpon = '@';
              }else{
                arpon = ' ';
              }
              char note = getch();
              //do re mi fa sol la si do re mi fa sol
              if(note == 'z'){ //configure speed
                cout << " "<<endl;
                cout << "Speed note: ";
                cin >> speed;                       
              }
              if(note == 'x'){ //Arpegio mode
                arp =  not arp;
                
              }
              if(note == 'a'){ //c4
                    Beep(c4,speed);
                      if(arp == true){
                            Beep(e4,speed);
                            Beep(g4,speed);
                      }
                      
                }
              if(note == 's'){ //d4
                      Beep(d4,speed);
                      
                      if(arp == true){
                            Beep(fs4,speed);
                            Beep(a4,speed);
                      }
                }     
              if(note == 'd'){//e4
                      Beep(e4,speed);
                      
                      if(arp == true){
                            Beep(gs4,speed);
                            Beep(b4,speed);
                      }
                }  
              if(note == 'f'){ //f4
                      Beep(f4,speed);
                      
                      if(arp == true){
                            Beep(a4,speed);
                            Beep(c5,speed);
                      }
                }
              if(note == 'g'){ //g4
                      Beep(g4,speed);
                      
                      if(arp == true){
                            Beep(b4,speed);
                            Beep(d5,speed);
                        }
                }
              if(note == 'h'){ //la
                      Beep(a4,speed);
                      
                      if(arp == true){
                            Beep(cs5,speed);
                            Beep(e5,speed);
                      }
                }     
              if(note == 'j'){ //si
                      Beep(b4,speed);
                      
                      if(arp == true){
                            Beep(ds5,speed);
                            Beep(fs5,speed);
                      }
                }                           
              if(note == 'k'){ //do
                      Beep(523,speed);
                      }                      
              if(note == 'l'){ //re
                      Beep(587,speed);
                      }
              if(note == ';'){
                      Beep(659,speed);
                      }  
              if(note == '\''){
                      Beep(698,speed);
                      } 
               if(note == '\\'){
                      Beep(784,speed);
                      } 
                      
               //rebemol mibemol solbemol labemol sibemol rebemol mibemol solbemol
               if(note == 'w'){
                      Beep(cs4,speed);
                      } 
                      if(note == 'e'){
                      Beep(ds4,speed);
                      }
                      if(note == 't'){
                      Beep(fs4,speed);
                      }
                      if(note == 'y'){
                      Beep(gs4,speed);
                      }
                      if(note == 'u'){
                      Beep(as4,speed);
                      }
                      if(note == 'o'){
                      Beep(cs5,speed);
                      }
                      if(note == 'p'){
                      Beep(ds5,speed);
                      }
                      if(note == '`'){
                      Beep(740,speed);
                      }     
                      
            system("cls");          
}  
    
    return EXIT_SUCCESS;
}
