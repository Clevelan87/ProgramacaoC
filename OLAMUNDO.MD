#include <stdio.h>
    
// Desafio Super Trunfo - Países
// Tema 1 - Cadastro das Cartas
// Este código inicial serve como base para o desenvolvimento do sistema de cadastro de cartas de cidades.
// Siga os comentários para implementar cada parte do desafio.
//Teste larissa

int main() {
    printf("CARTAS SUPER TRUNFO! \n");

    int codcidade;
    char nomecidade[50];
    int populacao;
    float area;
    float pib;
    int pontoturistico;
    // CODIGO DA CIDADE 
    printf("Codigo da cidade:\n");
    scanf("%d", &codcidade);
    // NOME DA CIDADE
    printf("Nome da Cidade:\n");
    scanf("%s", &nomecidade);
    // printf("Nome da Cidade:\n");
    //getchar(); // Consome o caractere de nova linha pendente
    //fgets(nomecidade, sizeof(nomecidade), stdin);

    // POPULAÇÃO
    printf("Digite a população da cidade:\n");
    scanf ("%d", &populacao);
    // AREA
    printf ("Digite a área da cidade:\n");
    scanf("%f", &area);
    // PIB
    printf ("Digite o Pib da Cidade:\n");
    scanf ("%f",&pib);
    // NUMEROS DE PONTOS TURISTICOS
    printf ("Digite o numero de pontos turisticos:\n");
    scanf ("%d", &pontoturistico);

    // SAINDA DE DADOS  
printf("\n--- DADOS DA CIDADE ---\n");
printf("\n CODIGO DA CIDADE: %d\n", codcidade);
printf("\n NOME DA CIDADE: %s\n", nomecidade);
printf("\n POPULAÇÃO DA CIDADE: %d\n", populacao);
printf("\n AREA DA CIDADE: %f\n", area);
printf("\n PIB DA CIDADE: %f\n", pib); 
printf("\n NUMERO DE PONTOS TURISTICOS: %d\n", pontoturistico);
//printf("\n");




    // Sugestão: Defina variáveis separadas para cada atributo da cidade.
    // Exemplos de atributos: código da cidade, nome, população, área, PIB, número de pontos turísticos.
    
    // Cadastro das Cartas:
    // Sugestão: Utilize a função scanf para capturar as entradas do usuário para cada atributo.
    // Solicite ao usuário que insira as informações de cada cidade, como o código, nome, população, área, etc.
    
    // Exibição dos Dados das Cartas:
    // Sugestão: Utilize a função printf para exibir as informações das cartas cadastradas de forma clara e organizada.
    // Exiba os valores inseridos para cada atributo da cidade, um por linha.

        return 0;
    }
