#include <stdio.h>

int main() {

    //Rodrigo Martinez

    //Cadastro carta 1

    char estado1[23];
    char codigo1[20];
    char nomedacidade1[20];
    float populacao1;
    float areakm1;
    float pib1;
    int numerodepontos1;
    float densidadepopulacional1;
    float pibpercapita1;
    int resultado;
    float superpoder1;
    int opcao;

    //cadastro carta 2
    char estado2[23];
    char codigo2[20];
    char nomedacidade2[20];
    float populacao2;
    float areakm2;
    float pib2;
    int numerodepontos2;
    float densidadepopulacional2;
    float pibpercapita2;
    float superpoder2;



    //Entrada e saída dos dados da 1 carta abaixo:

    printf("Coloque o código da carta: \n");
    scanf("%s", &codigo1);


    printf("Coloque o estado abreviado (EX -> RJ,SP):\n");
    scanf("%s", &estado1);
  
  
    printf("Coloque o nome da cidade: \n");
    scanf("%s", &nomedacidade1);
    

    printf("Coloque a população: \n");
    scanf("%f", &populacao1);
    

    printf("Coloque a área em Km²: \n");
    scanf("%f", &areakm1);
    

    printf("Coloque o PIB: \n");
    scanf("%f", &pib1);
    

    printf("Coloque o núemro de pontos turísticos: \n");
    scanf("%d", &numerodepontos1);

    //Função para calcular a Densidade e PIB per Cápita da carta 1

    densidadepopulacional1 = (float)populacao1 / areakm1;
    pibpercapita1 = pib1 / populacao1; 


    //calculando o super poder carta 1
    superpoder1 = (float)populacao1 + areakm1 + pib1 + numerodepontos1 + pibpercapita1 + (1 / densidadepopulacional1);
    
    //exibir as informações da carta 1 cadastrada

    printf("Carta 1\n");
    printf("Código da Carta: %s\n", codigo1);
    printf("Estado: %s\n", estado1);
    printf("Nome da Cidade: %s\n", nomedacidade1);
    printf("População: %.0f\n", populacao1);
    printf("Área: %.2f Km²\n", areakm1);
    printf("PIB: %.2f Bilhões de reais\n", pib1);
    printf("Quantidade de pontos Turísticos: %d\n", numerodepontos1);
    printf("Densidade Populacional é: %.2f hab/Km²\n", densidadepopulacional1);
    printf("PIB per Cápita é: %.2f Bilhões de Reais\n", pibpercapita1);



    //Entrada e saída dos dados da 2 carta abaixo:
    printf("Coloque o código da carta2:\n");
    scanf("%s", &codigo2);


    printf("Coloque o estado abreviado (EX -> RJ,SP):\n");
    scanf("%s", &estado2);
  
  
    printf("Coloque o nome da cidade: \n");
    scanf("%s", &nomedacidade2);
    

    printf("Coloque a população: \n");
    scanf("%f", &populacao2);
    

    printf("Coloque a área em Km²: \n");
    scanf("%f", &areakm2);
    

    printf("Coloque o PIB: \n");
    scanf("%f", &pib2);
    

    printf("Coloque o núemro de pontos turísticos: \n");
    scanf("%d", &numerodepontos2);

    //Função para calcular a Densidade e PIB per Cápita da carta 1

    densidadepopulacional2 = (float)populacao2 / areakm2;
    pibpercapita2 = pib2 / populacao2; 


    //calculando super poder carta 2

    superpoder2 = (float)populacao2 + areakm2 + pib2 + numerodepontos2 + pibpercapita2 + (1 / densidadepopulacional2);


    
    //exibir as informações da carta 2 cadastrada

    printf("Carta 2\n");
    printf("Código da Carta2: %s\n", codigo2);
    printf("Estado: %s\n", estado2);
    printf("Nome da Cidade: %s\n", nomedacidade2);
    printf("População: %.0f\n", populacao2);
    printf("Área: %.2f Km²\n", areakm2);
    printf("PIB: %.2f Bilhões de reais\n", pib2);
    printf("Quantidade de pontos Turísticos: %d\n", numerodepontos2);
    printf("Densidade Populacional é: %.2f hab/Km²\n", densidadepopulacional2);
    printf("PIB per Cápita é: %.2f Bilhões de Reais\n", pibpercapita2);


    //comparando as cartas

    printf("*** Escolha o atributo que você deseja comparar ***\n");
    printf("1 - População.\n");
    printf("2 - Área.\n");
    printf("3 - PIB.\n");
    printf("4 - Número de pontos turísticos\n");
    printf("5 - Densidade demográfica.\n");
    scanf("%d" , &opcao);

    // Exibindo resultados:

    printf("### RESULTADO COMPARAÇÃO ###\n");
    printf("### %s X %s ###\n", nomedacidade1, nomedacidade2);
    switch (opcao){

        case 1: 
            printf("Vamos comparar a população:\n");
            printf("A população de %s é: %lu hab. População de %s é: %lu hab.\n" , nomedacidade1 , populacao1 , nomedacidade2 , populacao2);
        
            if (populacao1 > populacao2)
            { 
                printf("### A CARTA UM VENCEU!! ###\n");
            } else if (populacao1 < populacao2)
            {
                printf("### A CARTA DOIS VENCEU!! ###\n");
            } else {
                printf("### EMPATOU!! ###\n");
            }
        break;

        case 2: 
            printf("Vamos comparar a área:\n");
            printf("A área de %s é: %f km². A área de %s é: %f km².\n" , nomedacidade1 , areakm1, nomedacidade2 , areakm2);
        
            if (areakm1 > areakm2)
            { 
                printf("*** A CARTA UM VENCEU!! ***\n");
            } else if (areakm1 < areakm2)
            {
                printf("*** A CARTA DOIS VENCEU!! ***\n");
            } else {
                printf("*** EMPATOU!! ***\n");
            }
        break;

        case 3 :
            printf("Vamos comparar o PIB:\n");
            printf("O PIB de %s é: %lf. O PIB de %s é: %lf.\n" , nomedacidade1 , pib1, nomedacidade2 , pib2);
        
            if (pib1 > pib2)
            { 
                printf("### A CARTA UM VENCEU!! ###\n");
            } else if (pib1 < pib2)
            {
                printf("### A CARTA DOIS VENCEU!! ###\n");
            } else {
                printf("### EMPATOU!! ###\n");
            }
        break;

        case 4 :
            printf("Vamos comparar o número de pontos turísticos:\n");
            printf("%s tem %d pontos turísticos. %s tem %d pontos turísticos.\n" , nomedacidade1 , numerodepontos1, nomedacidade2 , numerodepontos2);
        
            if (numerodepontos1 > numerodepontos2)
            { 
                printf("### A CARTA UM VENCEU!! ###\n");
            } else if (numerodepontos1 < numerodepontos2)
            {
                printf("### A CARTA DOIS VENCEU!! ###\n");
            } else {
                printf("### EMPATOU!! ###\n");
            }
        break;
        
         case 5 :
            printf("Vamos comparar a densidade demográfica:\n");
            printf("A densidade demográfica de %s é: %f. A densidade demográfica de %s é: %f.\n" , nomedacidade1 , densidadepopulacional1, nomedacidade2 , densidadepopulacional2);
        
            if (densidadepopulacional1 < densidadepopulacional2)
            { 
                printf("### A CARTA UM VENCEU!! ###\n");
            } else if (densidadepopulacional1 > densidadepopulacional2)
            {
                printf("### A CARTA DOIS VENCEU!! ###\n");
            } else {
                printf("### EMPATOU!! ###\n");
            }
        break;

        default:
            printf("Opção inválida!\n");
        break;
    }

  


    return 0;
}
