# questao11

float aloha[10], coisas[10][5], *pf, value = 2.2;
int i=3;

aloha[2] = value;
scanf("%f", &aloha);
aloha = value";   // inválida por ser argumentos tipos diferentes 
printf("%f", aloha);
coisas[4][4] = aloha[3];  //inválida pelo mesmo motivo
coisas[5] = aloha; // inválida por atribuição com tipo de array
pf = value;  //inválida por incompatibilidades de atribuições
pf = aloha;
