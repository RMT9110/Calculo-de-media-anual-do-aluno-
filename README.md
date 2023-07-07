		#include<stdio.h>
		main(){
				int idade;
			char nome[100];
			float media,nota1,nota2,nota3,nota4;
				
			printf("Digite seu nome: ");
			scanf("%s",&nome);
			printf("Digite sua idade: ");
			scanf("%d",&idade);
			printf("Primeira nota: ");
			scanf("%f",&nota1);
			printf("Segunda Nota: ");
			scanf("%f",&nota2);
			printf("Terceira nota: ");
			scanf("%f",&nota3);
			printf("Quarta nota: ");
			scanf("%f",&nota4);	
			
			media=(nota1+nota2+nota3+nota4)/4;
			
			if (media>=6){
				printf("Aprovado \n ");
			}
			if ((media>=4)&&(media<6)){
				printf("Em recuperacao \n ");
				else{
					printf("Reprovado");
				}
	}	

			printf("media final do aluno: \n %.2f ",media);
	
		}
		
			
