#include <iostream>
#include <string>
#include <sstream>
#include <string.h>
#include <cstring>
#include <math.h>
using namespace std;

int horarios(int hora, int minutos){
	
	if (hora==7 || hora==8 || hora==9 || hora==16 || hora==17 || hora==18 || hora==19){
		
		if (hora==9 || hora==19){
			if (minutos<=29){
				cout<<"\nNo circula";
			}else{
				cout<<"\nPuede circular";
			}
		}else{
			cout<<"\nNo circula";
		}
	
	}else{
		cout<<"\nPuede circular";
	}
}	

int main(){
	/* 
	
	Se ha creado un Calendario del 2020  
	lunes = 1
	martes = 2
  	miercoles = 3
   	jueves = 4
 	viernes = 5
  	sabado = 6
  	domingo = 7
	*/
	
	int enero[31];
	int febrero[29];
	int marzo[31];
	int abril[30];
	int mayo[31];
	int junio[30];
	int julio[31];
	int agosto[31];
	int septiembre[30];
	int octubre[31];
	int noviembre[30];
	int diciembre[31];
	
 	int aux = 3;
 	for (int i=0;i<31;i++){
 		enero[i] = aux;
 		julio[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;
 		
	 }
	 
	 aux = 6;
	 for (int i=0;i<29;i++){
 		febrero[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;
 	}
 	 aux = 7;
 	for (int i=0;i<31;i++){
 		marzo[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 3;
 	for (int i=0;i<30;i++){
 		abril[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }	
	 
	  aux = 5;
 	for (int i=0;i<31;i++){
 		mayo[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 1;
 	for (int i=0;i<30;i++){
 		junio[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 6;
 	for (int i=0;i<31;i++){
 		agosto[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 2;
 	for (int i=0;i<30;i++){
 		septiembre[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 4;
 	for (int i=0;i<31;i++){
 		octubre[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 7;
 	for (int i=0;i<30;i++){
 		noviembre[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	  aux = 2;
 	for (int i=0;i<31;i++){
 		diciembre[i] = aux;
 		
 		if (aux==7){
 			aux = 0;
		 }
 		aux = aux + 1;	
	 }
	 
	 float time = -1;
	 int placa = -1;
	 int n = 1;
	 int f = 1;
	 int vacia = 0;
	 string fecha;
	 string fecha_separada;
	 string mes;
	 string dia;
	 int mes_num;
	 int dia_num;
	 
	 cout<<"                   PICO Y PLACA\n              ";
	 cout<<"\nINTERFAZ PARA VERIFICAR LA CIRCULACION DEL VEHICULO\n";
	 
	 while (n==1){
	 	int c=0;
	 	cout<<"\nIngrese la fecha (enero_dd)(ej. enero_31): ";
	 	cin>>fecha;
	 	
	 	stringstream stream(fecha);
    	while (getline(stream, fecha_separada, '_') ){
    	
    	if (c==0){
    		 mes = fecha_separada;
		}
    	if (c==1){
    		 dia = fecha_separada;
    		
		}
		c=c+1;
	}
        
	 		istringstream(dia)>>dia_num;
	
			char cstr[mes.size()+1];
			strcpy(cstr,mes.c_str());
			
		if (strcmp(cstr,"enero")==0){
		 mes_num=1;
		}
			
		if (strcmp(cstr,"febrero")==0){
		 mes_num=2;
		}
	
		if (strcmp(cstr,"marzo")==0){
		 mes_num=3;
		}
		
		if (strcmp(cstr,"abril")==0){
		 mes_num=4;
		}
		
		if (strcmp(cstr,"mayo")==0){
		 mes_num=5;
		}
		
		if (strcmp(cstr,"junio")==0){
		 mes_num=6;
		}
		
		if (strcmp(cstr,"julio")==0){
		 mes_num=7;
		}
		
		if (strcmp(cstr,"agosto")==0){
		 mes_num=8;
		}	
	
		if (strcmp(cstr,"septiembre")==0){
		 mes_num=9;
		}
		
		if (strcmp(cstr,"octubre")==0){
		 mes_num=10;
		}
		
		if (strcmp(cstr,"noviembre")==0){
		 mes_num=11;
		}
		
		if (strcmp(cstr,"diciembre")==0){
		 mes_num=12;
		}
	
	
		
		switch(mes_num){
			case 1:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
			    main();
				}
				
				break;
			
			case 2:
				n=0;
				if(dia_num>29 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 3:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 4:
				n=0;
				if(dia_num>30 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
				
			case 5:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
				
			case 6:
				n=0;
				if(dia_num>30 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
				
			case 7:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 8:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 9:
				n=0;
				if(dia_num>30 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 10:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 11:
				n=0;
				if(dia_num>30 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
			
			case 12:
				n=0;
				if(dia_num>31 || dia_num<=0){
				cout<<"Ingrese correctamente la fecha\n";
				main();
				}
				break;
		
		default:
			n=1;
		}
		}
		
		while (placa < 0){
	 	
	 	cout<<"\nIngrese los numeros de la placa de su vehiculo: ";
	 	cin>>placa;
	 }
	 
	 int digito;
	 int hora;
	 int minutos=70;
	 while (time<0 || minutos>59){
	 
		cout<<"\nIngrese la hora que circula (hh.mm)(ej. 16.00): ";
		cin>>time;
		hora = time;
	 	minutos = 100*(time-hora);
	 }
	 

	 
	 
	 digito = placa%10;
	 
	 
	
	 
	 switch (mes_num){
	 	case 1:
	 		dia_num = enero[dia_num-1];
	 		break;
	 	
	 	case 2:
	 		dia_num = febrero[dia_num-1];
	 		break;
	 		
	 	case 3:
	 		dia_num = marzo[dia_num-1];
	 		break;
	 		
	 	case 4:
	 		dia_num = abril[dia_num-1];
	 		break;
	 	
	 	case 5:
	 		dia_num = mayo[dia_num-1];
	 		break;
	 	
	 	case 6:
	 		dia_num = junio[dia_num-1];
	 		break;
	 	
	 	case 7:
	 		dia_num = julio[dia_num-1];
	 		break;
	 	
	 	case 8:
	 		dia_num = agosto[dia_num-1];
	 		break;
	 		
	 	case 9:
	 		dia_num = septiembre[dia_num-1];
	 		break;
	 		
	 	case 10:
	 		dia_num = octubre[dia_num-1];
	 		break;
	 		
	 	case 11:
	 		dia_num = noviembre[dia_num-1];
	 		break;
	 		
	 	case 12:
	 		dia_num = diciembre[dia_num-1];
	 		break;
	 }
	 
	 switch (dia_num){
	 
    case 1:
    if (digito==1 || digito==2){
    	horarios(hora,minutos);
    }else{
      cout<<"\nPuede circular";
    }
    break;
    case 2:
    if (digito==3 || digito==4){
     	horarios(hora,minutos);
    }else{
      cout<<"\nPuede circular\n";
	}
	break;
    case 3:
    if (digito==5 || digito==6){
        horarios(hora,minutos);
    }else{
        cout<<"\nPuede circular\n";
	}
	break;
    case 4:
    if (digito==7 || digito==8){
    	horarios(hora,minutos);
    }else{
       cout<< "\nPuede circular\n";
    }
    break;
    case 5:
    if (digito==9 || digito==0){
    	horarios(hora,minutos);
    }else{
    cout<<"\nPuede circular\n";
    }
    break;
    case 6:
        cout<<"\nPuede circular";
        break;
    case 7:
        cout<<"\nPuede circular";
    break;
    }
}
