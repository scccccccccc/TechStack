使用visual studio编译带有asm文件的项目（往往用于生成shellcode等等）时，需要做的三件事：

1. Create a separate `.asm` file and write your assembly code there.
2. Right click your solution and navigate to **Build Dependencies**->**Build Customizations** and check the **masm** box.
3. Right click on your `.asm` file and go to **Properties**->**Item Type** and select **Microsoft Macro Assembler**.