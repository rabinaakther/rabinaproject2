#include <stdio.h>

float celsiusTofahrenheit(float c);
float fahrenheitTocelsius (float f);
float celsiusTokelvin (float c);
float kelvinTocelsius (float k);
float fahrenheitTokelvin (float f);
float kelvinTofahrenheit(float k);
int main(){
int choice;
float input;
float result;
int i,n;
printf("How many temperature you want to perform?:");
scanf("%d",&n);
for(i=0;i< n; i++){
    printf("\n==conversation %d==\n",i+1);
    printf("1. celsius to fahrenheit\n:");
    printf("2. fahrenheit to celsius\n");
    printf("3. celsius to kelvin\n");
    printf("4. kelvin to celsius\n");
    printf("5. fahrenheit to kelvin\n");
    printf("6. kelvin to fahrenheit\n");
    printf("Enter your choice from (1-6):");
    scanf("%d",&choice);
    printf("Enter temperature:");
    scanf("%f",&input);
    switch(choice){
    case 1:
        result = celsiusTofahrenheit(input);
        printf("%.2f degC=%.2f\n",input,result);
        break;
    case 2:
        result = fahrenheitTocelsius(input);
        printf("%.2f degf=%.2f\n",input,result);
        break;
    case 3:
        result = celsiusTokelvin(input);
        printf("%.2f degC= %.2f\n",input ,result) ;
        break;
    case 4:
    result = kelvinTocelsius(input);
    printf("%.2f degK= %.2f\n",input,result);
    break;
    case 5:
    result = fahrenheitTokelvin(input);
    printf("%.2f degF= %.2f\n",input,result);
    break;
    case 6:
    result = kelvinTofahrenheit(input);
    printf("%.2f degK=%.2f\n",input,result);
    break;
    default:
    printf("invalid");
    }

}

printf("All conversations completed...\n");
return 0;
}

float celsiusTofahrenheit(float c){
    return (c * 9.0/5.0)+32;

}
float fahrenheitTocelsius(float f){
    return (f - 32)* 5.0/9.0;

}
float celsiusTokelvin(float c){
    return c + 273.15;

}
float kelvinTocelsius(float k){
    return k - 273.15;

}
float fahrenheitTokelvin(float f){
    return celsiusTokelvin(fahrenheitTocelsius(f));

}
float kelvinTofahrenheit(float k){
    return celsiusTofahrenheit(kelvinTocelsius(k));

}
