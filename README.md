struct Carta carta1;
struct Carta carta2;

// Dados da Carta 1 (fornecidos)
carta1.codigo[0] = 'A';
carta1.codigo[1] = '0';
carta1.codigo[2] = '1';
carta1.codigo[3] = '\0';
carta1.populacao = 432957;
carta1.area = 281.033;
carta1.pib = 24.04;
carta1.pontosTuristicos = 0; // pode ser ajustado

// Dados da Carta 2 (fornecidos)
carta2.codigo[0] = 'B';
carta2.codigo[1] = '0';
carta2.codigo[2] = '2';
carta2.codigo[3] = '\0';
carta2.populacao = 12000000;
carta2.area = 1521.0;
carta2.pib = 748.0;
carta2.pontosTuristicos = 0; // pode ser ajustado

// Exibição dos dados
printf("Dados da Carta 1:\n");
printf("Código: %s\n", carta1.codigo);
printf("População: %d\n", carta1.populacao);
printf("Área: %.3f km²\n", carta1.area);
printf("PIB: %.2f bilhões\n", carta1.pib);
printf("Pontos Turísticos: %d\n", carta1.pontosTuristicos);

printf("\n");

printf("Dados da Carta 2:\n");
printf("Código: %s\n", carta2.codigo);
printf("População: %d\n", carta2.populacao);
printf("Área: %.3f km²\n", carta2.area);
printf("PIB: %.2f bilhões\n", carta2.pib);
printf("Pontos Turísticos: %d\n", carta2.pontosTuristicos);

return 0;
