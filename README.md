# Exerc-cio-Algoritmos

Exercícios de Algoritmos utilizando (if)
#include <iostream>

\#include <cstdlib>

using namespace std;



int main()

{

&#x20;   string nome1, nome2, nome3, nome4, nome5, melhorAluno;

&#x20;   float n1, n2, n3, media1, media2, media3, media4, media5, maiorMedia;



&#x20;   cout << "Digite o nome do aluno: ";

&#x20;   cin >> nome1;

&#x20;   cout << "Digite as 3 notas: ";

&#x20;   cin >> n1 >> n2 >> n3;

&#x20;   media1 = (n1 + n2 + n3) / 3;

&#x20;   cout<<"\\nAperte 2 vezes enter para continuar. ";

&#x20;   cin.get();

&#x20;   cin.get();

&#x20;   system("clear");

&#x20;   

&#x20;   cout << "Digite o nome do aluno: ";

&#x20;   cin >> nome2;

&#x20;   cout << "Digite as 3 notas: ";

&#x20;   cin >> n1 >> n2 >> n3;

&#x20;   media2 = (n1 + n2 + n3) / 3;

&#x20;   cout<<"\\nAperte 2 vezes enter para continuar. ";

&#x20;   cin.get();

&#x20;   cin.get();

&#x20;   system("clear");

&#x20;   

&#x20;   cout << "Digite o nome do aluno: ";

&#x20;   cin >> nome3;

&#x20;   cout << "Digite as 3 notas: ";

&#x20;   cin >> n1 >> n2 >> n3;

&#x20;   media3 = (n1 + n2 + n3) / 3;

&#x20;   cout<<"\\nAperte 2 vezes enter para continuar. ";

&#x20;   cin.get();

&#x20;   cin.get();

&#x20;   system("clear");



&#x20;   cout << "Digite o nome do aluno: ";

&#x20;   cin >> nome4;

&#x20;   cout << "Digite as 3 notas: ";

&#x20;   cin >> n1 >> n2 >> n3;

&#x20;   media4 = (n1 + n2 + n3) / 3;

&#x20;   cout<<"\\nAperte enter para continuar. ";

&#x20;   cin.get();

&#x20;   cin.get();

&#x20;   system("clear");



&#x20;   cout << "Digite o nome do aluno: ";

&#x20;   cin >> nome5;

&#x20;   cout << "Digite as 3 notas: ";

&#x20;   cin >> n1 >> n2 >> n3;

&#x20;   media5 = (n1 + n2 + n3) / 3;

&#x20;   cout<<"\\nAperte 2 vezes enter para continuar. ";

&#x20;   cin.get();

&#x20;   cin.get();

&#x20;   system("clear");

&#x20;   

&#x20;   cout << "\\n===== TABELA FINAL =====\\n";



&#x20;   cout << "\\nAluno: " << nome1;

&#x20;   cout << "\\nMedia: " << media1;

&#x20;   cout << "\\nSituacao: " << (media1 >= 7 ? "Aprovado\\n" : "Reprovado\\n");



&#x20;   cout << "-----------------------\\n";



&#x20;   cout << "\\nAluno: " << nome2;

&#x20;   cout << "\\nMedia: " << media2;

&#x20;   cout << "\\nSituacao: " << (media2 >= 7 ? "Aprovado\\n" : "Reprovado\\n");



&#x20;   cout << "-----------------------\\n";



&#x20;   cout << "\\nAluno: " << nome3;

&#x20;   cout << "\\nMedia: " << media3;

&#x20;   cout << "\\nSituacao: " << (media3 >= 7 ? "Aprovado\\n" : "Reprovado\\n");



&#x20;   cout << "-----------------------\\n";



&#x20;   cout << "\\nAluno: " << nome4;

&#x20;   cout << "\\nMedia: " << media4;

&#x20;   cout << "\\nSituacao: " << (media4 >= 7 ? "Aprovado\\n" : "Reprovado\\n");



&#x20;   cout << "-----------------------\\n";



&#x20;   cout << "\\nAluno: " << nome5;

&#x20;   cout << "\\nMedia: " << media5;

&#x20;   cout << "\\nSituacao: " << (media5 >= 7 ? "Aprovado\\n" : "Reprovado\\n");



&#x20;   cout<<"\\nAperte 2 vezes enter para continuar. ";

&#x20;   cin.get();

&#x20;   cin.get();

&#x20;   system("clear");

&#x20;   

&#x20;   maiorMedia = media1;

&#x20;   melhorAluno = nome1;



&#x20;   if (media2 > maiorMedia) {

&#x20;       maiorMedia = media2;

&#x20;       melhorAluno = nome2;

&#x20;   }



&#x20;   if (media3 > maiorMedia) {

&#x20;       maiorMedia = media3;

&#x20;       melhorAluno = nome3;

&#x20;   }



&#x20;   if (media4 > maiorMedia) {

&#x20;       maiorMedia = media4;

&#x20;       melhorAluno = nome4;

&#x20;   }



&#x20;   if (media5 > maiorMedia) {

&#x20;       maiorMedia = media5;

&#x20;       melhorAluno = nome5;

&#x20;   }



&#x20;   cout << "\\n===== MELHOR ALUNO =====\\n";

&#x20;   cout << "Aluno: " << melhorAluno;

&#x20;   cout << "\\nMaior media: " << maiorMedia;



&#x20;   return 0;

}

