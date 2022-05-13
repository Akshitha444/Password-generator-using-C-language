#include <math.h>
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
void randomPasswordGeneration(int n)
{
	int a = 0;

	int randomizer = 0;
	srand((unsigned int)(time(NULL)));
	char numbers[] = "0123456789";
	char letter[] = "abcdefghijklmnoqprstuvwxyz";
	char LETTER[] = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
	char symbols[] = "!@#$^&*?";
	char password[n];
	randomizer = rand() % 4;
	for (a = 0; a < n; a++) {

		if (randomizer == 1) {
			password[a] = numbers[rand() % 10];
			randomizer = rand() % 4;
			printf("%c", password[a]);
		}
		else if (randomizer == 2) {
			password[a] = symbols[rand() % 8];
			randomizer = rand() % 4;
			printf("%c", password[a]);
		}
		else if (randomizer == 3) {
			password[a] = LETTER[rand() % 26];
			randomizer = rand() % 4;
			printf("%c", password[a]);
		}
		else {
			password[a] = letter[rand() % 26];
			randomizer = rand() % 4;
			printf("%c", password[a]);
		}
	}
}
int main()
{
	int n = 10;
	randomPasswordGeneration(n);
    return 0;
}
