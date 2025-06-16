#include <stdio.h>

int main() {
    // Variáveis carta 1
    char estado1;
    char codigo1[4];
    char nome1[30];
    unsigned long int populacao1;
    float area1;
    float pib1;
    int pontos1;
    float densidadePopulacional1;
    float pibpercapita1;
    float superpoder1;



    // Variáveis carta 2
    char estado2;
    char codigo2[4];
    char nome2[30];
    unsigned long int populacao2;
    float area2;
    float pib2;
    int pontos2;
    float densidadePopulacional2;
    float pibpercapita2;
    float superpoder2;
    int vitoriaPopulacao, vitoriaArea, vitoriaPIB, vitoriaPontosTuristicos;
    int vitoriaDensidade, vitoriaPIBperCapita, vitoriaSuperPoder;

    // Carta 1
    printf("Digite os dados da carta 1:\n");
    printf("Estado (letra de A a H): ");
    scanf(" %c", &estado1);

    printf("Codigo da Carta (ex: A01, B03): ");
    scanf("%3s", codigo1);

    printf("Nome da Cidade (sem espacos): ");
    scanf("%s", nome1);

    printf("Populacao: ");
    scanf("%lu", &populacao1);

    printf("Area (km²): ");
    scanf("%f", &area1);

    printf("PIB: ");
    scanf("%f", &pib1);

    printf("Numero de Pontos Turisticos: ");
    scanf("%d", &pontos1);

    printf("\n");

     // Cálculo da densidade e PIB per capita da Carta 1
     densidadePopulacional1 = populacao1 / area1;
     pibpercapita1 = (pib1 * 10000000000) / populacao1;

    // Cálculo do super poder 1
    superpoder1 = (float)populacao1 + area1 + pib1 + pontos1 + pibpercapita1 + (1.0 / densidadePopulacional1);

    // Carta 2
    printf("Digite os dados da carta 2:\n");
    printf("Estado (letra de A a H): ");
    scanf(" %c", &estado2);

    printf("Codigo da Carta (ex: A01, B03): ");
    scanf("%3s", codigo2);

    printf("Nome da Cidade (sem espacos): ");
    scanf("%s", nome2);

    printf("Populacao: ");
    scanf("%lu", &populacao2);

    printf("Area (km²): ");
    scanf("%f", &area2);

    printf("PIB: ");
    scanf("%f", &pib2);

    printf("Numero de Pontos Turisticos: ");
    scanf("%d", &pontos2);

    printf("\n");

    // Cálculo da densidade e PIB per capita da Carta 2
     densidadePopulacional2 = populacao2 / area2;
     pibpercapita2 = (pib2 * 10000000000) / populacao2;

    // Cálculo do super poder 2
    superpoder2 = (float)populacao2 + area2 + pib2 + pontos2 + pibpercapita2 + (1.0 / densidadePopulacional2);

    // Comparação dos atributos
    vitoriaPopulacao = populacao1 > populacao2;
    vitoriaArea = area1 > area2;
    vitoriaPIB = pib1 > pib2;
    vitoriaPontosTuristicos = pontos1 > pontos2;
    vitoriaDensidade = densidadePopulacional1 < densidadePopulacional2; // menor vence
    vitoriaPIBperCapita = pibpercapita1 > pibpercapita2;
    vitoriaSuperPoder = superpoder1 > superpoder2;

    // Imprime carta 1
    printf("Dados da carta 1:\n");
    printf("Estado: %c\n", estado1);
    printf("Codigo da Carta: %s\n", codigo1);
    printf("Nome da Cidade: %s\n", nome1);
    printf("Populacao: %lu\n", populacao1);
    printf("Area (km²): %.2f\n", area1);
    printf("PIB: %.2f\n", pib1);
    printf("Numero de Pontos Turisticos: %d\n\n", pontos1);
    printf("Densidade Populacional: %.2f hab/km²\n", densidadePopulacional1);
    printf("PIB per Capita: %.2f reais\n", pibpercapita1);

    // Imprime carta 2
    printf("Dados da carta 2:\n");
    printf("Estado: %c\n", estado2);
    printf("Codigo da Carta: %s\n", codigo2);
    printf("Nome da Cidade: %s\n", nome2);
    printf("Populacao: %lu\n", populacao2);
    printf("Area (km²): %.2f\n", area2);
    printf("PIB: %.2f\n", pib2);
    printf("Numero de Pontos Turisticos: %d\n", pontos2);
    printf("Densidade Populacional: %.2f hab/km²\n", densidadePopulacional2);
    printf("PIB per Capita: %.2f reais\n", pibpercapita2);

    // Impressão dos resultados das comparações
    printf("\nComparacao de Cartas:\n");
    printf("Populacao: Carta %d venceu (%d)\n", vitoriaPopulacao ? 1 : 2, vitoriaPopulacao);
    printf("Area: Carta %d venceu (%d)\n", vitoriaArea ? 1 : 2, vitoriaArea);
    printf("PIB: Carta %d venceu (%d)\n", vitoriaPIB ? 1 : 2, vitoriaPIB);
    printf("Pontos Turisticos: Carta %d venceu (%d)\n", vitoriaPontosTuristicos ? 1 : 2, vitoriaPontosTuristicos);
    printf("Densidade Populacional: Carta %d venceu (%d)\n", vitoriaDensidade ? 1 : 2, vitoriaDensidade);
    printf("PIB per Capita: Carta %d venceu (%d)\n", vitoriaPIBperCapita ? 1 : 2, vitoriaPIBperCapita);
    printf("Super Poder: Carta %d venceu (%d)\n", vitoriaSuperPoder ? 1 : 2, vitoriaSuperPoder);

 //Comparação de cartas
    if (populacao1 > populacao2) {
        printf("Cidade 1 tem maior população.\n");
    } else {
         printf("Cidade 2 tem maior população.\n");
     }

     //Exibição do resultado
     printf("A cidade vencedora é: %s\n", nome1);

    return 0;
}
