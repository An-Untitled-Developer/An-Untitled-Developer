Welcome. I don't really code but I do stuff.

xor ecx,ecx

mov cx,0x2624

mov esi,dword [esi+ecx]

test esi,esi

je CodeEnd

xor eax,eax

mov cx,0x015D

dec ecx

mov dword [esi+ecx],eax
