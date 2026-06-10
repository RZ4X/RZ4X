<p align="center">
  <pre>
   ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄ 
  ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌
  ▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀█░▌
  ▐░▌       ▐░▌▐░▌       ▐░▌▐░▌       ▐░▌▐░▌       ▐░▌
  ▐░█▄▄▄▄▄▄▄█░▌▐░█▄▄▄▄▄▄▄█░▌▐░▌       ▐░▌▐░▌       ▐░▌
  ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░▌       ▐░▌▐░▌       ▐░▌
  ▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀█░▌▐░▌       ▐░▌▐░▌       ▐░▌
  ▐░▌       ▐░▌▐░▌       ▐░▌▐░▌       ▐░▌▐░▌       ▐░▌
  ▐░█▄▄▄▄▄▄▄█░▌▐░▌       ▐░▌▐░█▄▄▄▄▄▄▄█░▌▐░█▄▄▄▄▄▄▄█░▌
  ▐░░░░░░░░░░░▌▐░▌       ▐░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌
   ▀▀▀▀▀▀▀▀▀▀▀  ▀         ▀  ▀▀▀▀▀▀▀▀▀▀▀  ▀▀▀▀▀▀▀▀▀▀▀ 
  </pre>
  <h1 align="center">⚡ ZAID ALAA ⚡</h1>
  <p align="center">
    <i>System Architect • Memory Warlock • JVM Exorcist</i>
  </p>
</p>

<!-- Terrifying code snippet (low-level memory corruption in C) -->
<p align="center">
  <b>🔻 THE CODE THAT BURNS 🔻</b>
</p>

```c
#include <stdio.h>
#include <stdlib.h>

typedef struct {
    void (*summon)(void);
    char* soul;
} DarkPointer;

void unleash() {
    printf("\033[1;31m➤ SYSTEM BREACH. ZAID ALAA OWNS THE STACK.\033[0m\n");
}

int main() {
    DarkPointer shadow = { unleash, (char*)0xDEADBEEF };
    shadow.summon();
    
    // Pointer arithmetic that terrifies juniors
    int* fear = (int*)malloc(sizeof(int) * 666);
    for (int i = 0; i < 666; i++)
        fear[i] = i ^ 0xFF;
    
    free(fear);
    return 0; // Nothing is truly freed.
}
