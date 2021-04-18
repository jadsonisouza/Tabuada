# Tabuada

#include<stdio.h>

main()

{
    int a=1, c;
    float b;
   
    printf("Digite um valor para tabuada \n");
    scanf("%f", &b);
    
    printf("\nEscolha a opção desejada\n");
    printf("1 - Soma\n");
    printf("2 - Subtracao\n");
    printf("3 - Multiplicacao\n");
    printf("4 - Divisão\n");
    scanf("%d", &c);
    
    switch(c)
        {
            case 1:
                while(a<=10)
            {
                printf("%.0f + %i = %.0f\n", b, a, b+a);
                ++a;
            }
            break;
            
            case 2:
                while(a<=10)
            {
                printf("%.0f - %i = %.0f\n", b, a, b-a);
                ++a;
            }
            break;
        
            case 3:
                while(a<=10)
            {
                printf("%.0f * %i = %.0f\n", b, a, b*a);
                ++a;
            }
            break;
            
            case 4:
                while(a<=10)
            {
                printf("%.0f / %i = %.2f\n", b, a, (b/a));
                ++a;
            }
            break;
            
            default : printf("Opcao incorreta\n");
        }
    
    return printf("\nSENAI CIMATEC\nStudent Jadson");
    
    
}
