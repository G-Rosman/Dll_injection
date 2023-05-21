String with Library name: 01015018
Adress for patching code cave: 01007FA1 
                                        je 0x010080FB - >   jmp calc_patch0.10136B0
							    nop
Code in adress: 010136B0 ->
    								pushad 
								lea ecx,dword ptr ds:[1015018]
								call <kernel32.LoadLibraryW>
								popad 
								je calc_patch0.10080FB
								jmp calc_patch0.1007FA7



