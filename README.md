/*Maria quer saber quantos litros de gasolina precisa colocar em seu carro e quanto vai gastar para
fazer uma viagem até a casa de sua irmã. Faça algoritmo que leia:
a) A distância da casa de Maria até sua irmã;
b) Consumo do carro de Maria (KM rodados / litro);
c) O preço da gasolina (litro).*/

#include <stdio.h>

    int main(){
        
        float distancia,consumo,preco,litro,custoViagem;
        
        printf("\nA distancia até a casa de Maria em Km: ");
        scanf("%f",&distancia);      
        printf("\nO consumo do carro é de (Km rodados / litro: ");
        scanf("%f",&consumo);
        printf("\nQual o valor do litro de gasolina (litro): ");
        scanf("%f",&preco);
       
        litro = distancia/consumo;
        custoViagem = litro * preco;
        
        printf("\nMaria irá gastar R$%.2f e precisa colocar %2.f litros",custoViagem,litro);

    return 0;
    
}
