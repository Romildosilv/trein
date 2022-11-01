trein
 Aritmética //

int qde;
float total;
int main(){
	printf("Digite a quantidade de macas\n");
	scanf("%d", &qde);
	
	if(qde<12){
	total = qde*1.30;
	}
	else{
		total = qde*1.00;
	}
	printf("\nO preco total e %.2f", total);
	return 0;
}

