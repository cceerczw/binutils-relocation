# binutils-relocation
Dear all,  Recently, I have been studying the relocation types in the program linking process for arm32 target.  I have tested some little programs to produce different relocation types to analyze. And I found some of the relocation types are difficult to produce, such as R_ARM_ABS16, R_ARM_ABS12, R_ARM_THM_ABS5 and R_ARM_ABS8.    I have tried many times and none of them can be produced. I also tried to analyze the source codes of binutils (version 2.26). But no clues can be found how these types are generated in the relocation method elf32_arm_final_link_relocate() in file elf32-arm.c. Or maybe I am just not familiar with the source code and ommit some points.   Does someone know what are these four relocation types for? How can I produce them? Any suggestion is welcomed.     By the way, in the document link below, there are relocation type descriptions for arm32 target.  All my relocation knowledge is come from this document.   http://infocenter.arm.com/help/topic/com.arm.doc.ihi0044f/IHI0044F_aaelf.pdf
