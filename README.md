# Simple-KittyMemory-Exemple-
MemoryPatch("libil2cpp.so", 0x00000, "\x00\x00\x00\x00", 4).Modify();



MemoryPatch Exemple;

Exemple.Modify(); / Exemple.Retore();

Exemple = MemoryPatch("libil2cpp.so", 0x000000, "\x00\x00\x00\x00", 4);
