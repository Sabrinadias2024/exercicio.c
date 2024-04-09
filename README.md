int main()

 {

 char letra;
 printf("Digite uma letra: ");
 scanf("%d", &letra);

 switch (letra) {
 case 'a':
 case 'e':
 case 'i':
 case 'o':
 case 'u':
 printf("Vogal\n");
 break;
 default:
 printf("Consoante\n");
 }
 return 0;
 }
