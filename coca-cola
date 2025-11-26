#include <stdio.h>
int main() {
	int dinheiro, cascos, retornavel, pagamento, tipoCartao, preco;
	
	printf("COMPRA DE COCA COLA \n");
	printf("Digite quanto reais voce tem:"); //digite quantos reais você possui
	scanf("%d", &dinheiro);
	printf("Digite quantos cascos voce tem: ");//digite quantos cascos você possui
	scanf("%d", &cascos);
	printf("A Coca e retornavel? digite 1 para sim e 2 para não: ");//digite se a coca é retornável ou não
	scanf("%d", &retornavel);
	printf("Forma de pagamento? digite 1 para dinheiro e 2 para cartão: ");//digite a forma de pagamento dinheiro ou cartão
	scanf("%d", &pagamento);
	if (pagamento == 2) {
		printf("Cartao de (1 = debito / 2 = credito): "); //digite se seu cartão é debito ou crédito
		scanf("%d", &tipoCartao);
	}
	if (retornavel == 1) {
		preco = 7;
	} else {
		preco = 10;
	}
	if (retornavel == 1 && cascos < 1) {
		printf("Voce precisa de pelo menos 1 casco para comprar a retornavel!\n");
	}
	else if (dinheiro >= preco) {
		printf("\nCompra aprovada!\n");
		if (retornavel == 1) {
			printf("Voce comprou uma Coca retornavel.\n");
		} else {
			printf("Voce comprou uma Coca normal.\n");
		}
		if (pagamento == 1) {
			printf("Pagamento feito em dinheiro.\n");
		} else if (pagamento == 2 && tipoCartao == 1) {
			printf("Pagamento feito no cartao de debito.\n");
		} else if (pagamento == 2 && tipoCartao == 2) {
			printf("Pagamento feito no cartao de credito.\n");
		}
		for (int i = 1; i <= 3; i++) {
			printf("Você comprou a coca (%d)\n", i);
		}
	} else {
		printf("\nVoce nao tem dinheiro suficiente.\n");
	}
}
