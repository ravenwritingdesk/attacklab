
./rtarget:     file format elf64-x86-64


Disassembly of section .init:

0000000000000dc8 <_init>:
 dc8:	48 83 ec 08          	sub    $0x8,%rsp
 dcc:	48 8b 05 15 42 20 00 	mov    0x204215(%rip),%rax        # 204fe8 <__gmon_start__>
 dd3:	48 85 c0             	test   %rax,%rax
 dd6:	74 02                	je     dda <_init+0x12>
 dd8:	ff d0                	callq  *%rax
 dda:	48 83 c4 08          	add    $0x8,%rsp
 dde:	c3                   	retq   

Disassembly of section .plt:

0000000000000de0 <.plt>:
     de0:	ff 35 da 40 20 00    	pushq  0x2040da(%rip)        # 204ec0 <_GLOBAL_OFFSET_TABLE_+0x8>
     de6:	ff 25 dc 40 20 00    	jmpq   *0x2040dc(%rip)        # 204ec8 <_GLOBAL_OFFSET_TABLE_+0x10>
     dec:	0f 1f 40 00          	nopl   0x0(%rax)

0000000000000df0 <strcasecmp@plt>:
     df0:	ff 25 da 40 20 00    	jmpq   *0x2040da(%rip)        # 204ed0 <strcasecmp@GLIBC_2.2.5>
     df6:	68 00 00 00 00       	pushq  $0x0
     dfb:	e9 e0 ff ff ff       	jmpq   de0 <.plt>

0000000000000e00 <__errno_location@plt>:
     e00:	ff 25 d2 40 20 00    	jmpq   *0x2040d2(%rip)        # 204ed8 <__errno_location@GLIBC_2.2.5>
     e06:	68 01 00 00 00       	pushq  $0x1
     e0b:	e9 d0 ff ff ff       	jmpq   de0 <.plt>

0000000000000e10 <srandom@plt>:
     e10:	ff 25 ca 40 20 00    	jmpq   *0x2040ca(%rip)        # 204ee0 <srandom@GLIBC_2.2.5>
     e16:	68 02 00 00 00       	pushq  $0x2
     e1b:	e9 c0 ff ff ff       	jmpq   de0 <.plt>

0000000000000e20 <strncmp@plt>:
     e20:	ff 25 c2 40 20 00    	jmpq   *0x2040c2(%rip)        # 204ee8 <strncmp@GLIBC_2.2.5>
     e26:	68 03 00 00 00       	pushq  $0x3
     e2b:	e9 b0 ff ff ff       	jmpq   de0 <.plt>

0000000000000e30 <strcpy@plt>:
     e30:	ff 25 ba 40 20 00    	jmpq   *0x2040ba(%rip)        # 204ef0 <strcpy@GLIBC_2.2.5>
     e36:	68 04 00 00 00       	pushq  $0x4
     e3b:	e9 a0 ff ff ff       	jmpq   de0 <.plt>

0000000000000e40 <puts@plt>:
     e40:	ff 25 b2 40 20 00    	jmpq   *0x2040b2(%rip)        # 204ef8 <puts@GLIBC_2.2.5>
     e46:	68 05 00 00 00       	pushq  $0x5
     e4b:	e9 90 ff ff ff       	jmpq   de0 <.plt>

0000000000000e50 <write@plt>:
     e50:	ff 25 aa 40 20 00    	jmpq   *0x2040aa(%rip)        # 204f00 <write@GLIBC_2.2.5>
     e56:	68 06 00 00 00       	pushq  $0x6
     e5b:	e9 80 ff ff ff       	jmpq   de0 <.plt>

0000000000000e60 <__stack_chk_fail@plt>:
     e60:	ff 25 a2 40 20 00    	jmpq   *0x2040a2(%rip)        # 204f08 <__stack_chk_fail@GLIBC_2.4>
     e66:	68 07 00 00 00       	pushq  $0x7
     e6b:	e9 70 ff ff ff       	jmpq   de0 <.plt>

0000000000000e70 <mmap@plt>:
     e70:	ff 25 9a 40 20 00    	jmpq   *0x20409a(%rip)        # 204f10 <mmap@GLIBC_2.2.5>
     e76:	68 08 00 00 00       	pushq  $0x8
     e7b:	e9 60 ff ff ff       	jmpq   de0 <.plt>

0000000000000e80 <memset@plt>:
     e80:	ff 25 92 40 20 00    	jmpq   *0x204092(%rip)        # 204f18 <memset@GLIBC_2.2.5>
     e86:	68 09 00 00 00       	pushq  $0x9
     e8b:	e9 50 ff ff ff       	jmpq   de0 <.plt>

0000000000000e90 <alarm@plt>:
     e90:	ff 25 8a 40 20 00    	jmpq   *0x20408a(%rip)        # 204f20 <alarm@GLIBC_2.2.5>
     e96:	68 0a 00 00 00       	pushq  $0xa
     e9b:	e9 40 ff ff ff       	jmpq   de0 <.plt>

0000000000000ea0 <close@plt>:
     ea0:	ff 25 82 40 20 00    	jmpq   *0x204082(%rip)        # 204f28 <close@GLIBC_2.2.5>
     ea6:	68 0b 00 00 00       	pushq  $0xb
     eab:	e9 30 ff ff ff       	jmpq   de0 <.plt>

0000000000000eb0 <read@plt>:
     eb0:	ff 25 7a 40 20 00    	jmpq   *0x20407a(%rip)        # 204f30 <read@GLIBC_2.2.5>
     eb6:	68 0c 00 00 00       	pushq  $0xc
     ebb:	e9 20 ff ff ff       	jmpq   de0 <.plt>

0000000000000ec0 <signal@plt>:
     ec0:	ff 25 72 40 20 00    	jmpq   *0x204072(%rip)        # 204f38 <signal@GLIBC_2.2.5>
     ec6:	68 0d 00 00 00       	pushq  $0xd
     ecb:	e9 10 ff ff ff       	jmpq   de0 <.plt>

0000000000000ed0 <gethostbyname@plt>:
     ed0:	ff 25 6a 40 20 00    	jmpq   *0x20406a(%rip)        # 204f40 <gethostbyname@GLIBC_2.2.5>
     ed6:	68 0e 00 00 00       	pushq  $0xe
     edb:	e9 00 ff ff ff       	jmpq   de0 <.plt>

0000000000000ee0 <__memmove_chk@plt>:
     ee0:	ff 25 62 40 20 00    	jmpq   *0x204062(%rip)        # 204f48 <__memmove_chk@GLIBC_2.3.4>
     ee6:	68 0f 00 00 00       	pushq  $0xf
     eeb:	e9 f0 fe ff ff       	jmpq   de0 <.plt>

0000000000000ef0 <strtol@plt>:
     ef0:	ff 25 5a 40 20 00    	jmpq   *0x20405a(%rip)        # 204f50 <strtol@GLIBC_2.2.5>
     ef6:	68 10 00 00 00       	pushq  $0x10
     efb:	e9 e0 fe ff ff       	jmpq   de0 <.plt>

0000000000000f00 <memcpy@plt>:
     f00:	ff 25 52 40 20 00    	jmpq   *0x204052(%rip)        # 204f58 <memcpy@GLIBC_2.14>
     f06:	68 11 00 00 00       	pushq  $0x11
     f0b:	e9 d0 fe ff ff       	jmpq   de0 <.plt>

0000000000000f10 <time@plt>:
     f10:	ff 25 4a 40 20 00    	jmpq   *0x20404a(%rip)        # 204f60 <time@GLIBC_2.2.5>
     f16:	68 12 00 00 00       	pushq  $0x12
     f1b:	e9 c0 fe ff ff       	jmpq   de0 <.plt>

0000000000000f20 <random@plt>:
     f20:	ff 25 42 40 20 00    	jmpq   *0x204042(%rip)        # 204f68 <random@GLIBC_2.2.5>
     f26:	68 13 00 00 00       	pushq  $0x13
     f2b:	e9 b0 fe ff ff       	jmpq   de0 <.plt>

0000000000000f30 <_IO_getc@plt>:
     f30:	ff 25 3a 40 20 00    	jmpq   *0x20403a(%rip)        # 204f70 <_IO_getc@GLIBC_2.2.5>
     f36:	68 14 00 00 00       	pushq  $0x14
     f3b:	e9 a0 fe ff ff       	jmpq   de0 <.plt>

0000000000000f40 <__isoc99_sscanf@plt>:
     f40:	ff 25 32 40 20 00    	jmpq   *0x204032(%rip)        # 204f78 <__isoc99_sscanf@GLIBC_2.7>
     f46:	68 15 00 00 00       	pushq  $0x15
     f4b:	e9 90 fe ff ff       	jmpq   de0 <.plt>

0000000000000f50 <munmap@plt>:
     f50:	ff 25 2a 40 20 00    	jmpq   *0x20402a(%rip)        # 204f80 <munmap@GLIBC_2.2.5>
     f56:	68 16 00 00 00       	pushq  $0x16
     f5b:	e9 80 fe ff ff       	jmpq   de0 <.plt>

0000000000000f60 <__printf_chk@plt>:
     f60:	ff 25 22 40 20 00    	jmpq   *0x204022(%rip)        # 204f88 <__printf_chk@GLIBC_2.3.4>
     f66:	68 17 00 00 00       	pushq  $0x17
     f6b:	e9 70 fe ff ff       	jmpq   de0 <.plt>

0000000000000f70 <fopen@plt>:
     f70:	ff 25 1a 40 20 00    	jmpq   *0x20401a(%rip)        # 204f90 <fopen@GLIBC_2.2.5>
     f76:	68 18 00 00 00       	pushq  $0x18
     f7b:	e9 60 fe ff ff       	jmpq   de0 <.plt>

0000000000000f80 <getopt@plt>:
     f80:	ff 25 12 40 20 00    	jmpq   *0x204012(%rip)        # 204f98 <getopt@GLIBC_2.2.5>
     f86:	68 19 00 00 00       	pushq  $0x19
     f8b:	e9 50 fe ff ff       	jmpq   de0 <.plt>

0000000000000f90 <strtoul@plt>:
     f90:	ff 25 0a 40 20 00    	jmpq   *0x20400a(%rip)        # 204fa0 <strtoul@GLIBC_2.2.5>
     f96:	68 1a 00 00 00       	pushq  $0x1a
     f9b:	e9 40 fe ff ff       	jmpq   de0 <.plt>

0000000000000fa0 <gethostname@plt>:
     fa0:	ff 25 02 40 20 00    	jmpq   *0x204002(%rip)        # 204fa8 <gethostname@GLIBC_2.2.5>
     fa6:	68 1b 00 00 00       	pushq  $0x1b
     fab:	e9 30 fe ff ff       	jmpq   de0 <.plt>

0000000000000fb0 <exit@plt>:
     fb0:	ff 25 fa 3f 20 00    	jmpq   *0x203ffa(%rip)        # 204fb0 <exit@GLIBC_2.2.5>
     fb6:	68 1c 00 00 00       	pushq  $0x1c
     fbb:	e9 20 fe ff ff       	jmpq   de0 <.plt>

0000000000000fc0 <connect@plt>:
     fc0:	ff 25 f2 3f 20 00    	jmpq   *0x203ff2(%rip)        # 204fb8 <connect@GLIBC_2.2.5>
     fc6:	68 1d 00 00 00       	pushq  $0x1d
     fcb:	e9 10 fe ff ff       	jmpq   de0 <.plt>

0000000000000fd0 <__fprintf_chk@plt>:
     fd0:	ff 25 ea 3f 20 00    	jmpq   *0x203fea(%rip)        # 204fc0 <__fprintf_chk@GLIBC_2.3.4>
     fd6:	68 1e 00 00 00       	pushq  $0x1e
     fdb:	e9 00 fe ff ff       	jmpq   de0 <.plt>

0000000000000fe0 <__sprintf_chk@plt>:
     fe0:	ff 25 e2 3f 20 00    	jmpq   *0x203fe2(%rip)        # 204fc8 <__sprintf_chk@GLIBC_2.3.4>
     fe6:	68 1f 00 00 00       	pushq  $0x1f
     feb:	e9 f0 fd ff ff       	jmpq   de0 <.plt>

0000000000000ff0 <socket@plt>:
     ff0:	ff 25 da 3f 20 00    	jmpq   *0x203fda(%rip)        # 204fd0 <socket@GLIBC_2.2.5>
     ff6:	68 20 00 00 00       	pushq  $0x20
     ffb:	e9 e0 fd ff ff       	jmpq   de0 <.plt>

Disassembly of section .plt.got:

0000000000001000 <__cxa_finalize@plt>:
    1000:	ff 25 f2 3f 20 00    	jmpq   *0x203ff2(%rip)        # 204ff8 <__cxa_finalize@GLIBC_2.2.5>
    1006:	66 90                	xchg   %ax,%ax

Disassembly of section .text:

0000000000001010 <_start>:
    1010:	31 ed                	xor    %ebp,%ebp
    1012:	49 89 d1             	mov    %rdx,%r9
    1015:	5e                   	pop    %rsi
    1016:	48 89 e2             	mov    %rsp,%rdx
    1019:	48 83 e4 f0          	and    $0xfffffffffffffff0,%rsp
    101d:	50                   	push   %rax
    101e:	54                   	push   %rsp
    101f:	4c 8d 05 6a 22 00 00 	lea    0x226a(%rip),%r8        # 3290 <__libc_csu_fini>
    1026:	48 8d 0d f3 21 00 00 	lea    0x21f3(%rip),%rcx        # 3220 <__libc_csu_init>
    102d:	48 8d 3d 0d 03 00 00 	lea    0x30d(%rip),%rdi        # 1341 <main>
    1034:	ff 15 a6 3f 20 00    	callq  *0x203fa6(%rip)        # 204fe0 <__libc_start_main@GLIBC_2.2.5>
    103a:	f4                   	hlt    
    103b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001040 <deregister_tm_clones>:
    1040:	48 8d 3d 29 43 20 00 	lea    0x204329(%rip),%rdi        # 205370 <__TMC_END__>
    1047:	55                   	push   %rbp
    1048:	48 8d 05 21 43 20 00 	lea    0x204321(%rip),%rax        # 205370 <__TMC_END__>
    104f:	48 39 f8             	cmp    %rdi,%rax
    1052:	48 89 e5             	mov    %rsp,%rbp
    1055:	74 19                	je     1070 <deregister_tm_clones+0x30>
    1057:	48 8b 05 7a 3f 20 00 	mov    0x203f7a(%rip),%rax        # 204fd8 <_ITM_deregisterTMCloneTable>
    105e:	48 85 c0             	test   %rax,%rax
    1061:	74 0d                	je     1070 <deregister_tm_clones+0x30>
    1063:	5d                   	pop    %rbp
    1064:	ff e0                	jmpq   *%rax
    1066:	66 2e 0f 1f 84 00 00 	nopw   %cs:0x0(%rax,%rax,1)
    106d:	00 00 00 
    1070:	5d                   	pop    %rbp
    1071:	c3                   	retq   
    1072:	0f 1f 40 00          	nopl   0x0(%rax)
    1076:	66 2e 0f 1f 84 00 00 	nopw   %cs:0x0(%rax,%rax,1)
    107d:	00 00 00 

0000000000001080 <register_tm_clones>:
    1080:	48 8d 3d e9 42 20 00 	lea    0x2042e9(%rip),%rdi        # 205370 <__TMC_END__>
    1087:	48 8d 35 e2 42 20 00 	lea    0x2042e2(%rip),%rsi        # 205370 <__TMC_END__>
    108e:	55                   	push   %rbp
    108f:	48 29 fe             	sub    %rdi,%rsi
    1092:	48 89 e5             	mov    %rsp,%rbp
    1095:	48 c1 fe 03          	sar    $0x3,%rsi
    1099:	48 89 f0             	mov    %rsi,%rax
    109c:	48 c1 e8 3f          	shr    $0x3f,%rax
    10a0:	48 01 c6             	add    %rax,%rsi
    10a3:	48 d1 fe             	sar    %rsi
    10a6:	74 18                	je     10c0 <register_tm_clones+0x40>
    10a8:	48 8b 05 41 3f 20 00 	mov    0x203f41(%rip),%rax        # 204ff0 <_ITM_registerTMCloneTable>
    10af:	48 85 c0             	test   %rax,%rax
    10b2:	74 0c                	je     10c0 <register_tm_clones+0x40>
    10b4:	5d                   	pop    %rbp
    10b5:	ff e0                	jmpq   *%rax
    10b7:	66 0f 1f 84 00 00 00 	nopw   0x0(%rax,%rax,1)
    10be:	00 00 
    10c0:	5d                   	pop    %rbp
    10c1:	c3                   	retq   
    10c2:	0f 1f 40 00          	nopl   0x0(%rax)
    10c6:	66 2e 0f 1f 84 00 00 	nopw   %cs:0x0(%rax,%rax,1)
    10cd:	00 00 00 

00000000000010d0 <__do_global_dtors_aux>:
    10d0:	80 3d d1 42 20 00 00 	cmpb   $0x0,0x2042d1(%rip)        # 2053a8 <completed.7697>
    10d7:	75 2f                	jne    1108 <__do_global_dtors_aux+0x38>
    10d9:	48 83 3d 17 3f 20 00 	cmpq   $0x0,0x203f17(%rip)        # 204ff8 <__cxa_finalize@GLIBC_2.2.5>
    10e0:	00 
    10e1:	55                   	push   %rbp
    10e2:	48 89 e5             	mov    %rsp,%rbp
    10e5:	74 0c                	je     10f3 <__do_global_dtors_aux+0x23>
    10e7:	48 8b 3d 1a 3f 20 00 	mov    0x203f1a(%rip),%rdi        # 205008 <__dso_handle>
    10ee:	e8 0d ff ff ff       	callq  1000 <__cxa_finalize@plt>
    10f3:	e8 48 ff ff ff       	callq  1040 <deregister_tm_clones>
    10f8:	c6 05 a9 42 20 00 01 	movb   $0x1,0x2042a9(%rip)        # 2053a8 <completed.7697>
    10ff:	5d                   	pop    %rbp
    1100:	c3                   	retq   
    1101:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    1108:	f3 c3                	repz retq 
    110a:	66 0f 1f 44 00 00    	nopw   0x0(%rax,%rax,1)

0000000000001110 <frame_dummy>:
    1110:	55                   	push   %rbp
    1111:	48 89 e5             	mov    %rsp,%rbp
    1114:	5d                   	pop    %rbp
    1115:	e9 66 ff ff ff       	jmpq   1080 <register_tm_clones>

000000000000111a <usage>:
    111a:	48 83 ec 08          	sub    $0x8,%rsp
    111e:	48 89 fa             	mov    %rdi,%rdx
    1121:	83 3d c0 42 20 00 00 	cmpl   $0x0,0x2042c0(%rip)        # 2053e8 <is_checker>
    1128:	74 50                	je     117a <usage+0x60>
    112a:	48 8d 35 77 21 00 00 	lea    0x2177(%rip),%rsi        # 32a8 <_IO_stdin_used+0x8>
    1131:	bf 01 00 00 00       	mov    $0x1,%edi
    1136:	b8 00 00 00 00       	mov    $0x0,%eax
    113b:	e8 20 fe ff ff       	callq  f60 <__printf_chk@plt>
    1140:	48 8d 3d 99 21 00 00 	lea    0x2199(%rip),%rdi        # 32e0 <_IO_stdin_used+0x40>
    1147:	e8 f4 fc ff ff       	callq  e40 <puts@plt>
    114c:	48 8d 3d 05 23 00 00 	lea    0x2305(%rip),%rdi        # 3458 <_IO_stdin_used+0x1b8>
    1153:	e8 e8 fc ff ff       	callq  e40 <puts@plt>
    1158:	48 8d 3d a9 21 00 00 	lea    0x21a9(%rip),%rdi        # 3308 <_IO_stdin_used+0x68>
    115f:	e8 dc fc ff ff       	callq  e40 <puts@plt>
    1164:	48 8d 3d 07 23 00 00 	lea    0x2307(%rip),%rdi        # 3472 <_IO_stdin_used+0x1d2>
    116b:	e8 d0 fc ff ff       	callq  e40 <puts@plt>
    1170:	bf 00 00 00 00       	mov    $0x0,%edi
    1175:	e8 36 fe ff ff       	callq  fb0 <exit@plt>
    117a:	48 8d 35 0d 23 00 00 	lea    0x230d(%rip),%rsi        # 348e <_IO_stdin_used+0x1ee>
    1181:	bf 01 00 00 00       	mov    $0x1,%edi
    1186:	b8 00 00 00 00       	mov    $0x0,%eax
    118b:	e8 d0 fd ff ff       	callq  f60 <__printf_chk@plt>
    1190:	48 8d 3d 99 21 00 00 	lea    0x2199(%rip),%rdi        # 3330 <_IO_stdin_used+0x90>
    1197:	e8 a4 fc ff ff       	callq  e40 <puts@plt>
    119c:	48 8d 3d b5 21 00 00 	lea    0x21b5(%rip),%rdi        # 3358 <_IO_stdin_used+0xb8>
    11a3:	e8 98 fc ff ff       	callq  e40 <puts@plt>
    11a8:	48 8d 3d fd 22 00 00 	lea    0x22fd(%rip),%rdi        # 34ac <_IO_stdin_used+0x20c>
    11af:	e8 8c fc ff ff       	callq  e40 <puts@plt>
    11b4:	eb ba                	jmp    1170 <usage+0x56>

00000000000011b6 <initialize_target>:
    11b6:	55                   	push   %rbp
    11b7:	53                   	push   %rbx
    11b8:	48 81 ec 18 21 00 00 	sub    $0x2118,%rsp
    11bf:	89 f5                	mov    %esi,%ebp
    11c1:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    11c8:	00 00 
    11ca:	48 89 84 24 08 21 00 	mov    %rax,0x2108(%rsp)
    11d1:	00 
    11d2:	31 c0                	xor    %eax,%eax
    11d4:	89 3d fe 41 20 00    	mov    %edi,0x2041fe(%rip)        # 2053d8 <check_level>
    11da:	8b 3d 30 3e 20 00    	mov    0x203e30(%rip),%edi        # 205010 <target_id>
    11e0:	e8 16 20 00 00       	callq  31fb <gencookie>
    11e5:	89 05 f9 41 20 00    	mov    %eax,0x2041f9(%rip)        # 2053e4 <cookie>
    11eb:	89 c7                	mov    %eax,%edi
    11ed:	e8 09 20 00 00       	callq  31fb <gencookie>
    11f2:	89 05 e8 41 20 00    	mov    %eax,0x2041e8(%rip)        # 2053e0 <authkey>
    11f8:	8b 05 12 3e 20 00    	mov    0x203e12(%rip),%eax        # 205010 <target_id>
    11fe:	8d 78 01             	lea    0x1(%rax),%edi
    1201:	e8 0a fc ff ff       	callq  e10 <srandom@plt>
    1206:	e8 15 fd ff ff       	callq  f20 <random@plt>
    120b:	89 c7                	mov    %eax,%edi
    120d:	e8 1a 03 00 00       	callq  152c <scramble>
    1212:	89 c3                	mov    %eax,%ebx
    1214:	85 ed                	test   %ebp,%ebp
    1216:	75 54                	jne    126c <initialize_target+0xb6>
    1218:	b8 00 00 00 00       	mov    $0x0,%eax
    121d:	01 d8                	add    %ebx,%eax
    121f:	0f b7 c0             	movzwl %ax,%eax
    1222:	8d 04 c5 00 01 00 00 	lea    0x100(,%rax,8),%eax
    1229:	89 c0                	mov    %eax,%eax
    122b:	48 89 05 2e 41 20 00 	mov    %rax,0x20412e(%rip)        # 205360 <buf_offset>
    1232:	c6 05 cf 4d 20 00 72 	movb   $0x72,0x204dcf(%rip)        # 206008 <target_prefix>
    1239:	83 3d 28 41 20 00 00 	cmpl   $0x0,0x204128(%rip)        # 205368 <notify>
    1240:	74 09                	je     124b <initialize_target+0x95>
    1242:	83 3d 9f 41 20 00 00 	cmpl   $0x0,0x20419f(%rip)        # 2053e8 <is_checker>
    1249:	74 39                	je     1284 <initialize_target+0xce>
    124b:	48 8b 84 24 08 21 00 	mov    0x2108(%rsp),%rax
    1252:	00 
    1253:	64 48 33 04 25 28 00 	xor    %fs:0x28,%rax
    125a:	00 00 
    125c:	0f 85 da 00 00 00    	jne    133c <initialize_target+0x186>
    1262:	48 81 c4 18 21 00 00 	add    $0x2118,%rsp
    1269:	5b                   	pop    %rbx
    126a:	5d                   	pop    %rbp
    126b:	c3                   	retq   
    126c:	bf 00 00 00 00       	mov    $0x0,%edi
    1271:	e8 9a fc ff ff       	callq  f10 <time@plt>
    1276:	89 c7                	mov    %eax,%edi
    1278:	e8 93 fb ff ff       	callq  e10 <srandom@plt>
    127d:	e8 9e fc ff ff       	callq  f20 <random@plt>
    1282:	eb 99                	jmp    121d <initialize_target+0x67>
    1284:	48 89 e7             	mov    %rsp,%rdi
    1287:	be 00 01 00 00       	mov    $0x100,%esi
    128c:	e8 0f fd ff ff       	callq  fa0 <gethostname@plt>
    1291:	89 c5                	mov    %eax,%ebp
    1293:	85 c0                	test   %eax,%eax
    1295:	75 26                	jne    12bd <initialize_target+0x107>
    1297:	89 c3                	mov    %eax,%ebx
    1299:	48 63 c3             	movslq %ebx,%rax
    129c:	48 8d 15 9d 3d 20 00 	lea    0x203d9d(%rip),%rdx        # 205040 <host_table>
    12a3:	48 8b 3c c2          	mov    (%rdx,%rax,8),%rdi
    12a7:	48 85 ff             	test   %rdi,%rdi
    12aa:	74 2c                	je     12d8 <initialize_target+0x122>
    12ac:	48 89 e6             	mov    %rsp,%rsi
    12af:	e8 3c fb ff ff       	callq  df0 <strcasecmp@plt>
    12b4:	85 c0                	test   %eax,%eax
    12b6:	74 1b                	je     12d3 <initialize_target+0x11d>
    12b8:	83 c3 01             	add    $0x1,%ebx
    12bb:	eb dc                	jmp    1299 <initialize_target+0xe3>
    12bd:	48 8d 3d c4 20 00 00 	lea    0x20c4(%rip),%rdi        # 3388 <_IO_stdin_used+0xe8>
    12c4:	e8 77 fb ff ff       	callq  e40 <puts@plt>
    12c9:	bf 08 00 00 00       	mov    $0x8,%edi
    12ce:	e8 dd fc ff ff       	callq  fb0 <exit@plt>
    12d3:	bd 01 00 00 00       	mov    $0x1,%ebp
    12d8:	85 ed                	test   %ebp,%ebp
    12da:	74 3d                	je     1319 <initialize_target+0x163>
    12dc:	48 8d bc 24 00 01 00 	lea    0x100(%rsp),%rdi
    12e3:	00 
    12e4:	e8 42 1c 00 00       	callq  2f2b <init_driver>
    12e9:	85 c0                	test   %eax,%eax
    12eb:	0f 89 5a ff ff ff    	jns    124b <initialize_target+0x95>
    12f1:	48 8d 94 24 00 01 00 	lea    0x100(%rsp),%rdx
    12f8:	00 
    12f9:	48 8d 35 00 21 00 00 	lea    0x2100(%rip),%rsi        # 3400 <_IO_stdin_used+0x160>
    1300:	bf 01 00 00 00       	mov    $0x1,%edi
    1305:	b8 00 00 00 00       	mov    $0x0,%eax
    130a:	e8 51 fc ff ff       	callq  f60 <__printf_chk@plt>
    130f:	bf 08 00 00 00       	mov    $0x8,%edi
    1314:	e8 97 fc ff ff       	callq  fb0 <exit@plt>
    1319:	48 89 e2             	mov    %rsp,%rdx
    131c:	48 8d 35 9d 20 00 00 	lea    0x209d(%rip),%rsi        # 33c0 <_IO_stdin_used+0x120>
    1323:	bf 01 00 00 00       	mov    $0x1,%edi
    1328:	b8 00 00 00 00       	mov    $0x0,%eax
    132d:	e8 2e fc ff ff       	callq  f60 <__printf_chk@plt>
    1332:	bf 08 00 00 00       	mov    $0x8,%edi
    1337:	e8 74 fc ff ff       	callq  fb0 <exit@plt>
    133c:	e8 1f fb ff ff       	callq  e60 <__stack_chk_fail@plt>

0000000000001341 <main>:
    1341:	41 56                	push   %r14
    1343:	41 55                	push   %r13
    1345:	41 54                	push   %r12
    1347:	55                   	push   %rbp
    1348:	53                   	push   %rbx
    1349:	41 89 fc             	mov    %edi,%r12d
    134c:	48 89 f3             	mov    %rsi,%rbx
    134f:	48 8d 35 dc 0e 00 00 	lea    0xedc(%rip),%rsi        # 2232 <seghandler>
    1356:	bf 0b 00 00 00       	mov    $0xb,%edi
    135b:	e8 60 fb ff ff       	callq  ec0 <signal@plt>
    1360:	48 8d 35 77 0e 00 00 	lea    0xe77(%rip),%rsi        # 21de <bushandler>
    1367:	bf 07 00 00 00       	mov    $0x7,%edi
    136c:	e8 4f fb ff ff       	callq  ec0 <signal@plt>
    1371:	48 8d 35 0e 0f 00 00 	lea    0xf0e(%rip),%rsi        # 2286 <illegalhandler>
    1378:	bf 04 00 00 00       	mov    $0x4,%edi
    137d:	e8 3e fb ff ff       	callq  ec0 <signal@plt>
    1382:	83 3d 5f 40 20 00 00 	cmpl   $0x0,0x20405f(%rip)        # 2053e8 <is_checker>
    1389:	75 26                	jne    13b1 <main+0x70>
    138b:	48 8d 2d 33 21 00 00 	lea    0x2133(%rip),%rbp        # 34c5 <_IO_stdin_used+0x225>
    1392:	48 8b 05 e7 3f 20 00 	mov    0x203fe7(%rip),%rax        # 205380 <stdin@@GLIBC_2.2.5>
    1399:	48 89 05 30 40 20 00 	mov    %rax,0x204030(%rip)        # 2053d0 <infile>
    13a0:	41 bd 00 00 00 00    	mov    $0x0,%r13d
    13a6:	41 be 00 00 00 00    	mov    $0x0,%r14d
    13ac:	e9 8d 00 00 00       	jmpq   143e <main+0xfd>
    13b1:	48 8d 35 22 0f 00 00 	lea    0xf22(%rip),%rsi        # 22da <sigalrmhandler>
    13b8:	bf 0e 00 00 00       	mov    $0xe,%edi
    13bd:	e8 fe fa ff ff       	callq  ec0 <signal@plt>
    13c2:	bf 05 00 00 00       	mov    $0x5,%edi
    13c7:	e8 c4 fa ff ff       	callq  e90 <alarm@plt>
    13cc:	48 8d 2d f7 20 00 00 	lea    0x20f7(%rip),%rbp        # 34ca <_IO_stdin_used+0x22a>
    13d3:	eb bd                	jmp    1392 <main+0x51>
    13d5:	48 8b 3b             	mov    (%rbx),%rdi
    13d8:	e8 3d fd ff ff       	callq  111a <usage>
    13dd:	48 8d 35 49 23 00 00 	lea    0x2349(%rip),%rsi        # 372d <_IO_stdin_used+0x48d>
    13e4:	48 8b 3d 9d 3f 20 00 	mov    0x203f9d(%rip),%rdi        # 205388 <optarg@@GLIBC_2.2.5>
    13eb:	e8 80 fb ff ff       	callq  f70 <fopen@plt>
    13f0:	48 89 05 d9 3f 20 00 	mov    %rax,0x203fd9(%rip)        # 2053d0 <infile>
    13f7:	48 85 c0             	test   %rax,%rax
    13fa:	75 42                	jne    143e <main+0xfd>
    13fc:	48 8b 0d 85 3f 20 00 	mov    0x203f85(%rip),%rcx        # 205388 <optarg@@GLIBC_2.2.5>
    1403:	48 8d 15 c8 20 00 00 	lea    0x20c8(%rip),%rdx        # 34d2 <_IO_stdin_used+0x232>
    140a:	be 01 00 00 00       	mov    $0x1,%esi
    140f:	48 8b 3d 8a 3f 20 00 	mov    0x203f8a(%rip),%rdi        # 2053a0 <stderr@@GLIBC_2.2.5>
    1416:	e8 b5 fb ff ff       	callq  fd0 <__fprintf_chk@plt>
    141b:	b8 01 00 00 00       	mov    $0x1,%eax
    1420:	e9 d9 00 00 00       	jmpq   14fe <main+0x1bd>
    1425:	ba 10 00 00 00       	mov    $0x10,%edx
    142a:	be 00 00 00 00       	mov    $0x0,%esi
    142f:	48 8b 3d 52 3f 20 00 	mov    0x203f52(%rip),%rdi        # 205388 <optarg@@GLIBC_2.2.5>
    1436:	e8 55 fb ff ff       	callq  f90 <strtoul@plt>
    143b:	41 89 c6             	mov    %eax,%r14d
    143e:	48 89 ea             	mov    %rbp,%rdx
    1441:	48 89 de             	mov    %rbx,%rsi
    1444:	44 89 e7             	mov    %r12d,%edi
    1447:	e8 34 fb ff ff       	callq  f80 <getopt@plt>
    144c:	3c ff                	cmp    $0xff,%al
    144e:	74 62                	je     14b2 <main+0x171>
    1450:	0f be d0             	movsbl %al,%edx
    1453:	83 e8 61             	sub    $0x61,%eax
    1456:	3c 10                	cmp    $0x10,%al
    1458:	77 3a                	ja     1494 <main+0x153>
    145a:	0f b6 c0             	movzbl %al,%eax
    145d:	48 8d 0d ac 20 00 00 	lea    0x20ac(%rip),%rcx        # 3510 <_IO_stdin_used+0x270>
    1464:	48 63 04 81          	movslq (%rcx,%rax,4),%rax
    1468:	48 01 c8             	add    %rcx,%rax
    146b:	ff e0                	jmpq   *%rax
    146d:	ba 0a 00 00 00       	mov    $0xa,%edx
    1472:	be 00 00 00 00       	mov    $0x0,%esi
    1477:	48 8b 3d 0a 3f 20 00 	mov    0x203f0a(%rip),%rdi        # 205388 <optarg@@GLIBC_2.2.5>
    147e:	e8 6d fa ff ff       	callq  ef0 <strtol@plt>
    1483:	41 89 c5             	mov    %eax,%r13d
    1486:	eb b6                	jmp    143e <main+0xfd>
    1488:	c7 05 d6 3e 20 00 00 	movl   $0x0,0x203ed6(%rip)        # 205368 <notify>
    148f:	00 00 00 
    1492:	eb aa                	jmp    143e <main+0xfd>
    1494:	48 8d 35 54 20 00 00 	lea    0x2054(%rip),%rsi        # 34ef <_IO_stdin_used+0x24f>
    149b:	bf 01 00 00 00       	mov    $0x1,%edi
    14a0:	b8 00 00 00 00       	mov    $0x0,%eax
    14a5:	e8 b6 fa ff ff       	callq  f60 <__printf_chk@plt>
    14aa:	48 8b 3b             	mov    (%rbx),%rdi
    14ad:	e8 68 fc ff ff       	callq  111a <usage>
    14b2:	be 01 00 00 00       	mov    $0x1,%esi
    14b7:	44 89 ef             	mov    %r13d,%edi
    14ba:	e8 f7 fc ff ff       	callq  11b6 <initialize_target>
    14bf:	83 3d 22 3f 20 00 00 	cmpl   $0x0,0x203f22(%rip)        # 2053e8 <is_checker>
    14c6:	74 09                	je     14d1 <main+0x190>
    14c8:	44 39 35 11 3f 20 00 	cmp    %r14d,0x203f11(%rip)        # 2053e0 <authkey>
    14cf:	75 36                	jne    1507 <main+0x1c6>
    14d1:	8b 15 0d 3f 20 00    	mov    0x203f0d(%rip),%edx        # 2053e4 <cookie>
    14d7:	48 8d 35 24 20 00 00 	lea    0x2024(%rip),%rsi        # 3502 <_IO_stdin_used+0x262>
    14de:	bf 01 00 00 00       	mov    $0x1,%edi
    14e3:	b8 00 00 00 00       	mov    $0x0,%eax
    14e8:	e8 73 fa ff ff       	callq  f60 <__printf_chk@plt>
    14ed:	48 8b 3d 6c 3e 20 00 	mov    0x203e6c(%rip),%rdi        # 205360 <buf_offset>
    14f4:	e8 38 0e 00 00       	callq  2331 <launch>
    14f9:	b8 00 00 00 00       	mov    $0x0,%eax
    14fe:	5b                   	pop    %rbx
    14ff:	5d                   	pop    %rbp
    1500:	41 5c                	pop    %r12
    1502:	41 5d                	pop    %r13
    1504:	41 5e                	pop    %r14
    1506:	c3                   	retq   
    1507:	44 89 f2             	mov    %r14d,%edx
    150a:	48 8d 35 17 1f 00 00 	lea    0x1f17(%rip),%rsi        # 3428 <_IO_stdin_used+0x188>
    1511:	bf 01 00 00 00       	mov    $0x1,%edi
    1516:	b8 00 00 00 00       	mov    $0x0,%eax
    151b:	e8 40 fa ff ff       	callq  f60 <__printf_chk@plt>
    1520:	b8 00 00 00 00       	mov    $0x0,%eax
    1525:	e8 14 09 00 00       	callq  1e3e <check_fail>
    152a:	eb a5                	jmp    14d1 <main+0x190>

000000000000152c <scramble>:
    152c:	48 83 ec 38          	sub    $0x38,%rsp
    1530:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1537:	00 00 
    1539:	48 89 44 24 28       	mov    %rax,0x28(%rsp)
    153e:	31 c0                	xor    %eax,%eax
    1540:	eb 10                	jmp    1552 <scramble+0x26>
    1542:	69 d0 64 2d 00 00    	imul   $0x2d64,%eax,%edx
    1548:	01 fa                	add    %edi,%edx
    154a:	89 c1                	mov    %eax,%ecx
    154c:	89 14 8c             	mov    %edx,(%rsp,%rcx,4)
    154f:	83 c0 01             	add    $0x1,%eax
    1552:	83 f8 09             	cmp    $0x9,%eax
    1555:	76 eb                	jbe    1542 <scramble+0x16>
    1557:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    155b:	69 c0 7a dd 00 00    	imul   $0xdd7a,%eax,%eax
    1561:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    1565:	8b 44 24 04          	mov    0x4(%rsp),%eax
    1569:	6b c0 74             	imul   $0x74,%eax,%eax
    156c:	89 44 24 04          	mov    %eax,0x4(%rsp)
    1570:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    1574:	69 c0 e0 18 00 00    	imul   $0x18e0,%eax,%eax
    157a:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    157e:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    1582:	69 c0 e3 a8 00 00    	imul   $0xa8e3,%eax,%eax
    1588:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    158c:	8b 44 24 10          	mov    0x10(%rsp),%eax
    1590:	69 c0 d7 aa 00 00    	imul   $0xaad7,%eax,%eax
    1596:	89 44 24 10          	mov    %eax,0x10(%rsp)
    159a:	8b 44 24 04          	mov    0x4(%rsp),%eax
    159e:	69 c0 7c 63 00 00    	imul   $0x637c,%eax,%eax
    15a4:	89 44 24 04          	mov    %eax,0x4(%rsp)
    15a8:	8b 44 24 04          	mov    0x4(%rsp),%eax
    15ac:	69 c0 1a f8 00 00    	imul   $0xf81a,%eax,%eax
    15b2:	89 44 24 04          	mov    %eax,0x4(%rsp)
    15b6:	8b 44 24 10          	mov    0x10(%rsp),%eax
    15ba:	69 c0 05 35 00 00    	imul   $0x3505,%eax,%eax
    15c0:	89 44 24 10          	mov    %eax,0x10(%rsp)
    15c4:	8b 44 24 20          	mov    0x20(%rsp),%eax
    15c8:	69 c0 ef 2e 00 00    	imul   $0x2eef,%eax,%eax
    15ce:	89 44 24 20          	mov    %eax,0x20(%rsp)
    15d2:	8b 44 24 04          	mov    0x4(%rsp),%eax
    15d6:	69 c0 07 ef 00 00    	imul   $0xef07,%eax,%eax
    15dc:	89 44 24 04          	mov    %eax,0x4(%rsp)
    15e0:	8b 44 24 10          	mov    0x10(%rsp),%eax
    15e4:	69 c0 4d 39 00 00    	imul   $0x394d,%eax,%eax
    15ea:	89 44 24 10          	mov    %eax,0x10(%rsp)
    15ee:	8b 04 24             	mov    (%rsp),%eax
    15f1:	69 c0 4d ad 00 00    	imul   $0xad4d,%eax,%eax
    15f7:	89 04 24             	mov    %eax,(%rsp)
    15fa:	8b 44 24 18          	mov    0x18(%rsp),%eax
    15fe:	69 c0 9b 19 00 00    	imul   $0x199b,%eax,%eax
    1604:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1608:	8b 44 24 08          	mov    0x8(%rsp),%eax
    160c:	69 c0 b2 b1 00 00    	imul   $0xb1b2,%eax,%eax
    1612:	89 44 24 08          	mov    %eax,0x8(%rsp)
    1616:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    161a:	69 c0 92 cd 00 00    	imul   $0xcd92,%eax,%eax
    1620:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    1624:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1628:	69 c0 3f e5 00 00    	imul   $0xe53f,%eax,%eax
    162e:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1632:	8b 44 24 04          	mov    0x4(%rsp),%eax
    1636:	69 c0 bb dd 00 00    	imul   $0xddbb,%eax,%eax
    163c:	89 44 24 04          	mov    %eax,0x4(%rsp)
    1640:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    1644:	69 c0 fd 87 00 00    	imul   $0x87fd,%eax,%eax
    164a:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    164e:	8b 04 24             	mov    (%rsp),%eax
    1651:	69 c0 6e cd 00 00    	imul   $0xcd6e,%eax,%eax
    1657:	89 04 24             	mov    %eax,(%rsp)
    165a:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    165e:	69 c0 1e f6 00 00    	imul   $0xf61e,%eax,%eax
    1664:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    1668:	8b 04 24             	mov    (%rsp),%eax
    166b:	69 c0 08 d2 00 00    	imul   $0xd208,%eax,%eax
    1671:	89 04 24             	mov    %eax,(%rsp)
    1674:	8b 44 24 20          	mov    0x20(%rsp),%eax
    1678:	69 c0 17 5e 00 00    	imul   $0x5e17,%eax,%eax
    167e:	89 44 24 20          	mov    %eax,0x20(%rsp)
    1682:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1686:	69 c0 d7 e4 00 00    	imul   $0xe4d7,%eax,%eax
    168c:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1690:	8b 44 24 14          	mov    0x14(%rsp),%eax
    1694:	69 c0 80 15 00 00    	imul   $0x1580,%eax,%eax
    169a:	89 44 24 14          	mov    %eax,0x14(%rsp)
    169e:	8b 44 24 08          	mov    0x8(%rsp),%eax
    16a2:	69 c0 fc ef 00 00    	imul   $0xeffc,%eax,%eax
    16a8:	89 44 24 08          	mov    %eax,0x8(%rsp)
    16ac:	8b 44 24 14          	mov    0x14(%rsp),%eax
    16b0:	69 c0 44 6f 00 00    	imul   $0x6f44,%eax,%eax
    16b6:	89 44 24 14          	mov    %eax,0x14(%rsp)
    16ba:	8b 44 24 14          	mov    0x14(%rsp),%eax
    16be:	69 c0 2e 03 00 00    	imul   $0x32e,%eax,%eax
    16c4:	89 44 24 14          	mov    %eax,0x14(%rsp)
    16c8:	8b 04 24             	mov    (%rsp),%eax
    16cb:	69 c0 98 36 00 00    	imul   $0x3698,%eax,%eax
    16d1:	89 04 24             	mov    %eax,(%rsp)
    16d4:	8b 44 24 10          	mov    0x10(%rsp),%eax
    16d8:	69 c0 37 ff 00 00    	imul   $0xff37,%eax,%eax
    16de:	89 44 24 10          	mov    %eax,0x10(%rsp)
    16e2:	8b 44 24 14          	mov    0x14(%rsp),%eax
    16e6:	69 c0 a4 d4 00 00    	imul   $0xd4a4,%eax,%eax
    16ec:	89 44 24 14          	mov    %eax,0x14(%rsp)
    16f0:	8b 44 24 24          	mov    0x24(%rsp),%eax
    16f4:	69 c0 d3 24 00 00    	imul   $0x24d3,%eax,%eax
    16fa:	89 44 24 24          	mov    %eax,0x24(%rsp)
    16fe:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1702:	69 c0 d5 77 00 00    	imul   $0x77d5,%eax,%eax
    1708:	89 44 24 18          	mov    %eax,0x18(%rsp)
    170c:	8b 44 24 20          	mov    0x20(%rsp),%eax
    1710:	69 c0 97 9f 00 00    	imul   $0x9f97,%eax,%eax
    1716:	89 44 24 20          	mov    %eax,0x20(%rsp)
    171a:	8b 44 24 04          	mov    0x4(%rsp),%eax
    171e:	69 c0 29 f9 00 00    	imul   $0xf929,%eax,%eax
    1724:	89 44 24 04          	mov    %eax,0x4(%rsp)
    1728:	8b 44 24 08          	mov    0x8(%rsp),%eax
    172c:	69 c0 b2 30 00 00    	imul   $0x30b2,%eax,%eax
    1732:	89 44 24 08          	mov    %eax,0x8(%rsp)
    1736:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    173a:	69 c0 4b e5 00 00    	imul   $0xe54b,%eax,%eax
    1740:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    1744:	8b 44 24 08          	mov    0x8(%rsp),%eax
    1748:	69 c0 e2 48 00 00    	imul   $0x48e2,%eax,%eax
    174e:	89 44 24 08          	mov    %eax,0x8(%rsp)
    1752:	8b 44 24 20          	mov    0x20(%rsp),%eax
    1756:	69 c0 dd cc 00 00    	imul   $0xccdd,%eax,%eax
    175c:	89 44 24 20          	mov    %eax,0x20(%rsp)
    1760:	8b 04 24             	mov    (%rsp),%eax
    1763:	69 c0 7e d6 00 00    	imul   $0xd67e,%eax,%eax
    1769:	89 04 24             	mov    %eax,(%rsp)
    176c:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1770:	69 c0 81 41 00 00    	imul   $0x4181,%eax,%eax
    1776:	89 44 24 18          	mov    %eax,0x18(%rsp)
    177a:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    177e:	69 c0 e6 e6 00 00    	imul   $0xe6e6,%eax,%eax
    1784:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    1788:	8b 04 24             	mov    (%rsp),%eax
    178b:	69 c0 c3 ef 00 00    	imul   $0xefc3,%eax,%eax
    1791:	89 04 24             	mov    %eax,(%rsp)
    1794:	8b 44 24 24          	mov    0x24(%rsp),%eax
    1798:	69 c0 57 cd 00 00    	imul   $0xcd57,%eax,%eax
    179e:	89 44 24 24          	mov    %eax,0x24(%rsp)
    17a2:	8b 44 24 18          	mov    0x18(%rsp),%eax
    17a6:	69 c0 de 06 00 00    	imul   $0x6de,%eax,%eax
    17ac:	89 44 24 18          	mov    %eax,0x18(%rsp)
    17b0:	8b 44 24 14          	mov    0x14(%rsp),%eax
    17b4:	69 c0 a5 0e 00 00    	imul   $0xea5,%eax,%eax
    17ba:	89 44 24 14          	mov    %eax,0x14(%rsp)
    17be:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    17c2:	69 c0 58 99 00 00    	imul   $0x9958,%eax,%eax
    17c8:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    17cc:	8b 44 24 14          	mov    0x14(%rsp),%eax
    17d0:	69 c0 66 95 00 00    	imul   $0x9566,%eax,%eax
    17d6:	89 44 24 14          	mov    %eax,0x14(%rsp)
    17da:	8b 44 24 24          	mov    0x24(%rsp),%eax
    17de:	69 c0 07 36 00 00    	imul   $0x3607,%eax,%eax
    17e4:	89 44 24 24          	mov    %eax,0x24(%rsp)
    17e8:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    17ec:	69 c0 00 11 00 00    	imul   $0x1100,%eax,%eax
    17f2:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    17f6:	8b 44 24 18          	mov    0x18(%rsp),%eax
    17fa:	69 c0 03 a2 00 00    	imul   $0xa203,%eax,%eax
    1800:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1804:	8b 44 24 08          	mov    0x8(%rsp),%eax
    1808:	69 c0 79 1e 00 00    	imul   $0x1e79,%eax,%eax
    180e:	89 44 24 08          	mov    %eax,0x8(%rsp)
    1812:	8b 44 24 14          	mov    0x14(%rsp),%eax
    1816:	69 c0 6d 44 00 00    	imul   $0x446d,%eax,%eax
    181c:	89 44 24 14          	mov    %eax,0x14(%rsp)
    1820:	8b 44 24 24          	mov    0x24(%rsp),%eax
    1824:	69 c0 b0 ca 00 00    	imul   $0xcab0,%eax,%eax
    182a:	89 44 24 24          	mov    %eax,0x24(%rsp)
    182e:	8b 44 24 10          	mov    0x10(%rsp),%eax
    1832:	69 c0 15 95 00 00    	imul   $0x9515,%eax,%eax
    1838:	89 44 24 10          	mov    %eax,0x10(%rsp)
    183c:	8b 44 24 08          	mov    0x8(%rsp),%eax
    1840:	69 c0 a9 f3 00 00    	imul   $0xf3a9,%eax,%eax
    1846:	89 44 24 08          	mov    %eax,0x8(%rsp)
    184a:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    184e:	69 c0 a8 67 00 00    	imul   $0x67a8,%eax,%eax
    1854:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    1858:	8b 44 24 04          	mov    0x4(%rsp),%eax
    185c:	69 c0 5c 87 00 00    	imul   $0x875c,%eax,%eax
    1862:	89 44 24 04          	mov    %eax,0x4(%rsp)
    1866:	8b 44 24 04          	mov    0x4(%rsp),%eax
    186a:	69 c0 a3 c4 00 00    	imul   $0xc4a3,%eax,%eax
    1870:	89 44 24 04          	mov    %eax,0x4(%rsp)
    1874:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1878:	69 c0 c7 7d 00 00    	imul   $0x7dc7,%eax,%eax
    187e:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1882:	8b 44 24 20          	mov    0x20(%rsp),%eax
    1886:	69 c0 41 21 00 00    	imul   $0x2141,%eax,%eax
    188c:	89 44 24 20          	mov    %eax,0x20(%rsp)
    1890:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    1894:	69 c0 05 a7 00 00    	imul   $0xa705,%eax,%eax
    189a:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    189e:	8b 44 24 24          	mov    0x24(%rsp),%eax
    18a2:	69 c0 e5 bf 00 00    	imul   $0xbfe5,%eax,%eax
    18a8:	89 44 24 24          	mov    %eax,0x24(%rsp)
    18ac:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    18b0:	69 c0 c7 cb 00 00    	imul   $0xcbc7,%eax,%eax
    18b6:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    18ba:	8b 44 24 14          	mov    0x14(%rsp),%eax
    18be:	69 c0 69 71 00 00    	imul   $0x7169,%eax,%eax
    18c4:	89 44 24 14          	mov    %eax,0x14(%rsp)
    18c8:	8b 44 24 08          	mov    0x8(%rsp),%eax
    18cc:	69 c0 1e 25 00 00    	imul   $0x251e,%eax,%eax
    18d2:	89 44 24 08          	mov    %eax,0x8(%rsp)
    18d6:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    18da:	69 c0 79 1e 00 00    	imul   $0x1e79,%eax,%eax
    18e0:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    18e4:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    18e8:	69 c0 ba 9a 00 00    	imul   $0x9aba,%eax,%eax
    18ee:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    18f2:	8b 04 24             	mov    (%rsp),%eax
    18f5:	69 c0 f2 aa 00 00    	imul   $0xaaf2,%eax,%eax
    18fb:	89 04 24             	mov    %eax,(%rsp)
    18fe:	8b 44 24 20          	mov    0x20(%rsp),%eax
    1902:	69 c0 32 74 00 00    	imul   $0x7432,%eax,%eax
    1908:	89 44 24 20          	mov    %eax,0x20(%rsp)
    190c:	8b 44 24 1c          	mov    0x1c(%rsp),%eax
    1910:	69 c0 98 06 00 00    	imul   $0x698,%eax,%eax
    1916:	89 44 24 1c          	mov    %eax,0x1c(%rsp)
    191a:	8b 44 24 18          	mov    0x18(%rsp),%eax
    191e:	69 c0 9e 16 00 00    	imul   $0x169e,%eax,%eax
    1924:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1928:	8b 04 24             	mov    (%rsp),%eax
    192b:	69 c0 6a 42 00 00    	imul   $0x426a,%eax,%eax
    1931:	89 04 24             	mov    %eax,(%rsp)
    1934:	8b 44 24 14          	mov    0x14(%rsp),%eax
    1938:	69 c0 ab c5 00 00    	imul   $0xc5ab,%eax,%eax
    193e:	89 44 24 14          	mov    %eax,0x14(%rsp)
    1942:	8b 44 24 08          	mov    0x8(%rsp),%eax
    1946:	69 c0 ad f2 00 00    	imul   $0xf2ad,%eax,%eax
    194c:	89 44 24 08          	mov    %eax,0x8(%rsp)
    1950:	8b 44 24 04          	mov    0x4(%rsp),%eax
    1954:	69 c0 8f d2 00 00    	imul   $0xd28f,%eax,%eax
    195a:	89 44 24 04          	mov    %eax,0x4(%rsp)
    195e:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1962:	69 c0 df cf 00 00    	imul   $0xcfdf,%eax,%eax
    1968:	89 44 24 18          	mov    %eax,0x18(%rsp)
    196c:	8b 44 24 10          	mov    0x10(%rsp),%eax
    1970:	69 c0 88 ce 00 00    	imul   $0xce88,%eax,%eax
    1976:	89 44 24 10          	mov    %eax,0x10(%rsp)
    197a:	8b 44 24 14          	mov    0x14(%rsp),%eax
    197e:	69 c0 00 b6 00 00    	imul   $0xb600,%eax,%eax
    1984:	89 44 24 14          	mov    %eax,0x14(%rsp)
    1988:	8b 44 24 24          	mov    0x24(%rsp),%eax
    198c:	69 c0 b1 85 00 00    	imul   $0x85b1,%eax,%eax
    1992:	89 44 24 24          	mov    %eax,0x24(%rsp)
    1996:	8b 44 24 04          	mov    0x4(%rsp),%eax
    199a:	69 c0 16 77 00 00    	imul   $0x7716,%eax,%eax
    19a0:	89 44 24 04          	mov    %eax,0x4(%rsp)
    19a4:	8b 44 24 18          	mov    0x18(%rsp),%eax
    19a8:	69 c0 d5 3a 00 00    	imul   $0x3ad5,%eax,%eax
    19ae:	89 44 24 18          	mov    %eax,0x18(%rsp)
    19b2:	8b 44 24 24          	mov    0x24(%rsp),%eax
    19b6:	69 c0 66 ee 00 00    	imul   $0xee66,%eax,%eax
    19bc:	89 44 24 24          	mov    %eax,0x24(%rsp)
    19c0:	8b 44 24 24          	mov    0x24(%rsp),%eax
    19c4:	69 c0 77 f8 00 00    	imul   $0xf877,%eax,%eax
    19ca:	89 44 24 24          	mov    %eax,0x24(%rsp)
    19ce:	8b 44 24 04          	mov    0x4(%rsp),%eax
    19d2:	69 c0 f9 3a 00 00    	imul   $0x3af9,%eax,%eax
    19d8:	89 44 24 04          	mov    %eax,0x4(%rsp)
    19dc:	8b 44 24 14          	mov    0x14(%rsp),%eax
    19e0:	69 c0 61 d9 00 00    	imul   $0xd961,%eax,%eax
    19e6:	89 44 24 14          	mov    %eax,0x14(%rsp)
    19ea:	8b 44 24 24          	mov    0x24(%rsp),%eax
    19ee:	69 c0 84 d4 00 00    	imul   $0xd484,%eax,%eax
    19f4:	89 44 24 24          	mov    %eax,0x24(%rsp)
    19f8:	8b 04 24             	mov    (%rsp),%eax
    19fb:	69 c0 d1 af 00 00    	imul   $0xafd1,%eax,%eax
    1a01:	89 04 24             	mov    %eax,(%rsp)
    1a04:	8b 44 24 08          	mov    0x8(%rsp),%eax
    1a08:	69 c0 fa 8d 00 00    	imul   $0x8dfa,%eax,%eax
    1a0e:	89 44 24 08          	mov    %eax,0x8(%rsp)
    1a12:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    1a16:	69 c0 fb 1d 00 00    	imul   $0x1dfb,%eax,%eax
    1a1c:	89 44 24 0c          	mov    %eax,0xc(%rsp)
    1a20:	8b 44 24 24          	mov    0x24(%rsp),%eax
    1a24:	69 c0 ef b8 00 00    	imul   $0xb8ef,%eax,%eax
    1a2a:	89 44 24 24          	mov    %eax,0x24(%rsp)
    1a2e:	8b 04 24             	mov    (%rsp),%eax
    1a31:	69 c0 96 94 00 00    	imul   $0x9496,%eax,%eax
    1a37:	89 04 24             	mov    %eax,(%rsp)
    1a3a:	8b 44 24 04          	mov    0x4(%rsp),%eax
    1a3e:	69 c0 1f 6a 00 00    	imul   $0x6a1f,%eax,%eax
    1a44:	89 44 24 04          	mov    %eax,0x4(%rsp)
    1a48:	8b 44 24 14          	mov    0x14(%rsp),%eax
    1a4c:	69 c0 92 18 00 00    	imul   $0x1892,%eax,%eax
    1a52:	89 44 24 14          	mov    %eax,0x14(%rsp)
    1a56:	8b 44 24 18          	mov    0x18(%rsp),%eax
    1a5a:	69 c0 6e fd 00 00    	imul   $0xfd6e,%eax,%eax
    1a60:	89 44 24 18          	mov    %eax,0x18(%rsp)
    1a64:	8b 44 24 24          	mov    0x24(%rsp),%eax
    1a68:	69 c0 88 47 00 00    	imul   $0x4788,%eax,%eax
    1a6e:	89 44 24 24          	mov    %eax,0x24(%rsp)
    1a72:	8b 44 24 24          	mov    0x24(%rsp),%eax
    1a76:	69 c0 13 49 00 00    	imul   $0x4913,%eax,%eax
    1a7c:	89 44 24 24          	mov    %eax,0x24(%rsp)
    1a80:	ba 00 00 00 00       	mov    $0x0,%edx
    1a85:	b8 00 00 00 00       	mov    $0x0,%eax
    1a8a:	eb 0a                	jmp    1a96 <scramble+0x56a>
    1a8c:	89 d1                	mov    %edx,%ecx
    1a8e:	8b 0c 8c             	mov    (%rsp,%rcx,4),%ecx
    1a91:	01 c8                	add    %ecx,%eax
    1a93:	83 c2 01             	add    $0x1,%edx
    1a96:	83 fa 09             	cmp    $0x9,%edx
    1a99:	76 f1                	jbe    1a8c <scramble+0x560>
    1a9b:	48 8b 74 24 28       	mov    0x28(%rsp),%rsi
    1aa0:	64 48 33 34 25 28 00 	xor    %fs:0x28,%rsi
    1aa7:	00 00 
    1aa9:	75 05                	jne    1ab0 <scramble+0x584>
    1aab:	48 83 c4 38          	add    $0x38,%rsp
    1aaf:	c3                   	retq   
    1ab0:	e8 ab f3 ff ff       	callq  e60 <__stack_chk_fail@plt>

0000000000001ab5 <getbuf>:
    1ab5:	48 83 ec 18          	sub    $0x18,%rsp
    1ab9:	48 89 e7             	mov    %rsp,%rdi
    1abc:	e8 b5 03 00 00       	callq  1e76 <Gets>
    1ac1:	b8 01 00 00 00       	mov    $0x1,%eax
    1ac6:	48 83 c4 18          	add    $0x18,%rsp
    1aca:	c3                   	retq   

0000000000001acb <touch1>:
    1acb:	48 83 ec 08          	sub    $0x8,%rsp
    1acf:	c7 05 03 39 20 00 01 	movl   $0x1,0x203903(%rip)        # 2053dc <vlevel>
    1ad6:	00 00 00 
    1ad9:	48 8d 3d a2 1a 00 00 	lea    0x1aa2(%rip),%rdi        # 3582 <_IO_stdin_used+0x2e2>
    1ae0:	e8 5b f3 ff ff       	callq  e40 <puts@plt>
    1ae5:	bf 01 00 00 00       	mov    $0x1,%edi
    1aea:	e8 f7 05 00 00       	callq  20e6 <validate>
    1aef:	bf 00 00 00 00       	mov    $0x0,%edi
    1af4:	e8 b7 f4 ff ff       	callq  fb0 <exit@plt>

0000000000001af9 <touch2>:
    1af9:	48 83 ec 08          	sub    $0x8,%rsp
    1afd:	89 fa                	mov    %edi,%edx
    1aff:	c7 05 d3 38 20 00 02 	movl   $0x2,0x2038d3(%rip)        # 2053dc <vlevel>
    1b06:	00 00 00 
    1b09:	39 3d d5 38 20 00    	cmp    %edi,0x2038d5(%rip)        # 2053e4 <cookie>
    1b0f:	74 2a                	je     1b3b <touch2+0x42>
    1b11:	48 8d 35 b8 1a 00 00 	lea    0x1ab8(%rip),%rsi        # 35d0 <_IO_stdin_used+0x330>
    1b18:	bf 01 00 00 00       	mov    $0x1,%edi
    1b1d:	b8 00 00 00 00       	mov    $0x0,%eax
    1b22:	e8 39 f4 ff ff       	callq  f60 <__printf_chk@plt>
    1b27:	bf 02 00 00 00       	mov    $0x2,%edi
    1b2c:	e8 85 06 00 00       	callq  21b6 <fail>
    1b31:	bf 00 00 00 00       	mov    $0x0,%edi
    1b36:	e8 75 f4 ff ff       	callq  fb0 <exit@plt>
    1b3b:	48 8d 35 66 1a 00 00 	lea    0x1a66(%rip),%rsi        # 35a8 <_IO_stdin_used+0x308>
    1b42:	bf 01 00 00 00       	mov    $0x1,%edi
    1b47:	b8 00 00 00 00       	mov    $0x0,%eax
    1b4c:	e8 0f f4 ff ff       	callq  f60 <__printf_chk@plt>
    1b51:	bf 02 00 00 00       	mov    $0x2,%edi
    1b56:	e8 8b 05 00 00       	callq  20e6 <validate>
    1b5b:	eb d4                	jmp    1b31 <touch2+0x38>

0000000000001b5d <hexmatch>:
    1b5d:	41 54                	push   %r12
    1b5f:	55                   	push   %rbp
    1b60:	53                   	push   %rbx
    1b61:	48 83 c4 80          	add    $0xffffffffffffff80,%rsp
    1b65:	89 fd                	mov    %edi,%ebp
    1b67:	48 89 f3             	mov    %rsi,%rbx
    1b6a:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1b71:	00 00 
    1b73:	48 89 44 24 78       	mov    %rax,0x78(%rsp)
    1b78:	31 c0                	xor    %eax,%eax
    1b7a:	e8 a1 f3 ff ff       	callq  f20 <random@plt>
    1b7f:	48 89 c1             	mov    %rax,%rcx
    1b82:	48 ba 0b d7 a3 70 3d 	movabs $0xa3d70a3d70a3d70b,%rdx
    1b89:	0a d7 a3 
    1b8c:	48 f7 ea             	imul   %rdx
    1b8f:	48 01 ca             	add    %rcx,%rdx
    1b92:	48 c1 fa 06          	sar    $0x6,%rdx
    1b96:	48 89 c8             	mov    %rcx,%rax
    1b99:	48 c1 f8 3f          	sar    $0x3f,%rax
    1b9d:	48 29 c2             	sub    %rax,%rdx
    1ba0:	48 8d 04 92          	lea    (%rdx,%rdx,4),%rax
    1ba4:	48 8d 14 80          	lea    (%rax,%rax,4),%rdx
    1ba8:	48 8d 04 95 00 00 00 	lea    0x0(,%rdx,4),%rax
    1baf:	00 
    1bb0:	48 29 c1             	sub    %rax,%rcx
    1bb3:	4c 8d 24 0c          	lea    (%rsp,%rcx,1),%r12
    1bb7:	41 89 e8             	mov    %ebp,%r8d
    1bba:	48 8d 0d de 19 00 00 	lea    0x19de(%rip),%rcx        # 359f <_IO_stdin_used+0x2ff>
    1bc1:	48 c7 c2 ff ff ff ff 	mov    $0xffffffffffffffff,%rdx
    1bc8:	be 01 00 00 00       	mov    $0x1,%esi
    1bcd:	4c 89 e7             	mov    %r12,%rdi
    1bd0:	b8 00 00 00 00       	mov    $0x0,%eax
    1bd5:	e8 06 f4 ff ff       	callq  fe0 <__sprintf_chk@plt>
    1bda:	ba 09 00 00 00       	mov    $0x9,%edx
    1bdf:	4c 89 e6             	mov    %r12,%rsi
    1be2:	48 89 df             	mov    %rbx,%rdi
    1be5:	e8 36 f2 ff ff       	callq  e20 <strncmp@plt>
    1bea:	85 c0                	test   %eax,%eax
    1bec:	0f 94 c0             	sete   %al
    1bef:	48 8b 5c 24 78       	mov    0x78(%rsp),%rbx
    1bf4:	64 48 33 1c 25 28 00 	xor    %fs:0x28,%rbx
    1bfb:	00 00 
    1bfd:	75 0c                	jne    1c0b <hexmatch+0xae>
    1bff:	0f b6 c0             	movzbl %al,%eax
    1c02:	48 83 ec 80          	sub    $0xffffffffffffff80,%rsp
    1c06:	5b                   	pop    %rbx
    1c07:	5d                   	pop    %rbp
    1c08:	41 5c                	pop    %r12
    1c0a:	c3                   	retq   
    1c0b:	e8 50 f2 ff ff       	callq  e60 <__stack_chk_fail@plt>

0000000000001c10 <touch3>:
    1c10:	53                   	push   %rbx
    1c11:	48 89 fb             	mov    %rdi,%rbx
    1c14:	c7 05 be 37 20 00 03 	movl   $0x3,0x2037be(%rip)        # 2053dc <vlevel>
    1c1b:	00 00 00 
    1c1e:	48 89 fe             	mov    %rdi,%rsi
    1c21:	8b 3d bd 37 20 00    	mov    0x2037bd(%rip),%edi        # 2053e4 <cookie>
    1c27:	e8 31 ff ff ff       	callq  1b5d <hexmatch>
    1c2c:	85 c0                	test   %eax,%eax
    1c2e:	74 2d                	je     1c5d <touch3+0x4d>
    1c30:	48 89 da             	mov    %rbx,%rdx
    1c33:	48 8d 35 be 19 00 00 	lea    0x19be(%rip),%rsi        # 35f8 <_IO_stdin_used+0x358>
    1c3a:	bf 01 00 00 00       	mov    $0x1,%edi
    1c3f:	b8 00 00 00 00       	mov    $0x0,%eax
    1c44:	e8 17 f3 ff ff       	callq  f60 <__printf_chk@plt>
    1c49:	bf 03 00 00 00       	mov    $0x3,%edi
    1c4e:	e8 93 04 00 00       	callq  20e6 <validate>
    1c53:	bf 00 00 00 00       	mov    $0x0,%edi
    1c58:	e8 53 f3 ff ff       	callq  fb0 <exit@plt>
    1c5d:	48 89 da             	mov    %rbx,%rdx
    1c60:	48 8d 35 b9 19 00 00 	lea    0x19b9(%rip),%rsi        # 3620 <_IO_stdin_used+0x380>
    1c67:	bf 01 00 00 00       	mov    $0x1,%edi
    1c6c:	b8 00 00 00 00       	mov    $0x0,%eax
    1c71:	e8 ea f2 ff ff       	callq  f60 <__printf_chk@plt>
    1c76:	bf 03 00 00 00       	mov    $0x3,%edi
    1c7b:	e8 36 05 00 00       	callq  21b6 <fail>
    1c80:	eb d1                	jmp    1c53 <touch3+0x43>

0000000000001c82 <test>:
    1c82:	48 83 ec 08          	sub    $0x8,%rsp
    1c86:	b8 00 00 00 00       	mov    $0x0,%eax
    1c8b:	e8 25 fe ff ff       	callq  1ab5 <getbuf>
    1c90:	89 c2                	mov    %eax,%edx
    1c92:	48 8d 35 af 19 00 00 	lea    0x19af(%rip),%rsi        # 3648 <_IO_stdin_used+0x3a8>
    1c99:	bf 01 00 00 00       	mov    $0x1,%edi
    1c9e:	b8 00 00 00 00       	mov    $0x0,%eax
    1ca3:	e8 b8 f2 ff ff       	callq  f60 <__printf_chk@plt>
    1ca8:	48 83 c4 08          	add    $0x8,%rsp
    1cac:	c3                   	retq   

0000000000001cad <start_farm>:
    1cad:	b8 01 00 00 00       	mov    $0x1,%eax
    1cb2:	c3                   	retq   

0000000000001cb3 <getval_436>:
    1cb3:	b8 3d 45 58 92       	mov    $0x9258453d,%eax
    1cb8:	c3                   	retq   

0000000000001cb9 <setval_147>:
    1cb9:	c7 07 5f bf 58 90    	movl   $0x9058bf5f,(%rdi)
    1cbf:	c3                   	retq   

0000000000001cc0 <addval_189>:
    1cc0:	8d 87 48 89 c7 90    	lea    -0x6f3876b8(%rdi),%eax
    1cc6:	c3                   	retq   

0000000000001cc7 <setval_350>:
    1cc7:	c7 07 2f 5c 2f 58    	movl   $0x582f5c2f,(%rdi)
    1ccd:	c3                   	retq   

0000000000001cce <getval_281>:
    1cce:	b8 48 89 c7 c7       	mov    $0xc7c78948,%eax
    1cd3:	c3                   	retq   

0000000000001cd4 <setval_323>:
    1cd4:	c7 07 48 89 c7 c3    	movl   $0xc3c78948,(%rdi)
    1cda:	c3                   	retq   

0000000000001cdb <setval_348>:
    1cdb:	c7 07 48 88 c7 c3    	movl   $0xc3c78848,(%rdi)
    1ce1:	c3                   	retq   

0000000000001ce2 <setval_109>:
    1ce2:	c7 07 78 90 90 90    	movl   $0x90909078,(%rdi)
    1ce8:	c3                   	retq   

0000000000001ce9 <mid_farm>:
    1ce9:	b8 01 00 00 00       	mov    $0x1,%eax
    1cee:	c3                   	retq   

0000000000001cef <add_xy>:
    1cef:	48 8d 04 37          	lea    (%rdi,%rsi,1),%rax
    1cf3:	c3                   	retq   

0000000000001cf4 <addval_477>:
    1cf4:	8d 87 48 89 e0 90    	lea    -0x6f1f76b8(%rdi),%eax
    1cfa:	c3                   	retq   

0000000000001cfb <addval_239>:
    1cfb:	8d 87 89 c1 a4 db    	lea    -0x245b3e77(%rdi),%eax
    1d01:	c3                   	retq   

0000000000001d02 <addval_152>:
    1d02:	8d 87 48 89 e0 c3    	lea    -0x3c1f76b8(%rdi),%eax
    1d08:	c3                   	retq   

0000000000001d09 <addval_499>:
    1d09:	8d 87 89 d6 48 d2    	lea    -0x2db72977(%rdi),%eax
    1d0f:	c3                   	retq   

0000000000001d10 <addval_302>:
    1d10:	8d 87 8d ca 38 c0    	lea    -0x3fc73573(%rdi),%eax
    1d16:	c3                   	retq   

0000000000001d17 <addval_279>:
    1d17:	8d 87 89 c1 38 d2    	lea    -0x2dc73e77(%rdi),%eax
    1d1d:	c3                   	retq   

0000000000001d1e <setval_251>:
    1d1e:	c7 07 8d d6 08 c9    	movl   $0xc908d68d,(%rdi)
    1d24:	c3                   	retq   

0000000000001d25 <getval_126>:
    1d25:	b8 89 ca 94 d2       	mov    $0xd294ca89,%eax
    1d2a:	c3                   	retq   

0000000000001d2b <setval_297>:
    1d2b:	c7 07 81 d6 20 c9    	movl   $0xc920d681,(%rdi)
    1d31:	c3                   	retq   

0000000000001d32 <getval_115>:
    1d32:	b8 4c 89 e0 c3       	mov    $0xc3e0894c,%eax
    1d37:	c3                   	retq   

0000000000001d38 <setval_269>:
    1d38:	c7 07 89 c1 28 d2    	movl   $0xd228c189,(%rdi)
    1d3e:	c3                   	retq   

0000000000001d3f <addval_137>:
    1d3f:	8d 87 48 89 e0 94    	lea    -0x6b1f76b8(%rdi),%eax
    1d45:	c3                   	retq   

0000000000001d46 <getval_219>:
    1d46:	b8 89 d6 20 db       	mov    $0xdb20d689,%eax
    1d4b:	c3                   	retq   

0000000000001d4c <getval_199>:
    1d4c:	b8 48 c9 e0 c3       	mov    $0xc3e0c948,%eax
    1d51:	c3                   	retq   

0000000000001d52 <addval_387>:
    1d52:	8d 87 89 ca 00 c9    	lea    -0x36ff3577(%rdi),%eax
    1d58:	c3                   	retq   

0000000000001d59 <setval_116>:
    1d59:	c7 07 89 c1 18 db    	movl   $0xdb18c189,(%rdi)
    1d5f:	c3                   	retq   

0000000000001d60 <addval_382>:
    1d60:	8d 87 84 89 c1 92    	lea    -0x6d3e767c(%rdi),%eax
    1d66:	c3                   	retq   

0000000000001d67 <getval_498>:
    1d67:	b8 89 ca 08 c9       	mov    $0xc908ca89,%eax
    1d6c:	c3                   	retq   

0000000000001d6d <getval_171>:
    1d6d:	b8 48 89 e0 c1       	mov    $0xc1e08948,%eax
    1d72:	c3                   	retq   

0000000000001d73 <getval_270>:
    1d73:	b8 09 ca 38 db       	mov    $0xdb38ca09,%eax
    1d78:	c3                   	retq   

0000000000001d79 <setval_449>:
    1d79:	c7 07 40 89 e0 c3    	movl   $0xc3e08940,(%rdi)
    1d7f:	c3                   	retq   

0000000000001d80 <addval_427>:
    1d80:	8d 87 89 d6 c3 24    	lea    0x24c3d689(%rdi),%eax
    1d86:	c3                   	retq   

0000000000001d87 <getval_184>:
    1d87:	b8 89 c1 90 c2       	mov    $0xc290c189,%eax
    1d8c:	c3                   	retq   

0000000000001d8d <getval_262>:
    1d8d:	b8 8d c1 20 db       	mov    $0xdb20c18d,%eax
    1d92:	c3                   	retq   

0000000000001d93 <getval_280>:
    1d93:	b8 89 d6 a4 c0       	mov    $0xc0a4d689,%eax
    1d98:	c3                   	retq   

0000000000001d99 <setval_336>:
    1d99:	c7 07 89 c1 08 db    	movl   $0xdb08c189,(%rdi)
    1d9f:	c3                   	retq   

0000000000001da0 <getval_408>:
    1da0:	b8 89 ca 30 c0       	mov    $0xc030ca89,%eax
    1da5:	c3                   	retq   

0000000000001da6 <getval_351>:
    1da6:	b8 48 99 e0 90       	mov    $0x90e09948,%eax
    1dab:	c3                   	retq   

0000000000001dac <setval_230>:
    1dac:	c7 07 89 ca 30 c0    	movl   $0xc030ca89,(%rdi)
    1db2:	c3                   	retq   

0000000000001db3 <setval_243>:
    1db3:	c7 07 89 ca 20 db    	movl   $0xdb20ca89,(%rdi)
    1db9:	c3                   	retq   

0000000000001dba <addval_314>:
    1dba:	8d 87 99 d6 08 d2    	lea    -0x2df72967(%rdi),%eax
    1dc0:	c3                   	retq   

0000000000001dc1 <setval_493>:
    1dc1:	c7 07 a9 d6 38 d2    	movl   $0xd238d6a9,(%rdi)
    1dc7:	c3                   	retq   

0000000000001dc8 <end_farm>:
    1dc8:	b8 01 00 00 00       	mov    $0x1,%eax
    1dcd:	c3                   	retq   

0000000000001dce <save_char>:
    1dce:	8b 05 30 42 20 00    	mov    0x204230(%rip),%eax        # 206004 <gets_cnt>
    1dd4:	3d ff 03 00 00       	cmp    $0x3ff,%eax
    1dd9:	7f 4a                	jg     1e25 <save_char+0x57>
    1ddb:	89 f9                	mov    %edi,%ecx
    1ddd:	c0 e9 04             	shr    $0x4,%cl
    1de0:	8d 14 40             	lea    (%rax,%rax,2),%edx
    1de3:	4c 8d 05 86 1b 00 00 	lea    0x1b86(%rip),%r8        # 3970 <trans_char>
    1dea:	83 e1 0f             	and    $0xf,%ecx
    1ded:	45 0f b6 0c 08       	movzbl (%r8,%rcx,1),%r9d
    1df2:	48 8d 0d 07 36 20 00 	lea    0x203607(%rip),%rcx        # 205400 <gets_buf>
    1df9:	48 63 f2             	movslq %edx,%rsi
    1dfc:	44 88 0c 31          	mov    %r9b,(%rcx,%rsi,1)
    1e00:	8d 72 01             	lea    0x1(%rdx),%esi
    1e03:	83 e7 0f             	and    $0xf,%edi
    1e06:	41 0f b6 3c 38       	movzbl (%r8,%rdi,1),%edi
    1e0b:	48 63 f6             	movslq %esi,%rsi
    1e0e:	40 88 3c 31          	mov    %dil,(%rcx,%rsi,1)
    1e12:	83 c2 02             	add    $0x2,%edx
    1e15:	48 63 d2             	movslq %edx,%rdx
    1e18:	c6 04 11 20          	movb   $0x20,(%rcx,%rdx,1)
    1e1c:	83 c0 01             	add    $0x1,%eax
    1e1f:	89 05 df 41 20 00    	mov    %eax,0x2041df(%rip)        # 206004 <gets_cnt>
    1e25:	f3 c3                	repz retq 

0000000000001e27 <save_term>:
    1e27:	8b 05 d7 41 20 00    	mov    0x2041d7(%rip),%eax        # 206004 <gets_cnt>
    1e2d:	8d 04 40             	lea    (%rax,%rax,2),%eax
    1e30:	48 98                	cltq   
    1e32:	48 8d 15 c7 35 20 00 	lea    0x2035c7(%rip),%rdx        # 205400 <gets_buf>
    1e39:	c6 04 02 00          	movb   $0x0,(%rdx,%rax,1)
    1e3d:	c3                   	retq   

0000000000001e3e <check_fail>:
    1e3e:	48 83 ec 08          	sub    $0x8,%rsp
    1e42:	0f be 15 bf 41 20 00 	movsbl 0x2041bf(%rip),%edx        # 206008 <target_prefix>
    1e49:	4c 8d 05 b0 35 20 00 	lea    0x2035b0(%rip),%r8        # 205400 <gets_buf>
    1e50:	8b 0d 82 35 20 00    	mov    0x203582(%rip),%ecx        # 2053d8 <check_level>
    1e56:	48 8d 35 0e 18 00 00 	lea    0x180e(%rip),%rsi        # 366b <_IO_stdin_used+0x3cb>
    1e5d:	bf 01 00 00 00       	mov    $0x1,%edi
    1e62:	b8 00 00 00 00       	mov    $0x0,%eax
    1e67:	e8 f4 f0 ff ff       	callq  f60 <__printf_chk@plt>
    1e6c:	bf 01 00 00 00       	mov    $0x1,%edi
    1e71:	e8 3a f1 ff ff       	callq  fb0 <exit@plt>

0000000000001e76 <Gets>:
    1e76:	41 54                	push   %r12
    1e78:	55                   	push   %rbp
    1e79:	53                   	push   %rbx
    1e7a:	49 89 fc             	mov    %rdi,%r12
    1e7d:	c7 05 7d 41 20 00 00 	movl   $0x0,0x20417d(%rip)        # 206004 <gets_cnt>
    1e84:	00 00 00 
    1e87:	48 89 fb             	mov    %rdi,%rbx
    1e8a:	eb 11                	jmp    1e9d <Gets+0x27>
    1e8c:	48 8d 6b 01          	lea    0x1(%rbx),%rbp
    1e90:	88 03                	mov    %al,(%rbx)
    1e92:	0f b6 f8             	movzbl %al,%edi
    1e95:	e8 34 ff ff ff       	callq  1dce <save_char>
    1e9a:	48 89 eb             	mov    %rbp,%rbx
    1e9d:	48 8b 3d 2c 35 20 00 	mov    0x20352c(%rip),%rdi        # 2053d0 <infile>
    1ea4:	e8 87 f0 ff ff       	callq  f30 <_IO_getc@plt>
    1ea9:	83 f8 ff             	cmp    $0xffffffff,%eax
    1eac:	74 05                	je     1eb3 <Gets+0x3d>
    1eae:	83 f8 0a             	cmp    $0xa,%eax
    1eb1:	75 d9                	jne    1e8c <Gets+0x16>
    1eb3:	c6 03 00             	movb   $0x0,(%rbx)
    1eb6:	b8 00 00 00 00       	mov    $0x0,%eax
    1ebb:	e8 67 ff ff ff       	callq  1e27 <save_term>
    1ec0:	4c 89 e0             	mov    %r12,%rax
    1ec3:	5b                   	pop    %rbx
    1ec4:	5d                   	pop    %rbp
    1ec5:	41 5c                	pop    %r12
    1ec7:	c3                   	retq   

0000000000001ec8 <notify_server>:
    1ec8:	55                   	push   %rbp
    1ec9:	53                   	push   %rbx
    1eca:	48 81 ec 18 40 00 00 	sub    $0x4018,%rsp
    1ed1:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1ed8:	00 00 
    1eda:	48 89 84 24 08 40 00 	mov    %rax,0x4008(%rsp)
    1ee1:	00 
    1ee2:	31 c0                	xor    %eax,%eax
    1ee4:	83 3d fd 34 20 00 00 	cmpl   $0x0,0x2034fd(%rip)        # 2053e8 <is_checker>
    1eeb:	0f 85 d2 00 00 00    	jne    1fc3 <notify_server+0xfb>
    1ef1:	89 fb                	mov    %edi,%ebx
    1ef3:	8b 05 0b 41 20 00    	mov    0x20410b(%rip),%eax        # 206004 <gets_cnt>
    1ef9:	83 c0 64             	add    $0x64,%eax
    1efc:	3d 00 20 00 00       	cmp    $0x2000,%eax
    1f01:	0f 8f dd 00 00 00    	jg     1fe4 <notify_server+0x11c>
    1f07:	0f be 05 fa 40 20 00 	movsbl 0x2040fa(%rip),%eax        # 206008 <target_prefix>
    1f0e:	83 3d 53 34 20 00 00 	cmpl   $0x0,0x203453(%rip)        # 205368 <notify>
    1f15:	0f 84 e9 00 00 00    	je     2004 <notify_server+0x13c>
    1f1b:	8b 15 bf 34 20 00    	mov    0x2034bf(%rip),%edx        # 2053e0 <authkey>
    1f21:	85 db                	test   %ebx,%ebx
    1f23:	0f 84 e5 00 00 00    	je     200e <notify_server+0x146>
    1f29:	48 8d 2d 51 17 00 00 	lea    0x1751(%rip),%rbp        # 3681 <_IO_stdin_used+0x3e1>
    1f30:	48 89 e7             	mov    %rsp,%rdi
    1f33:	48 8d 0d c6 34 20 00 	lea    0x2034c6(%rip),%rcx        # 205400 <gets_buf>
    1f3a:	51                   	push   %rcx
    1f3b:	56                   	push   %rsi
    1f3c:	50                   	push   %rax
    1f3d:	52                   	push   %rdx
    1f3e:	49 89 e9             	mov    %rbp,%r9
    1f41:	44 8b 05 c8 30 20 00 	mov    0x2030c8(%rip),%r8d        # 205010 <target_id>
    1f48:	48 8d 0d 3c 17 00 00 	lea    0x173c(%rip),%rcx        # 368b <_IO_stdin_used+0x3eb>
    1f4f:	ba 00 20 00 00       	mov    $0x2000,%edx
    1f54:	be 01 00 00 00       	mov    $0x1,%esi
    1f59:	b8 00 00 00 00       	mov    $0x0,%eax
    1f5e:	e8 7d f0 ff ff       	callq  fe0 <__sprintf_chk@plt>
    1f63:	48 83 c4 20          	add    $0x20,%rsp
    1f67:	83 3d fa 33 20 00 00 	cmpl   $0x0,0x2033fa(%rip)        # 205368 <notify>
    1f6e:	0f 84 df 00 00 00    	je     2053 <notify_server+0x18b>
    1f74:	85 db                	test   %ebx,%ebx
    1f76:	0f 84 c6 00 00 00    	je     2042 <notify_server+0x17a>
    1f7c:	48 89 e1             	mov    %rsp,%rcx
    1f7f:	4c 8d 8c 24 00 20 00 	lea    0x2000(%rsp),%r9
    1f86:	00 
    1f87:	41 b8 00 00 00 00    	mov    $0x0,%r8d
    1f8d:	48 8b 15 94 30 20 00 	mov    0x203094(%rip),%rdx        # 205028 <lab>
    1f94:	48 8b 35 95 30 20 00 	mov    0x203095(%rip),%rsi        # 205030 <course>
    1f9b:	48 8b 3d 7e 30 20 00 	mov    0x20307e(%rip),%rdi        # 205020 <user_id>
    1fa2:	e8 af 11 00 00       	callq  3156 <driver_post>
    1fa7:	85 c0                	test   %eax,%eax
    1fa9:	78 6f                	js     201a <notify_server+0x152>
    1fab:	48 8d 3d 1e 18 00 00 	lea    0x181e(%rip),%rdi        # 37d0 <_IO_stdin_used+0x530>
    1fb2:	e8 89 ee ff ff       	callq  e40 <puts@plt>
    1fb7:	48 8d 3d f5 16 00 00 	lea    0x16f5(%rip),%rdi        # 36b3 <_IO_stdin_used+0x413>
    1fbe:	e8 7d ee ff ff       	callq  e40 <puts@plt>
    1fc3:	48 8b 84 24 08 40 00 	mov    0x4008(%rsp),%rax
    1fca:	00 
    1fcb:	64 48 33 04 25 28 00 	xor    %fs:0x28,%rax
    1fd2:	00 00 
    1fd4:	0f 85 07 01 00 00    	jne    20e1 <notify_server+0x219>
    1fda:	48 81 c4 18 40 00 00 	add    $0x4018,%rsp
    1fe1:	5b                   	pop    %rbx
    1fe2:	5d                   	pop    %rbp
    1fe3:	c3                   	retq   
    1fe4:	48 8d 35 b5 17 00 00 	lea    0x17b5(%rip),%rsi        # 37a0 <_IO_stdin_used+0x500>
    1feb:	bf 01 00 00 00       	mov    $0x1,%edi
    1ff0:	b8 00 00 00 00       	mov    $0x0,%eax
    1ff5:	e8 66 ef ff ff       	callq  f60 <__printf_chk@plt>
    1ffa:	bf 01 00 00 00       	mov    $0x1,%edi
    1fff:	e8 ac ef ff ff       	callq  fb0 <exit@plt>
    2004:	ba ff ff ff ff       	mov    $0xffffffff,%edx
    2009:	e9 13 ff ff ff       	jmpq   1f21 <notify_server+0x59>
    200e:	48 8d 2d 71 16 00 00 	lea    0x1671(%rip),%rbp        # 3686 <_IO_stdin_used+0x3e6>
    2015:	e9 16 ff ff ff       	jmpq   1f30 <notify_server+0x68>
    201a:	48 8d 94 24 00 20 00 	lea    0x2000(%rsp),%rdx
    2021:	00 
    2022:	48 8d 35 7e 16 00 00 	lea    0x167e(%rip),%rsi        # 36a7 <_IO_stdin_used+0x407>
    2029:	bf 01 00 00 00       	mov    $0x1,%edi
    202e:	b8 00 00 00 00       	mov    $0x0,%eax
    2033:	e8 28 ef ff ff       	callq  f60 <__printf_chk@plt>
    2038:	bf 01 00 00 00       	mov    $0x1,%edi
    203d:	e8 6e ef ff ff       	callq  fb0 <exit@plt>
    2042:	48 8d 3d 74 16 00 00 	lea    0x1674(%rip),%rdi        # 36bd <_IO_stdin_used+0x41d>
    2049:	e8 f2 ed ff ff       	callq  e40 <puts@plt>
    204e:	e9 70 ff ff ff       	jmpq   1fc3 <notify_server+0xfb>
    2053:	48 89 ea             	mov    %rbp,%rdx
    2056:	48 8d 35 ab 17 00 00 	lea    0x17ab(%rip),%rsi        # 3808 <_IO_stdin_used+0x568>
    205d:	bf 01 00 00 00       	mov    $0x1,%edi
    2062:	b8 00 00 00 00       	mov    $0x0,%eax
    2067:	e8 f4 ee ff ff       	callq  f60 <__printf_chk@plt>
    206c:	48 8b 15 ad 2f 20 00 	mov    0x202fad(%rip),%rdx        # 205020 <user_id>
    2073:	48 8d 35 4a 16 00 00 	lea    0x164a(%rip),%rsi        # 36c4 <_IO_stdin_used+0x424>
    207a:	bf 01 00 00 00       	mov    $0x1,%edi
    207f:	b8 00 00 00 00       	mov    $0x0,%eax
    2084:	e8 d7 ee ff ff       	callq  f60 <__printf_chk@plt>
    2089:	48 8b 15 a0 2f 20 00 	mov    0x202fa0(%rip),%rdx        # 205030 <course>
    2090:	48 8d 35 3a 16 00 00 	lea    0x163a(%rip),%rsi        # 36d1 <_IO_stdin_used+0x431>
    2097:	bf 01 00 00 00       	mov    $0x1,%edi
    209c:	b8 00 00 00 00       	mov    $0x0,%eax
    20a1:	e8 ba ee ff ff       	callq  f60 <__printf_chk@plt>
    20a6:	48 8b 15 7b 2f 20 00 	mov    0x202f7b(%rip),%rdx        # 205028 <lab>
    20ad:	48 8d 35 29 16 00 00 	lea    0x1629(%rip),%rsi        # 36dd <_IO_stdin_used+0x43d>
    20b4:	bf 01 00 00 00       	mov    $0x1,%edi
    20b9:	b8 00 00 00 00       	mov    $0x0,%eax
    20be:	e8 9d ee ff ff       	callq  f60 <__printf_chk@plt>
    20c3:	48 89 e2             	mov    %rsp,%rdx
    20c6:	48 8d 35 19 16 00 00 	lea    0x1619(%rip),%rsi        # 36e6 <_IO_stdin_used+0x446>
    20cd:	bf 01 00 00 00       	mov    $0x1,%edi
    20d2:	b8 00 00 00 00       	mov    $0x0,%eax
    20d7:	e8 84 ee ff ff       	callq  f60 <__printf_chk@plt>
    20dc:	e9 e2 fe ff ff       	jmpq   1fc3 <notify_server+0xfb>
    20e1:	e8 7a ed ff ff       	callq  e60 <__stack_chk_fail@plt>

00000000000020e6 <validate>:
    20e6:	53                   	push   %rbx
    20e7:	89 fb                	mov    %edi,%ebx
    20e9:	83 3d f8 32 20 00 00 	cmpl   $0x0,0x2032f8(%rip)        # 2053e8 <is_checker>
    20f0:	74 72                	je     2164 <validate+0x7e>
    20f2:	39 3d e4 32 20 00    	cmp    %edi,0x2032e4(%rip)        # 2053dc <vlevel>
    20f8:	75 32                	jne    212c <validate+0x46>
    20fa:	8b 15 d8 32 20 00    	mov    0x2032d8(%rip),%edx        # 2053d8 <check_level>
    2100:	39 fa                	cmp    %edi,%edx
    2102:	75 3e                	jne    2142 <validate+0x5c>
    2104:	0f be 15 fd 3e 20 00 	movsbl 0x203efd(%rip),%edx        # 206008 <target_prefix>
    210b:	4c 8d 05 ee 32 20 00 	lea    0x2032ee(%rip),%r8        # 205400 <gets_buf>
    2112:	89 f9                	mov    %edi,%ecx
    2114:	48 8d 35 f5 15 00 00 	lea    0x15f5(%rip),%rsi        # 3710 <_IO_stdin_used+0x470>
    211b:	bf 01 00 00 00       	mov    $0x1,%edi
    2120:	b8 00 00 00 00       	mov    $0x0,%eax
    2125:	e8 36 ee ff ff       	callq  f60 <__printf_chk@plt>
    212a:	5b                   	pop    %rbx
    212b:	c3                   	retq   
    212c:	48 8d 3d bf 15 00 00 	lea    0x15bf(%rip),%rdi        # 36f2 <_IO_stdin_used+0x452>
    2133:	e8 08 ed ff ff       	callq  e40 <puts@plt>
    2138:	b8 00 00 00 00       	mov    $0x0,%eax
    213d:	e8 fc fc ff ff       	callq  1e3e <check_fail>
    2142:	89 f9                	mov    %edi,%ecx
    2144:	48 8d 35 e5 16 00 00 	lea    0x16e5(%rip),%rsi        # 3830 <_IO_stdin_used+0x590>
    214b:	bf 01 00 00 00       	mov    $0x1,%edi
    2150:	b8 00 00 00 00       	mov    $0x0,%eax
    2155:	e8 06 ee ff ff       	callq  f60 <__printf_chk@plt>
    215a:	b8 00 00 00 00       	mov    $0x0,%eax
    215f:	e8 da fc ff ff       	callq  1e3e <check_fail>
    2164:	39 3d 72 32 20 00    	cmp    %edi,0x203272(%rip)        # 2053dc <vlevel>
    216a:	74 1a                	je     2186 <validate+0xa0>
    216c:	48 8d 3d 7f 15 00 00 	lea    0x157f(%rip),%rdi        # 36f2 <_IO_stdin_used+0x452>
    2173:	e8 c8 ec ff ff       	callq  e40 <puts@plt>
    2178:	89 de                	mov    %ebx,%esi
    217a:	bf 00 00 00 00       	mov    $0x0,%edi
    217f:	e8 44 fd ff ff       	callq  1ec8 <notify_server>
    2184:	eb a4                	jmp    212a <validate+0x44>
    2186:	0f be 0d 7b 3e 20 00 	movsbl 0x203e7b(%rip),%ecx        # 206008 <target_prefix>
    218d:	89 fa                	mov    %edi,%edx
    218f:	48 8d 35 c2 16 00 00 	lea    0x16c2(%rip),%rsi        # 3858 <_IO_stdin_used+0x5b8>
    2196:	bf 01 00 00 00       	mov    $0x1,%edi
    219b:	b8 00 00 00 00       	mov    $0x0,%eax
    21a0:	e8 bb ed ff ff       	callq  f60 <__printf_chk@plt>
    21a5:	89 de                	mov    %ebx,%esi
    21a7:	bf 01 00 00 00       	mov    $0x1,%edi
    21ac:	e8 17 fd ff ff       	callq  1ec8 <notify_server>
    21b1:	e9 74 ff ff ff       	jmpq   212a <validate+0x44>

00000000000021b6 <fail>:
    21b6:	48 83 ec 08          	sub    $0x8,%rsp
    21ba:	83 3d 27 32 20 00 00 	cmpl   $0x0,0x203227(%rip)        # 2053e8 <is_checker>
    21c1:	75 11                	jne    21d4 <fail+0x1e>
    21c3:	89 fe                	mov    %edi,%esi
    21c5:	bf 00 00 00 00       	mov    $0x0,%edi
    21ca:	e8 f9 fc ff ff       	callq  1ec8 <notify_server>
    21cf:	48 83 c4 08          	add    $0x8,%rsp
    21d3:	c3                   	retq   
    21d4:	b8 00 00 00 00       	mov    $0x0,%eax
    21d9:	e8 60 fc ff ff       	callq  1e3e <check_fail>

00000000000021de <bushandler>:
    21de:	48 83 ec 08          	sub    $0x8,%rsp
    21e2:	83 3d ff 31 20 00 00 	cmpl   $0x0,0x2031ff(%rip)        # 2053e8 <is_checker>
    21e9:	74 16                	je     2201 <bushandler+0x23>
    21eb:	48 8d 3d 33 15 00 00 	lea    0x1533(%rip),%rdi        # 3725 <_IO_stdin_used+0x485>
    21f2:	e8 49 ec ff ff       	callq  e40 <puts@plt>
    21f7:	b8 00 00 00 00       	mov    $0x0,%eax
    21fc:	e8 3d fc ff ff       	callq  1e3e <check_fail>
    2201:	48 8d 3d 88 16 00 00 	lea    0x1688(%rip),%rdi        # 3890 <_IO_stdin_used+0x5f0>
    2208:	e8 33 ec ff ff       	callq  e40 <puts@plt>
    220d:	48 8d 3d 1b 15 00 00 	lea    0x151b(%rip),%rdi        # 372f <_IO_stdin_used+0x48f>
    2214:	e8 27 ec ff ff       	callq  e40 <puts@plt>
    2219:	be 00 00 00 00       	mov    $0x0,%esi
    221e:	bf 00 00 00 00       	mov    $0x0,%edi
    2223:	e8 a0 fc ff ff       	callq  1ec8 <notify_server>
    2228:	bf 01 00 00 00       	mov    $0x1,%edi
    222d:	e8 7e ed ff ff       	callq  fb0 <exit@plt>

0000000000002232 <seghandler>:
    2232:	48 83 ec 08          	sub    $0x8,%rsp
    2236:	83 3d ab 31 20 00 00 	cmpl   $0x0,0x2031ab(%rip)        # 2053e8 <is_checker>
    223d:	74 16                	je     2255 <seghandler+0x23>
    223f:	48 8d 3d ff 14 00 00 	lea    0x14ff(%rip),%rdi        # 3745 <_IO_stdin_used+0x4a5>
    2246:	e8 f5 eb ff ff       	callq  e40 <puts@plt>
    224b:	b8 00 00 00 00       	mov    $0x0,%eax
    2250:	e8 e9 fb ff ff       	callq  1e3e <check_fail>
    2255:	48 8d 3d 54 16 00 00 	lea    0x1654(%rip),%rdi        # 38b0 <_IO_stdin_used+0x610>
    225c:	e8 df eb ff ff       	callq  e40 <puts@plt>
    2261:	48 8d 3d c7 14 00 00 	lea    0x14c7(%rip),%rdi        # 372f <_IO_stdin_used+0x48f>
    2268:	e8 d3 eb ff ff       	callq  e40 <puts@plt>
    226d:	be 00 00 00 00       	mov    $0x0,%esi
    2272:	bf 00 00 00 00       	mov    $0x0,%edi
    2277:	e8 4c fc ff ff       	callq  1ec8 <notify_server>
    227c:	bf 01 00 00 00       	mov    $0x1,%edi
    2281:	e8 2a ed ff ff       	callq  fb0 <exit@plt>

0000000000002286 <illegalhandler>:
    2286:	48 83 ec 08          	sub    $0x8,%rsp
    228a:	83 3d 57 31 20 00 00 	cmpl   $0x0,0x203157(%rip)        # 2053e8 <is_checker>
    2291:	74 16                	je     22a9 <illegalhandler+0x23>
    2293:	48 8d 3d be 14 00 00 	lea    0x14be(%rip),%rdi        # 3758 <_IO_stdin_used+0x4b8>
    229a:	e8 a1 eb ff ff       	callq  e40 <puts@plt>
    229f:	b8 00 00 00 00       	mov    $0x0,%eax
    22a4:	e8 95 fb ff ff       	callq  1e3e <check_fail>
    22a9:	48 8d 3d 28 16 00 00 	lea    0x1628(%rip),%rdi        # 38d8 <_IO_stdin_used+0x638>
    22b0:	e8 8b eb ff ff       	callq  e40 <puts@plt>
    22b5:	48 8d 3d 73 14 00 00 	lea    0x1473(%rip),%rdi        # 372f <_IO_stdin_used+0x48f>
    22bc:	e8 7f eb ff ff       	callq  e40 <puts@plt>
    22c1:	be 00 00 00 00       	mov    $0x0,%esi
    22c6:	bf 00 00 00 00       	mov    $0x0,%edi
    22cb:	e8 f8 fb ff ff       	callq  1ec8 <notify_server>
    22d0:	bf 01 00 00 00       	mov    $0x1,%edi
    22d5:	e8 d6 ec ff ff       	callq  fb0 <exit@plt>

00000000000022da <sigalrmhandler>:
    22da:	48 83 ec 08          	sub    $0x8,%rsp
    22de:	83 3d 03 31 20 00 00 	cmpl   $0x0,0x203103(%rip)        # 2053e8 <is_checker>
    22e5:	74 16                	je     22fd <sigalrmhandler+0x23>
    22e7:	48 8d 3d 7e 14 00 00 	lea    0x147e(%rip),%rdi        # 376c <_IO_stdin_used+0x4cc>
    22ee:	e8 4d eb ff ff       	callq  e40 <puts@plt>
    22f3:	b8 00 00 00 00       	mov    $0x0,%eax
    22f8:	e8 41 fb ff ff       	callq  1e3e <check_fail>
    22fd:	ba 05 00 00 00       	mov    $0x5,%edx
    2302:	48 8d 35 ff 15 00 00 	lea    0x15ff(%rip),%rsi        # 3908 <_IO_stdin_used+0x668>
    2309:	bf 01 00 00 00       	mov    $0x1,%edi
    230e:	b8 00 00 00 00       	mov    $0x0,%eax
    2313:	e8 48 ec ff ff       	callq  f60 <__printf_chk@plt>
    2318:	be 00 00 00 00       	mov    $0x0,%esi
    231d:	bf 00 00 00 00       	mov    $0x0,%edi
    2322:	e8 a1 fb ff ff       	callq  1ec8 <notify_server>
    2327:	bf 01 00 00 00       	mov    $0x1,%edi
    232c:	e8 7f ec ff ff       	callq  fb0 <exit@plt>

0000000000002331 <launch>:
    2331:	55                   	push   %rbp
    2332:	48 89 e5             	mov    %rsp,%rbp
    2335:	48 83 ec 10          	sub    $0x10,%rsp
    2339:	48 89 fa             	mov    %rdi,%rdx
    233c:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    2343:	00 00 
    2345:	48 89 45 f8          	mov    %rax,-0x8(%rbp)
    2349:	31 c0                	xor    %eax,%eax
    234b:	48 8d 47 1e          	lea    0x1e(%rdi),%rax
    234f:	48 83 e0 f0          	and    $0xfffffffffffffff0,%rax
    2353:	48 29 c4             	sub    %rax,%rsp
    2356:	48 8d 7c 24 0f       	lea    0xf(%rsp),%rdi
    235b:	48 83 e7 f0          	and    $0xfffffffffffffff0,%rdi
    235f:	be f4 00 00 00       	mov    $0xf4,%esi
    2364:	e8 17 eb ff ff       	callq  e80 <memset@plt>
    2369:	48 8b 05 10 30 20 00 	mov    0x203010(%rip),%rax        # 205380 <stdin@@GLIBC_2.2.5>
    2370:	48 39 05 59 30 20 00 	cmp    %rax,0x203059(%rip)        # 2053d0 <infile>
    2377:	74 3a                	je     23b3 <launch+0x82>
    2379:	c7 05 59 30 20 00 00 	movl   $0x0,0x203059(%rip)        # 2053dc <vlevel>
    2380:	00 00 00 
    2383:	b8 00 00 00 00       	mov    $0x0,%eax
    2388:	e8 f5 f8 ff ff       	callq  1c82 <test>
    238d:	83 3d 54 30 20 00 00 	cmpl   $0x0,0x203054(%rip)        # 2053e8 <is_checker>
    2394:	75 35                	jne    23cb <launch+0x9a>
    2396:	48 8d 3d ef 13 00 00 	lea    0x13ef(%rip),%rdi        # 378c <_IO_stdin_used+0x4ec>
    239d:	e8 9e ea ff ff       	callq  e40 <puts@plt>
    23a2:	48 8b 45 f8          	mov    -0x8(%rbp),%rax
    23a6:	64 48 33 04 25 28 00 	xor    %fs:0x28,%rax
    23ad:	00 00 
    23af:	75 30                	jne    23e1 <launch+0xb0>
    23b1:	c9                   	leaveq 
    23b2:	c3                   	retq   
    23b3:	48 8d 35 ba 13 00 00 	lea    0x13ba(%rip),%rsi        # 3774 <_IO_stdin_used+0x4d4>
    23ba:	bf 01 00 00 00       	mov    $0x1,%edi
    23bf:	b8 00 00 00 00       	mov    $0x0,%eax
    23c4:	e8 97 eb ff ff       	callq  f60 <__printf_chk@plt>
    23c9:	eb ae                	jmp    2379 <launch+0x48>
    23cb:	48 8d 3d af 13 00 00 	lea    0x13af(%rip),%rdi        # 3781 <_IO_stdin_used+0x4e1>
    23d2:	e8 69 ea ff ff       	callq  e40 <puts@plt>
    23d7:	b8 00 00 00 00       	mov    $0x0,%eax
    23dc:	e8 5d fa ff ff       	callq  1e3e <check_fail>
    23e1:	e8 7a ea ff ff       	callq  e60 <__stack_chk_fail@plt>

00000000000023e6 <stable_launch>:
    23e6:	53                   	push   %rbx
    23e7:	48 89 3d da 2f 20 00 	mov    %rdi,0x202fda(%rip)        # 2053c8 <global_offset>
    23ee:	41 b9 00 00 00 00    	mov    $0x0,%r9d
    23f4:	41 b8 00 00 00 00    	mov    $0x0,%r8d
    23fa:	b9 32 01 00 00       	mov    $0x132,%ecx
    23ff:	ba 07 00 00 00       	mov    $0x7,%edx
    2404:	be 00 00 10 00       	mov    $0x100000,%esi
    2409:	bf 00 60 58 55       	mov    $0x55586000,%edi
    240e:	e8 5d ea ff ff       	callq  e70 <mmap@plt>
    2413:	48 89 c3             	mov    %rax,%rbx
    2416:	48 3d 00 60 58 55    	cmp    $0x55586000,%rax
    241c:	75 43                	jne    2461 <stable_launch+0x7b>
    241e:	48 8d 90 f8 ff 0f 00 	lea    0xffff8(%rax),%rdx
    2425:	48 89 15 e4 3b 20 00 	mov    %rdx,0x203be4(%rip)        # 206010 <stack_top>
    242c:	48 89 e0             	mov    %rsp,%rax
    242f:	48 89 d4             	mov    %rdx,%rsp
    2432:	48 89 c2             	mov    %rax,%rdx
    2435:	48 89 15 84 2f 20 00 	mov    %rdx,0x202f84(%rip)        # 2053c0 <global_save_stack>
    243c:	48 8b 3d 85 2f 20 00 	mov    0x202f85(%rip),%rdi        # 2053c8 <global_offset>
    2443:	e8 e9 fe ff ff       	callq  2331 <launch>
    2448:	48 8b 05 71 2f 20 00 	mov    0x202f71(%rip),%rax        # 2053c0 <global_save_stack>
    244f:	48 89 c4             	mov    %rax,%rsp
    2452:	be 00 00 10 00       	mov    $0x100000,%esi
    2457:	48 89 df             	mov    %rbx,%rdi
    245a:	e8 f1 ea ff ff       	callq  f50 <munmap@plt>
    245f:	5b                   	pop    %rbx
    2460:	c3                   	retq   
    2461:	be 00 00 10 00       	mov    $0x100000,%esi
    2466:	48 89 c7             	mov    %rax,%rdi
    2469:	e8 e2 ea ff ff       	callq  f50 <munmap@plt>
    246e:	b9 00 60 58 55       	mov    $0x55586000,%ecx
    2473:	48 8d 15 c6 14 00 00 	lea    0x14c6(%rip),%rdx        # 3940 <_IO_stdin_used+0x6a0>
    247a:	be 01 00 00 00       	mov    $0x1,%esi
    247f:	48 8b 3d 1a 2f 20 00 	mov    0x202f1a(%rip),%rdi        # 2053a0 <stderr@@GLIBC_2.2.5>
    2486:	b8 00 00 00 00       	mov    $0x0,%eax
    248b:	e8 40 eb ff ff       	callq  fd0 <__fprintf_chk@plt>
    2490:	bf 01 00 00 00       	mov    $0x1,%edi
    2495:	e8 16 eb ff ff       	callq  fb0 <exit@plt>

000000000000249a <rio_readinitb>:
    249a:	89 37                	mov    %esi,(%rdi)
    249c:	c7 47 04 00 00 00 00 	movl   $0x0,0x4(%rdi)
    24a3:	48 8d 47 10          	lea    0x10(%rdi),%rax
    24a7:	48 89 47 08          	mov    %rax,0x8(%rdi)
    24ab:	c3                   	retq   

00000000000024ac <sigalrm_handler>:
    24ac:	48 83 ec 08          	sub    $0x8,%rsp
    24b0:	b9 00 00 00 00       	mov    $0x0,%ecx
    24b5:	48 8d 15 c4 14 00 00 	lea    0x14c4(%rip),%rdx        # 3980 <trans_char+0x10>
    24bc:	be 01 00 00 00       	mov    $0x1,%esi
    24c1:	48 8b 3d d8 2e 20 00 	mov    0x202ed8(%rip),%rdi        # 2053a0 <stderr@@GLIBC_2.2.5>
    24c8:	b8 00 00 00 00       	mov    $0x0,%eax
    24cd:	e8 fe ea ff ff       	callq  fd0 <__fprintf_chk@plt>
    24d2:	bf 01 00 00 00       	mov    $0x1,%edi
    24d7:	e8 d4 ea ff ff       	callq  fb0 <exit@plt>

00000000000024dc <rio_writen>:
    24dc:	41 55                	push   %r13
    24de:	41 54                	push   %r12
    24e0:	55                   	push   %rbp
    24e1:	53                   	push   %rbx
    24e2:	48 83 ec 08          	sub    $0x8,%rsp
    24e6:	41 89 fc             	mov    %edi,%r12d
    24e9:	48 89 f5             	mov    %rsi,%rbp
    24ec:	49 89 d5             	mov    %rdx,%r13
    24ef:	48 89 d3             	mov    %rdx,%rbx
    24f2:	eb 06                	jmp    24fa <rio_writen+0x1e>
    24f4:	48 29 c3             	sub    %rax,%rbx
    24f7:	48 01 c5             	add    %rax,%rbp
    24fa:	48 85 db             	test   %rbx,%rbx
    24fd:	74 24                	je     2523 <rio_writen+0x47>
    24ff:	48 89 da             	mov    %rbx,%rdx
    2502:	48 89 ee             	mov    %rbp,%rsi
    2505:	44 89 e7             	mov    %r12d,%edi
    2508:	e8 43 e9 ff ff       	callq  e50 <write@plt>
    250d:	48 85 c0             	test   %rax,%rax
    2510:	7f e2                	jg     24f4 <rio_writen+0x18>
    2512:	e8 e9 e8 ff ff       	callq  e00 <__errno_location@plt>
    2517:	83 38 04             	cmpl   $0x4,(%rax)
    251a:	75 15                	jne    2531 <rio_writen+0x55>
    251c:	b8 00 00 00 00       	mov    $0x0,%eax
    2521:	eb d1                	jmp    24f4 <rio_writen+0x18>
    2523:	4c 89 e8             	mov    %r13,%rax
    2526:	48 83 c4 08          	add    $0x8,%rsp
    252a:	5b                   	pop    %rbx
    252b:	5d                   	pop    %rbp
    252c:	41 5c                	pop    %r12
    252e:	41 5d                	pop    %r13
    2530:	c3                   	retq   
    2531:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    2538:	eb ec                	jmp    2526 <rio_writen+0x4a>

000000000000253a <rio_read>:
    253a:	41 55                	push   %r13
    253c:	41 54                	push   %r12
    253e:	55                   	push   %rbp
    253f:	53                   	push   %rbx
    2540:	48 83 ec 08          	sub    $0x8,%rsp
    2544:	48 89 fb             	mov    %rdi,%rbx
    2547:	49 89 f5             	mov    %rsi,%r13
    254a:	49 89 d4             	mov    %rdx,%r12
    254d:	eb 0a                	jmp    2559 <rio_read+0x1f>
    254f:	e8 ac e8 ff ff       	callq  e00 <__errno_location@plt>
    2554:	83 38 04             	cmpl   $0x4,(%rax)
    2557:	75 5c                	jne    25b5 <rio_read+0x7b>
    2559:	8b 6b 04             	mov    0x4(%rbx),%ebp
    255c:	85 ed                	test   %ebp,%ebp
    255e:	7f 24                	jg     2584 <rio_read+0x4a>
    2560:	48 8d 6b 10          	lea    0x10(%rbx),%rbp
    2564:	8b 3b                	mov    (%rbx),%edi
    2566:	ba 00 20 00 00       	mov    $0x2000,%edx
    256b:	48 89 ee             	mov    %rbp,%rsi
    256e:	e8 3d e9 ff ff       	callq  eb0 <read@plt>
    2573:	89 43 04             	mov    %eax,0x4(%rbx)
    2576:	85 c0                	test   %eax,%eax
    2578:	78 d5                	js     254f <rio_read+0x15>
    257a:	85 c0                	test   %eax,%eax
    257c:	74 40                	je     25be <rio_read+0x84>
    257e:	48 89 6b 08          	mov    %rbp,0x8(%rbx)
    2582:	eb d5                	jmp    2559 <rio_read+0x1f>
    2584:	89 e8                	mov    %ebp,%eax
    2586:	4c 39 e0             	cmp    %r12,%rax
    2589:	72 03                	jb     258e <rio_read+0x54>
    258b:	44 89 e5             	mov    %r12d,%ebp
    258e:	4c 63 e5             	movslq %ebp,%r12
    2591:	48 8b 73 08          	mov    0x8(%rbx),%rsi
    2595:	4c 89 e2             	mov    %r12,%rdx
    2598:	4c 89 ef             	mov    %r13,%rdi
    259b:	e8 60 e9 ff ff       	callq  f00 <memcpy@plt>
    25a0:	4c 01 63 08          	add    %r12,0x8(%rbx)
    25a4:	29 6b 04             	sub    %ebp,0x4(%rbx)
    25a7:	4c 89 e0             	mov    %r12,%rax
    25aa:	48 83 c4 08          	add    $0x8,%rsp
    25ae:	5b                   	pop    %rbx
    25af:	5d                   	pop    %rbp
    25b0:	41 5c                	pop    %r12
    25b2:	41 5d                	pop    %r13
    25b4:	c3                   	retq   
    25b5:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    25bc:	eb ec                	jmp    25aa <rio_read+0x70>
    25be:	b8 00 00 00 00       	mov    $0x0,%eax
    25c3:	eb e5                	jmp    25aa <rio_read+0x70>

00000000000025c5 <rio_readlineb>:
    25c5:	41 55                	push   %r13
    25c7:	41 54                	push   %r12
    25c9:	55                   	push   %rbp
    25ca:	53                   	push   %rbx
    25cb:	48 83 ec 18          	sub    $0x18,%rsp
    25cf:	49 89 fd             	mov    %rdi,%r13
    25d2:	48 89 f5             	mov    %rsi,%rbp
    25d5:	49 89 d4             	mov    %rdx,%r12
    25d8:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    25df:	00 00 
    25e1:	48 89 44 24 08       	mov    %rax,0x8(%rsp)
    25e6:	31 c0                	xor    %eax,%eax
    25e8:	bb 01 00 00 00       	mov    $0x1,%ebx
    25ed:	4c 39 e3             	cmp    %r12,%rbx
    25f0:	73 47                	jae    2639 <rio_readlineb+0x74>
    25f2:	48 8d 74 24 07       	lea    0x7(%rsp),%rsi
    25f7:	ba 01 00 00 00       	mov    $0x1,%edx
    25fc:	4c 89 ef             	mov    %r13,%rdi
    25ff:	e8 36 ff ff ff       	callq  253a <rio_read>
    2604:	83 f8 01             	cmp    $0x1,%eax
    2607:	75 1c                	jne    2625 <rio_readlineb+0x60>
    2609:	48 8d 45 01          	lea    0x1(%rbp),%rax
    260d:	0f b6 54 24 07       	movzbl 0x7(%rsp),%edx
    2612:	88 55 00             	mov    %dl,0x0(%rbp)
    2615:	80 7c 24 07 0a       	cmpb   $0xa,0x7(%rsp)
    261a:	74 1a                	je     2636 <rio_readlineb+0x71>
    261c:	48 83 c3 01          	add    $0x1,%rbx
    2620:	48 89 c5             	mov    %rax,%rbp
    2623:	eb c8                	jmp    25ed <rio_readlineb+0x28>
    2625:	85 c0                	test   %eax,%eax
    2627:	75 32                	jne    265b <rio_readlineb+0x96>
    2629:	48 83 fb 01          	cmp    $0x1,%rbx
    262d:	75 0a                	jne    2639 <rio_readlineb+0x74>
    262f:	b8 00 00 00 00       	mov    $0x0,%eax
    2634:	eb 0a                	jmp    2640 <rio_readlineb+0x7b>
    2636:	48 89 c5             	mov    %rax,%rbp
    2639:	c6 45 00 00          	movb   $0x0,0x0(%rbp)
    263d:	48 89 d8             	mov    %rbx,%rax
    2640:	48 8b 4c 24 08       	mov    0x8(%rsp),%rcx
    2645:	64 48 33 0c 25 28 00 	xor    %fs:0x28,%rcx
    264c:	00 00 
    264e:	75 14                	jne    2664 <rio_readlineb+0x9f>
    2650:	48 83 c4 18          	add    $0x18,%rsp
    2654:	5b                   	pop    %rbx
    2655:	5d                   	pop    %rbp
    2656:	41 5c                	pop    %r12
    2658:	41 5d                	pop    %r13
    265a:	c3                   	retq   
    265b:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    2662:	eb dc                	jmp    2640 <rio_readlineb+0x7b>
    2664:	e8 f7 e7 ff ff       	callq  e60 <__stack_chk_fail@plt>

0000000000002669 <urlencode>:
    2669:	41 54                	push   %r12
    266b:	55                   	push   %rbp
    266c:	53                   	push   %rbx
    266d:	48 83 ec 10          	sub    $0x10,%rsp
    2671:	48 89 fb             	mov    %rdi,%rbx
    2674:	48 89 f5             	mov    %rsi,%rbp
    2677:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    267e:	00 00 
    2680:	48 89 44 24 08       	mov    %rax,0x8(%rsp)
    2685:	31 c0                	xor    %eax,%eax
    2687:	48 c7 c1 ff ff ff ff 	mov    $0xffffffffffffffff,%rcx
    268e:	f2 ae                	repnz scas %es:(%rdi),%al
    2690:	48 89 ce             	mov    %rcx,%rsi
    2693:	48 f7 d6             	not    %rsi
    2696:	8d 46 ff             	lea    -0x1(%rsi),%eax
    2699:	eb 0f                	jmp    26aa <urlencode+0x41>
    269b:	44 88 45 00          	mov    %r8b,0x0(%rbp)
    269f:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    26a3:	48 83 c3 01          	add    $0x1,%rbx
    26a7:	44 89 e0             	mov    %r12d,%eax
    26aa:	44 8d 60 ff          	lea    -0x1(%rax),%r12d
    26ae:	85 c0                	test   %eax,%eax
    26b0:	0f 84 a8 00 00 00    	je     275e <urlencode+0xf5>
    26b6:	44 0f b6 03          	movzbl (%rbx),%r8d
    26ba:	41 80 f8 2a          	cmp    $0x2a,%r8b
    26be:	0f 94 c2             	sete   %dl
    26c1:	41 80 f8 2d          	cmp    $0x2d,%r8b
    26c5:	0f 94 c0             	sete   %al
    26c8:	08 c2                	or     %al,%dl
    26ca:	75 cf                	jne    269b <urlencode+0x32>
    26cc:	41 80 f8 2e          	cmp    $0x2e,%r8b
    26d0:	74 c9                	je     269b <urlencode+0x32>
    26d2:	41 80 f8 5f          	cmp    $0x5f,%r8b
    26d6:	74 c3                	je     269b <urlencode+0x32>
    26d8:	41 8d 40 d0          	lea    -0x30(%r8),%eax
    26dc:	3c 09                	cmp    $0x9,%al
    26de:	76 bb                	jbe    269b <urlencode+0x32>
    26e0:	41 8d 40 bf          	lea    -0x41(%r8),%eax
    26e4:	3c 19                	cmp    $0x19,%al
    26e6:	76 b3                	jbe    269b <urlencode+0x32>
    26e8:	41 8d 40 9f          	lea    -0x61(%r8),%eax
    26ec:	3c 19                	cmp    $0x19,%al
    26ee:	76 ab                	jbe    269b <urlencode+0x32>
    26f0:	41 80 f8 20          	cmp    $0x20,%r8b
    26f4:	74 56                	je     274c <urlencode+0xe3>
    26f6:	41 8d 40 e0          	lea    -0x20(%r8),%eax
    26fa:	3c 5f                	cmp    $0x5f,%al
    26fc:	0f 96 c2             	setbe  %dl
    26ff:	41 80 f8 09          	cmp    $0x9,%r8b
    2703:	0f 94 c0             	sete   %al
    2706:	08 c2                	or     %al,%dl
    2708:	74 4f                	je     2759 <urlencode+0xf0>
    270a:	48 89 e7             	mov    %rsp,%rdi
    270d:	45 0f b6 c0          	movzbl %r8b,%r8d
    2711:	48 8d 0d 00 13 00 00 	lea    0x1300(%rip),%rcx        # 3a18 <trans_char+0xa8>
    2718:	ba 08 00 00 00       	mov    $0x8,%edx
    271d:	be 01 00 00 00       	mov    $0x1,%esi
    2722:	b8 00 00 00 00       	mov    $0x0,%eax
    2727:	e8 b4 e8 ff ff       	callq  fe0 <__sprintf_chk@plt>
    272c:	0f b6 04 24          	movzbl (%rsp),%eax
    2730:	88 45 00             	mov    %al,0x0(%rbp)
    2733:	0f b6 44 24 01       	movzbl 0x1(%rsp),%eax
    2738:	88 45 01             	mov    %al,0x1(%rbp)
    273b:	0f b6 44 24 02       	movzbl 0x2(%rsp),%eax
    2740:	88 45 02             	mov    %al,0x2(%rbp)
    2743:	48 8d 6d 03          	lea    0x3(%rbp),%rbp
    2747:	e9 57 ff ff ff       	jmpq   26a3 <urlencode+0x3a>
    274c:	c6 45 00 2b          	movb   $0x2b,0x0(%rbp)
    2750:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    2754:	e9 4a ff ff ff       	jmpq   26a3 <urlencode+0x3a>
    2759:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    275e:	48 8b 74 24 08       	mov    0x8(%rsp),%rsi
    2763:	64 48 33 34 25 28 00 	xor    %fs:0x28,%rsi
    276a:	00 00 
    276c:	75 09                	jne    2777 <urlencode+0x10e>
    276e:	48 83 c4 10          	add    $0x10,%rsp
    2772:	5b                   	pop    %rbx
    2773:	5d                   	pop    %rbp
    2774:	41 5c                	pop    %r12
    2776:	c3                   	retq   
    2777:	e8 e4 e6 ff ff       	callq  e60 <__stack_chk_fail@plt>

000000000000277c <submitr>:
    277c:	41 57                	push   %r15
    277e:	41 56                	push   %r14
    2780:	41 55                	push   %r13
    2782:	41 54                	push   %r12
    2784:	55                   	push   %rbp
    2785:	53                   	push   %rbx
    2786:	48 81 ec 68 a0 00 00 	sub    $0xa068,%rsp
    278d:	49 89 fd             	mov    %rdi,%r13
    2790:	89 74 24 14          	mov    %esi,0x14(%rsp)
    2794:	49 89 d7             	mov    %rdx,%r15
    2797:	48 89 4c 24 08       	mov    %rcx,0x8(%rsp)
    279c:	4c 89 44 24 18       	mov    %r8,0x18(%rsp)
    27a1:	4d 89 ce             	mov    %r9,%r14
    27a4:	48 8b ac 24 a0 a0 00 	mov    0xa0a0(%rsp),%rbp
    27ab:	00 
    27ac:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    27b3:	00 00 
    27b5:	48 89 84 24 58 a0 00 	mov    %rax,0xa058(%rsp)
    27bc:	00 
    27bd:	31 c0                	xor    %eax,%eax
    27bf:	c7 44 24 2c 00 00 00 	movl   $0x0,0x2c(%rsp)
    27c6:	00 
    27c7:	ba 00 00 00 00       	mov    $0x0,%edx
    27cc:	be 01 00 00 00       	mov    $0x1,%esi
    27d1:	bf 02 00 00 00       	mov    $0x2,%edi
    27d6:	e8 15 e8 ff ff       	callq  ff0 <socket@plt>
    27db:	85 c0                	test   %eax,%eax
    27dd:	0f 88 a9 02 00 00    	js     2a8c <submitr+0x310>
    27e3:	89 c3                	mov    %eax,%ebx
    27e5:	4c 89 ef             	mov    %r13,%rdi
    27e8:	e8 e3 e6 ff ff       	callq  ed0 <gethostbyname@plt>
    27ed:	48 85 c0             	test   %rax,%rax
    27f0:	0f 84 e2 02 00 00    	je     2ad8 <submitr+0x35c>
    27f6:	4c 8d 64 24 30       	lea    0x30(%rsp),%r12
    27fb:	48 c7 44 24 32 00 00 	movq   $0x0,0x32(%rsp)
    2802:	00 00 
    2804:	c7 44 24 3a 00 00 00 	movl   $0x0,0x3a(%rsp)
    280b:	00 
    280c:	66 c7 44 24 3e 00 00 	movw   $0x0,0x3e(%rsp)
    2813:	66 c7 44 24 30 02 00 	movw   $0x2,0x30(%rsp)
    281a:	48 63 50 14          	movslq 0x14(%rax),%rdx
    281e:	48 8b 40 18          	mov    0x18(%rax),%rax
    2822:	48 8b 30             	mov    (%rax),%rsi
    2825:	48 8d 7c 24 34       	lea    0x34(%rsp),%rdi
    282a:	b9 0c 00 00 00       	mov    $0xc,%ecx
    282f:	e8 ac e6 ff ff       	callq  ee0 <__memmove_chk@plt>
    2834:	0f b7 44 24 14       	movzwl 0x14(%rsp),%eax
    2839:	66 c1 c8 08          	ror    $0x8,%ax
    283d:	66 89 44 24 32       	mov    %ax,0x32(%rsp)
    2842:	ba 10 00 00 00       	mov    $0x10,%edx
    2847:	4c 89 e6             	mov    %r12,%rsi
    284a:	89 df                	mov    %ebx,%edi
    284c:	e8 6f e7 ff ff       	callq  fc0 <connect@plt>
    2851:	85 c0                	test   %eax,%eax
    2853:	0f 88 e7 02 00 00    	js     2b40 <submitr+0x3c4>
    2859:	48 c7 c6 ff ff ff ff 	mov    $0xffffffffffffffff,%rsi
    2860:	b8 00 00 00 00       	mov    $0x0,%eax
    2865:	48 89 f1             	mov    %rsi,%rcx
    2868:	4c 89 f7             	mov    %r14,%rdi
    286b:	f2 ae                	repnz scas %es:(%rdi),%al
    286d:	48 89 ca             	mov    %rcx,%rdx
    2870:	48 f7 d2             	not    %rdx
    2873:	48 89 f1             	mov    %rsi,%rcx
    2876:	4c 89 ff             	mov    %r15,%rdi
    2879:	f2 ae                	repnz scas %es:(%rdi),%al
    287b:	48 f7 d1             	not    %rcx
    287e:	49 89 c8             	mov    %rcx,%r8
    2881:	48 89 f1             	mov    %rsi,%rcx
    2884:	48 8b 7c 24 08       	mov    0x8(%rsp),%rdi
    2889:	f2 ae                	repnz scas %es:(%rdi),%al
    288b:	48 f7 d1             	not    %rcx
    288e:	4d 8d 44 08 fe       	lea    -0x2(%r8,%rcx,1),%r8
    2893:	48 89 f1             	mov    %rsi,%rcx
    2896:	48 8b 7c 24 18       	mov    0x18(%rsp),%rdi
    289b:	f2 ae                	repnz scas %es:(%rdi),%al
    289d:	48 89 c8             	mov    %rcx,%rax
    28a0:	48 f7 d0             	not    %rax
    28a3:	49 8d 4c 00 ff       	lea    -0x1(%r8,%rax,1),%rcx
    28a8:	48 8d 44 52 fd       	lea    -0x3(%rdx,%rdx,2),%rax
    28ad:	48 8d 84 01 80 00 00 	lea    0x80(%rcx,%rax,1),%rax
    28b4:	00 
    28b5:	48 3d 00 20 00 00    	cmp    $0x2000,%rax
    28bb:	0f 87 d9 02 00 00    	ja     2b9a <submitr+0x41e>
    28c1:	48 8d b4 24 50 40 00 	lea    0x4050(%rsp),%rsi
    28c8:	00 
    28c9:	b9 00 04 00 00       	mov    $0x400,%ecx
    28ce:	b8 00 00 00 00       	mov    $0x0,%eax
    28d3:	48 89 f7             	mov    %rsi,%rdi
    28d6:	f3 48 ab             	rep stos %rax,%es:(%rdi)
    28d9:	4c 89 f7             	mov    %r14,%rdi
    28dc:	e8 88 fd ff ff       	callq  2669 <urlencode>
    28e1:	85 c0                	test   %eax,%eax
    28e3:	0f 88 24 03 00 00    	js     2c0d <submitr+0x491>
    28e9:	4c 8d a4 24 50 20 00 	lea    0x2050(%rsp),%r12
    28f0:	00 
    28f1:	41 55                	push   %r13
    28f3:	48 8d 84 24 58 40 00 	lea    0x4058(%rsp),%rax
    28fa:	00 
    28fb:	50                   	push   %rax
    28fc:	4d 89 f9             	mov    %r15,%r9
    28ff:	4c 8b 44 24 18       	mov    0x18(%rsp),%r8
    2904:	48 8d 0d 9d 10 00 00 	lea    0x109d(%rip),%rcx        # 39a8 <trans_char+0x38>
    290b:	ba 00 20 00 00       	mov    $0x2000,%edx
    2910:	be 01 00 00 00       	mov    $0x1,%esi
    2915:	4c 89 e7             	mov    %r12,%rdi
    2918:	b8 00 00 00 00       	mov    $0x0,%eax
    291d:	e8 be e6 ff ff       	callq  fe0 <__sprintf_chk@plt>
    2922:	48 c7 c1 ff ff ff ff 	mov    $0xffffffffffffffff,%rcx
    2929:	b8 00 00 00 00       	mov    $0x0,%eax
    292e:	4c 89 e7             	mov    %r12,%rdi
    2931:	f2 ae                	repnz scas %es:(%rdi),%al
    2933:	48 89 ca             	mov    %rcx,%rdx
    2936:	48 f7 d2             	not    %rdx
    2939:	48 8d 52 ff          	lea    -0x1(%rdx),%rdx
    293d:	4c 89 e6             	mov    %r12,%rsi
    2940:	89 df                	mov    %ebx,%edi
    2942:	e8 95 fb ff ff       	callq  24dc <rio_writen>
    2947:	48 83 c4 10          	add    $0x10,%rsp
    294b:	48 85 c0             	test   %rax,%rax
    294e:	0f 88 44 03 00 00    	js     2c98 <submitr+0x51c>
    2954:	4c 8d 64 24 40       	lea    0x40(%rsp),%r12
    2959:	89 de                	mov    %ebx,%esi
    295b:	4c 89 e7             	mov    %r12,%rdi
    295e:	e8 37 fb ff ff       	callq  249a <rio_readinitb>
    2963:	48 8d b4 24 50 20 00 	lea    0x2050(%rsp),%rsi
    296a:	00 
    296b:	ba 00 20 00 00       	mov    $0x2000,%edx
    2970:	4c 89 e7             	mov    %r12,%rdi
    2973:	e8 4d fc ff ff       	callq  25c5 <rio_readlineb>
    2978:	48 85 c0             	test   %rax,%rax
    297b:	0f 8e 86 03 00 00    	jle    2d07 <submitr+0x58b>
    2981:	48 8d 4c 24 2c       	lea    0x2c(%rsp),%rcx
    2986:	48 8d 94 24 50 60 00 	lea    0x6050(%rsp),%rdx
    298d:	00 
    298e:	48 8d bc 24 50 20 00 	lea    0x2050(%rsp),%rdi
    2995:	00 
    2996:	4c 8d 84 24 50 80 00 	lea    0x8050(%rsp),%r8
    299d:	00 
    299e:	48 8d 35 7a 10 00 00 	lea    0x107a(%rip),%rsi        # 3a1f <trans_char+0xaf>
    29a5:	b8 00 00 00 00       	mov    $0x0,%eax
    29aa:	e8 91 e5 ff ff       	callq  f40 <__isoc99_sscanf@plt>
    29af:	48 8d b4 24 50 20 00 	lea    0x2050(%rsp),%rsi
    29b6:	00 
    29b7:	b9 03 00 00 00       	mov    $0x3,%ecx
    29bc:	48 8d 3d 73 10 00 00 	lea    0x1073(%rip),%rdi        # 3a36 <trans_char+0xc6>
    29c3:	f3 a6                	repz cmpsb %es:(%rdi),%ds:(%rsi)
    29c5:	0f 97 c0             	seta   %al
    29c8:	1c 00                	sbb    $0x0,%al
    29ca:	84 c0                	test   %al,%al
    29cc:	0f 84 b3 03 00 00    	je     2d85 <submitr+0x609>
    29d2:	48 8d b4 24 50 20 00 	lea    0x2050(%rsp),%rsi
    29d9:	00 
    29da:	48 8d 7c 24 40       	lea    0x40(%rsp),%rdi
    29df:	ba 00 20 00 00       	mov    $0x2000,%edx
    29e4:	e8 dc fb ff ff       	callq  25c5 <rio_readlineb>
    29e9:	48 85 c0             	test   %rax,%rax
    29ec:	7f c1                	jg     29af <submitr+0x233>
    29ee:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    29f5:	3a 20 43 
    29f8:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    29ff:	20 75 6e 
    2a02:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2a06:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2a0a:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2a11:	74 6f 20 
    2a14:	48 ba 72 65 61 64 20 	movabs $0x6165682064616572,%rdx
    2a1b:	68 65 61 
    2a1e:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2a22:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2a26:	48 b8 64 65 72 73 20 	movabs $0x6f72662073726564,%rax
    2a2d:	66 72 6f 
    2a30:	48 ba 6d 20 74 68 65 	movabs $0x657220656874206d,%rdx
    2a37:	20 72 65 
    2a3a:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2a3e:	48 89 55 28          	mov    %rdx,0x28(%rbp)
    2a42:	48 b8 73 75 6c 74 20 	movabs $0x72657320746c7573,%rax
    2a49:	73 65 72 
    2a4c:	48 89 45 30          	mov    %rax,0x30(%rbp)
    2a50:	c7 45 38 76 65 72 00 	movl   $0x726576,0x38(%rbp)
    2a57:	89 df                	mov    %ebx,%edi
    2a59:	e8 42 e4 ff ff       	callq  ea0 <close@plt>
    2a5e:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2a63:	48 8b 9c 24 58 a0 00 	mov    0xa058(%rsp),%rbx
    2a6a:	00 
    2a6b:	64 48 33 1c 25 28 00 	xor    %fs:0x28,%rbx
    2a72:	00 00 
    2a74:	0f 85 7e 04 00 00    	jne    2ef8 <submitr+0x77c>
    2a7a:	48 81 c4 68 a0 00 00 	add    $0xa068,%rsp
    2a81:	5b                   	pop    %rbx
    2a82:	5d                   	pop    %rbp
    2a83:	41 5c                	pop    %r12
    2a85:	41 5d                	pop    %r13
    2a87:	41 5e                	pop    %r14
    2a89:	41 5f                	pop    %r15
    2a8b:	c3                   	retq   
    2a8c:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2a93:	3a 20 43 
    2a96:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2a9d:	20 75 6e 
    2aa0:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2aa4:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2aa8:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2aaf:	74 6f 20 
    2ab2:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    2ab9:	65 20 73 
    2abc:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2ac0:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2ac4:	c7 45 20 6f 63 6b 65 	movl   $0x656b636f,0x20(%rbp)
    2acb:	66 c7 45 24 74 00    	movw   $0x74,0x24(%rbp)
    2ad1:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2ad6:	eb 8b                	jmp    2a63 <submitr+0x2e7>
    2ad8:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    2adf:	3a 20 44 
    2ae2:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    2ae9:	20 75 6e 
    2aec:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2af0:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2af4:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2afb:	74 6f 20 
    2afe:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    2b05:	76 65 20 
    2b08:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2b0c:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2b10:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    2b17:	72 20 61 
    2b1a:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2b1e:	c7 45 28 64 64 72 65 	movl   $0x65726464,0x28(%rbp)
    2b25:	66 c7 45 2c 73 73    	movw   $0x7373,0x2c(%rbp)
    2b2b:	c6 45 2e 00          	movb   $0x0,0x2e(%rbp)
    2b2f:	89 df                	mov    %ebx,%edi
    2b31:	e8 6a e3 ff ff       	callq  ea0 <close@plt>
    2b36:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2b3b:	e9 23 ff ff ff       	jmpq   2a63 <submitr+0x2e7>
    2b40:	48 b8 45 72 72 6f 72 	movabs $0x55203a726f727245,%rax
    2b47:	3a 20 55 
    2b4a:	48 ba 6e 61 62 6c 65 	movabs $0x6f7420656c62616e,%rdx
    2b51:	20 74 6f 
    2b54:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2b58:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2b5c:	48 b8 20 63 6f 6e 6e 	movabs $0x7463656e6e6f6320,%rax
    2b63:	65 63 74 
    2b66:	48 ba 20 74 6f 20 74 	movabs $0x20656874206f7420,%rdx
    2b6d:	68 65 20 
    2b70:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2b74:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2b78:	c7 45 20 73 65 72 76 	movl   $0x76726573,0x20(%rbp)
    2b7f:	66 c7 45 24 65 72    	movw   $0x7265,0x24(%rbp)
    2b85:	c6 45 26 00          	movb   $0x0,0x26(%rbp)
    2b89:	89 df                	mov    %ebx,%edi
    2b8b:	e8 10 e3 ff ff       	callq  ea0 <close@plt>
    2b90:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2b95:	e9 c9 fe ff ff       	jmpq   2a63 <submitr+0x2e7>
    2b9a:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    2ba1:	3a 20 52 
    2ba4:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    2bab:	20 73 74 
    2bae:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2bb2:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2bb6:	48 b8 72 69 6e 67 20 	movabs $0x6f6f7420676e6972,%rax
    2bbd:	74 6f 6f 
    2bc0:	48 ba 20 6c 61 72 67 	movabs $0x202e656772616c20,%rdx
    2bc7:	65 2e 20 
    2bca:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2bce:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2bd2:	48 b8 49 6e 63 72 65 	movabs $0x6573616572636e49,%rax
    2bd9:	61 73 65 
    2bdc:	48 ba 20 53 55 42 4d 	movabs $0x5254494d42555320,%rdx
    2be3:	49 54 52 
    2be6:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2bea:	48 89 55 28          	mov    %rdx,0x28(%rbp)
    2bee:	48 b8 5f 4d 41 58 42 	movabs $0x46554258414d5f,%rax
    2bf5:	55 46 00 
    2bf8:	48 89 45 30          	mov    %rax,0x30(%rbp)
    2bfc:	89 df                	mov    %ebx,%edi
    2bfe:	e8 9d e2 ff ff       	callq  ea0 <close@plt>
    2c03:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2c08:	e9 56 fe ff ff       	jmpq   2a63 <submitr+0x2e7>
    2c0d:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    2c14:	3a 20 52 
    2c17:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    2c1e:	20 73 74 
    2c21:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2c25:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2c29:	48 b8 72 69 6e 67 20 	movabs $0x6e6f6320676e6972,%rax
    2c30:	63 6f 6e 
    2c33:	48 ba 74 61 69 6e 73 	movabs $0x6e6120736e696174,%rdx
    2c3a:	20 61 6e 
    2c3d:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2c41:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2c45:	48 b8 20 69 6c 6c 65 	movabs $0x6c6167656c6c6920,%rax
    2c4c:	67 61 6c 
    2c4f:	48 ba 20 6f 72 20 75 	movabs $0x72706e7520726f20,%rdx
    2c56:	6e 70 72 
    2c59:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2c5d:	48 89 55 28          	mov    %rdx,0x28(%rbp)
    2c61:	48 b8 69 6e 74 61 62 	movabs $0x20656c6261746e69,%rax
    2c68:	6c 65 20 
    2c6b:	48 ba 63 68 61 72 61 	movabs $0x6574636172616863,%rdx
    2c72:	63 74 65 
    2c75:	48 89 45 30          	mov    %rax,0x30(%rbp)
    2c79:	48 89 55 38          	mov    %rdx,0x38(%rbp)
    2c7d:	66 c7 45 40 72 2e    	movw   $0x2e72,0x40(%rbp)
    2c83:	c6 45 42 00          	movb   $0x0,0x42(%rbp)
    2c87:	89 df                	mov    %ebx,%edi
    2c89:	e8 12 e2 ff ff       	callq  ea0 <close@plt>
    2c8e:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2c93:	e9 cb fd ff ff       	jmpq   2a63 <submitr+0x2e7>
    2c98:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2c9f:	3a 20 43 
    2ca2:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2ca9:	20 75 6e 
    2cac:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2cb0:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2cb4:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2cbb:	74 6f 20 
    2cbe:	48 ba 77 72 69 74 65 	movabs $0x6f74206574697277,%rdx
    2cc5:	20 74 6f 
    2cc8:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2ccc:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2cd0:	48 b8 20 74 68 65 20 	movabs $0x7365722065687420,%rax
    2cd7:	72 65 73 
    2cda:	48 ba 75 6c 74 20 73 	movabs $0x7672657320746c75,%rdx
    2ce1:	65 72 76 
    2ce4:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2ce8:	48 89 55 28          	mov    %rdx,0x28(%rbp)
    2cec:	66 c7 45 30 65 72    	movw   $0x7265,0x30(%rbp)
    2cf2:	c6 45 32 00          	movb   $0x0,0x32(%rbp)
    2cf6:	89 df                	mov    %ebx,%edi
    2cf8:	e8 a3 e1 ff ff       	callq  ea0 <close@plt>
    2cfd:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2d02:	e9 5c fd ff ff       	jmpq   2a63 <submitr+0x2e7>
    2d07:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2d0e:	3a 20 43 
    2d11:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2d18:	20 75 6e 
    2d1b:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2d1f:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2d23:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2d2a:	74 6f 20 
    2d2d:	48 ba 72 65 61 64 20 	movabs $0x7269662064616572,%rdx
    2d34:	66 69 72 
    2d37:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2d3b:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2d3f:	48 b8 73 74 20 68 65 	movabs $0x6564616568207473,%rax
    2d46:	61 64 65 
    2d49:	48 ba 72 20 66 72 6f 	movabs $0x72206d6f72662072,%rdx
    2d50:	6d 20 72 
    2d53:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2d57:	48 89 55 28          	mov    %rdx,0x28(%rbp)
    2d5b:	48 b8 65 73 75 6c 74 	movabs $0x657320746c757365,%rax
    2d62:	20 73 65 
    2d65:	48 89 45 30          	mov    %rax,0x30(%rbp)
    2d69:	c7 45 38 72 76 65 72 	movl   $0x72657672,0x38(%rbp)
    2d70:	c6 45 3c 00          	movb   $0x0,0x3c(%rbp)
    2d74:	89 df                	mov    %ebx,%edi
    2d76:	e8 25 e1 ff ff       	callq  ea0 <close@plt>
    2d7b:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2d80:	e9 de fc ff ff       	jmpq   2a63 <submitr+0x2e7>
    2d85:	48 8d b4 24 50 20 00 	lea    0x2050(%rsp),%rsi
    2d8c:	00 
    2d8d:	48 8d 7c 24 40       	lea    0x40(%rsp),%rdi
    2d92:	ba 00 20 00 00       	mov    $0x2000,%edx
    2d97:	e8 29 f8 ff ff       	callq  25c5 <rio_readlineb>
    2d9c:	48 85 c0             	test   %rax,%rax
    2d9f:	0f 8e 96 00 00 00    	jle    2e3b <submitr+0x6bf>
    2da5:	44 8b 44 24 2c       	mov    0x2c(%rsp),%r8d
    2daa:	41 81 f8 c8 00 00 00 	cmp    $0xc8,%r8d
    2db1:	0f 85 08 01 00 00    	jne    2ebf <submitr+0x743>
    2db7:	48 8d b4 24 50 20 00 	lea    0x2050(%rsp),%rsi
    2dbe:	00 
    2dbf:	48 89 ef             	mov    %rbp,%rdi
    2dc2:	e8 69 e0 ff ff       	callq  e30 <strcpy@plt>
    2dc7:	89 df                	mov    %ebx,%edi
    2dc9:	e8 d2 e0 ff ff       	callq  ea0 <close@plt>
    2dce:	b9 04 00 00 00       	mov    $0x4,%ecx
    2dd3:	48 8d 3d 56 0c 00 00 	lea    0xc56(%rip),%rdi        # 3a30 <trans_char+0xc0>
    2dda:	48 89 ee             	mov    %rbp,%rsi
    2ddd:	f3 a6                	repz cmpsb %es:(%rdi),%ds:(%rsi)
    2ddf:	0f 97 c0             	seta   %al
    2de2:	1c 00                	sbb    $0x0,%al
    2de4:	0f be c0             	movsbl %al,%eax
    2de7:	85 c0                	test   %eax,%eax
    2de9:	0f 84 74 fc ff ff    	je     2a63 <submitr+0x2e7>
    2def:	b9 05 00 00 00       	mov    $0x5,%ecx
    2df4:	48 8d 3d 39 0c 00 00 	lea    0xc39(%rip),%rdi        # 3a34 <trans_char+0xc4>
    2dfb:	48 89 ee             	mov    %rbp,%rsi
    2dfe:	f3 a6                	repz cmpsb %es:(%rdi),%ds:(%rsi)
    2e00:	0f 97 c0             	seta   %al
    2e03:	1c 00                	sbb    $0x0,%al
    2e05:	0f be c0             	movsbl %al,%eax
    2e08:	85 c0                	test   %eax,%eax
    2e0a:	0f 84 53 fc ff ff    	je     2a63 <submitr+0x2e7>
    2e10:	b9 03 00 00 00       	mov    $0x3,%ecx
    2e15:	48 8d 3d 1d 0c 00 00 	lea    0xc1d(%rip),%rdi        # 3a39 <trans_char+0xc9>
    2e1c:	48 89 ee             	mov    %rbp,%rsi
    2e1f:	f3 a6                	repz cmpsb %es:(%rdi),%ds:(%rsi)
    2e21:	0f 97 c0             	seta   %al
    2e24:	1c 00                	sbb    $0x0,%al
    2e26:	0f be c0             	movsbl %al,%eax
    2e29:	85 c0                	test   %eax,%eax
    2e2b:	0f 84 32 fc ff ff    	je     2a63 <submitr+0x2e7>
    2e31:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2e36:	e9 28 fc ff ff       	jmpq   2a63 <submitr+0x2e7>
    2e3b:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2e42:	3a 20 43 
    2e45:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2e4c:	20 75 6e 
    2e4f:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2e53:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2e57:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2e5e:	74 6f 20 
    2e61:	48 ba 72 65 61 64 20 	movabs $0x6174732064616572,%rdx
    2e68:	73 74 61 
    2e6b:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2e6f:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2e73:	48 b8 74 75 73 20 6d 	movabs $0x7373656d20737574,%rax
    2e7a:	65 73 73 
    2e7d:	48 ba 61 67 65 20 66 	movabs $0x6d6f726620656761,%rdx
    2e84:	72 6f 6d 
    2e87:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2e8b:	48 89 55 28          	mov    %rdx,0x28(%rbp)
    2e8f:	48 b8 20 72 65 73 75 	movabs $0x20746c7573657220,%rax
    2e96:	6c 74 20 
    2e99:	48 89 45 30          	mov    %rax,0x30(%rbp)
    2e9d:	c7 45 38 73 65 72 76 	movl   $0x76726573,0x38(%rbp)
    2ea4:	66 c7 45 3c 65 72    	movw   $0x7265,0x3c(%rbp)
    2eaa:	c6 45 3e 00          	movb   $0x0,0x3e(%rbp)
    2eae:	89 df                	mov    %ebx,%edi
    2eb0:	e8 eb df ff ff       	callq  ea0 <close@plt>
    2eb5:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2eba:	e9 a4 fb ff ff       	jmpq   2a63 <submitr+0x2e7>
    2ebf:	4c 8d 8c 24 50 80 00 	lea    0x8050(%rsp),%r9
    2ec6:	00 
    2ec7:	48 8d 0d 1a 0b 00 00 	lea    0xb1a(%rip),%rcx        # 39e8 <trans_char+0x78>
    2ece:	48 c7 c2 ff ff ff ff 	mov    $0xffffffffffffffff,%rdx
    2ed5:	be 01 00 00 00       	mov    $0x1,%esi
    2eda:	48 89 ef             	mov    %rbp,%rdi
    2edd:	b8 00 00 00 00       	mov    $0x0,%eax
    2ee2:	e8 f9 e0 ff ff       	callq  fe0 <__sprintf_chk@plt>
    2ee7:	89 df                	mov    %ebx,%edi
    2ee9:	e8 b2 df ff ff       	callq  ea0 <close@plt>
    2eee:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2ef3:	e9 6b fb ff ff       	jmpq   2a63 <submitr+0x2e7>
    2ef8:	e8 63 df ff ff       	callq  e60 <__stack_chk_fail@plt>

0000000000002efd <init_timeout>:
    2efd:	85 ff                	test   %edi,%edi
    2eff:	74 28                	je     2f29 <init_timeout+0x2c>
    2f01:	53                   	push   %rbx
    2f02:	89 fb                	mov    %edi,%ebx
    2f04:	85 ff                	test   %edi,%edi
    2f06:	78 1a                	js     2f22 <init_timeout+0x25>
    2f08:	48 8d 35 9d f5 ff ff 	lea    -0xa63(%rip),%rsi        # 24ac <sigalrm_handler>
    2f0f:	bf 0e 00 00 00       	mov    $0xe,%edi
    2f14:	e8 a7 df ff ff       	callq  ec0 <signal@plt>
    2f19:	89 df                	mov    %ebx,%edi
    2f1b:	e8 70 df ff ff       	callq  e90 <alarm@plt>
    2f20:	5b                   	pop    %rbx
    2f21:	c3                   	retq   
    2f22:	bb 00 00 00 00       	mov    $0x0,%ebx
    2f27:	eb df                	jmp    2f08 <init_timeout+0xb>
    2f29:	f3 c3                	repz retq 

0000000000002f2b <init_driver>:
    2f2b:	41 54                	push   %r12
    2f2d:	55                   	push   %rbp
    2f2e:	53                   	push   %rbx
    2f2f:	48 83 ec 20          	sub    $0x20,%rsp
    2f33:	49 89 fc             	mov    %rdi,%r12
    2f36:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    2f3d:	00 00 
    2f3f:	48 89 44 24 18       	mov    %rax,0x18(%rsp)
    2f44:	31 c0                	xor    %eax,%eax
    2f46:	be 01 00 00 00       	mov    $0x1,%esi
    2f4b:	bf 0d 00 00 00       	mov    $0xd,%edi
    2f50:	e8 6b df ff ff       	callq  ec0 <signal@plt>
    2f55:	be 01 00 00 00       	mov    $0x1,%esi
    2f5a:	bf 1d 00 00 00       	mov    $0x1d,%edi
    2f5f:	e8 5c df ff ff       	callq  ec0 <signal@plt>
    2f64:	be 01 00 00 00       	mov    $0x1,%esi
    2f69:	bf 1d 00 00 00       	mov    $0x1d,%edi
    2f6e:	e8 4d df ff ff       	callq  ec0 <signal@plt>
    2f73:	ba 00 00 00 00       	mov    $0x0,%edx
    2f78:	be 01 00 00 00       	mov    $0x1,%esi
    2f7d:	bf 02 00 00 00       	mov    $0x2,%edi
    2f82:	e8 69 e0 ff ff       	callq  ff0 <socket@plt>
    2f87:	85 c0                	test   %eax,%eax
    2f89:	0f 88 a3 00 00 00    	js     3032 <init_driver+0x107>
    2f8f:	89 c3                	mov    %eax,%ebx
    2f91:	48 8d 3d a4 0a 00 00 	lea    0xaa4(%rip),%rdi        # 3a3c <trans_char+0xcc>
    2f98:	e8 33 df ff ff       	callq  ed0 <gethostbyname@plt>
    2f9d:	48 85 c0             	test   %rax,%rax
    2fa0:	0f 84 df 00 00 00    	je     3085 <init_driver+0x15a>
    2fa6:	48 89 e5             	mov    %rsp,%rbp
    2fa9:	48 c7 44 24 02 00 00 	movq   $0x0,0x2(%rsp)
    2fb0:	00 00 
    2fb2:	c7 45 0a 00 00 00 00 	movl   $0x0,0xa(%rbp)
    2fb9:	66 c7 45 0e 00 00    	movw   $0x0,0xe(%rbp)
    2fbf:	66 c7 04 24 02 00    	movw   $0x2,(%rsp)
    2fc5:	48 63 50 14          	movslq 0x14(%rax),%rdx
    2fc9:	48 8b 40 18          	mov    0x18(%rax),%rax
    2fcd:	48 8b 30             	mov    (%rax),%rsi
    2fd0:	48 8d 7d 04          	lea    0x4(%rbp),%rdi
    2fd4:	b9 0c 00 00 00       	mov    $0xc,%ecx
    2fd9:	e8 02 df ff ff       	callq  ee0 <__memmove_chk@plt>
    2fde:	66 c7 44 24 02 3c 9a 	movw   $0x9a3c,0x2(%rsp)
    2fe5:	ba 10 00 00 00       	mov    $0x10,%edx
    2fea:	48 89 ee             	mov    %rbp,%rsi
    2fed:	89 df                	mov    %ebx,%edi
    2fef:	e8 cc df ff ff       	callq  fc0 <connect@plt>
    2ff4:	85 c0                	test   %eax,%eax
    2ff6:	0f 88 fb 00 00 00    	js     30f7 <init_driver+0x1cc>
    2ffc:	89 df                	mov    %ebx,%edi
    2ffe:	e8 9d de ff ff       	callq  ea0 <close@plt>
    3003:	66 41 c7 04 24 4f 4b 	movw   $0x4b4f,(%r12)
    300a:	41 c6 44 24 02 00    	movb   $0x0,0x2(%r12)
    3010:	b8 00 00 00 00       	mov    $0x0,%eax
    3015:	48 8b 4c 24 18       	mov    0x18(%rsp),%rcx
    301a:	64 48 33 0c 25 28 00 	xor    %fs:0x28,%rcx
    3021:	00 00 
    3023:	0f 85 28 01 00 00    	jne    3151 <init_driver+0x226>
    3029:	48 83 c4 20          	add    $0x20,%rsp
    302e:	5d                   	pop    %rbp
    302f:	41 5c                	pop    %r12
    3031:	c3                   	retq   
    3032:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    3039:	3a 20 43 
    303c:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    3043:	20 75 6e 
    3046:	49 89 04 24          	mov    %rax,(%r12)
    304a:	49 89 54 24 08       	mov    %rdx,0x8(%r12)
    304f:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    3056:	74 6f 20 
    3059:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    3060:	65 20 73 
    3063:	49 89 44 24 10       	mov    %rax,0x10(%r12)
    3068:	49 89 54 24 18       	mov    %rdx,0x18(%r12)
    306d:	41 c7 44 24 20 6f 63 	movl   $0x656b636f,0x20(%r12)
    3074:	6b 65 
    3076:	66 41 c7 44 24 24 74 	movw   $0x74,0x24(%r12)
    307d:	00 
    307e:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    3083:	eb 90                	jmp    3015 <init_driver+0xea>
    3085:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    308c:	3a 20 44 
    308f:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    3096:	20 75 6e 
    3099:	49 89 04 24          	mov    %rax,(%r12)
    309d:	49 89 54 24 08       	mov    %rdx,0x8(%r12)
    30a2:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    30a9:	74 6f 20 
    30ac:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    30b3:	76 65 20 
    30b6:	49 89 44 24 10       	mov    %rax,0x10(%r12)
    30bb:	49 89 54 24 18       	mov    %rdx,0x18(%r12)
    30c0:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    30c7:	72 20 61 
    30ca:	49 89 44 24 20       	mov    %rax,0x20(%r12)
    30cf:	41 c7 44 24 28 64 64 	movl   $0x65726464,0x28(%r12)
    30d6:	72 65 
    30d8:	66 41 c7 44 24 2c 73 	movw   $0x7373,0x2c(%r12)
    30df:	73 
    30e0:	41 c6 44 24 2e 00    	movb   $0x0,0x2e(%r12)
    30e6:	89 df                	mov    %ebx,%edi
    30e8:	e8 b3 dd ff ff       	callq  ea0 <close@plt>
    30ed:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    30f2:	e9 1e ff ff ff       	jmpq   3015 <init_driver+0xea>
    30f7:	48 b8 45 72 72 6f 72 	movabs $0x55203a726f727245,%rax
    30fe:	3a 20 55 
    3101:	48 ba 6e 61 62 6c 65 	movabs $0x6f7420656c62616e,%rdx
    3108:	20 74 6f 
    310b:	49 89 04 24          	mov    %rax,(%r12)
    310f:	49 89 54 24 08       	mov    %rdx,0x8(%r12)
    3114:	48 b8 20 63 6f 6e 6e 	movabs $0x7463656e6e6f6320,%rax
    311b:	65 63 74 
    311e:	48 ba 20 74 6f 20 73 	movabs $0x76726573206f7420,%rdx
    3125:	65 72 76 
    3128:	49 89 44 24 10       	mov    %rax,0x10(%r12)
    312d:	49 89 54 24 18       	mov    %rdx,0x18(%r12)
    3132:	66 41 c7 44 24 20 65 	movw   $0x7265,0x20(%r12)
    3139:	72 
    313a:	41 c6 44 24 22 00    	movb   $0x0,0x22(%r12)
    3140:	89 df                	mov    %ebx,%edi
    3142:	e8 59 dd ff ff       	callq  ea0 <close@plt>
    3147:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    314c:	e9 c4 fe ff ff       	jmpq   3015 <init_driver+0xea>
    3151:	e8 0a dd ff ff       	callq  e60 <__stack_chk_fail@plt>

0000000000003156 <driver_post>:
    3156:	53                   	push   %rbx
    3157:	4c 89 cb             	mov    %r9,%rbx
    315a:	45 85 c0             	test   %r8d,%r8d
    315d:	75 18                	jne    3177 <driver_post+0x21>
    315f:	48 85 ff             	test   %rdi,%rdi
    3162:	74 05                	je     3169 <driver_post+0x13>
    3164:	80 3f 00             	cmpb   $0x0,(%rdi)
    3167:	75 37                	jne    31a0 <driver_post+0x4a>
    3169:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    316e:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    3172:	44 89 c0             	mov    %r8d,%eax
    3175:	5b                   	pop    %rbx
    3176:	c3                   	retq   
    3177:	48 89 ca             	mov    %rcx,%rdx
    317a:	48 8d 35 cb 08 00 00 	lea    0x8cb(%rip),%rsi        # 3a4c <trans_char+0xdc>
    3181:	bf 01 00 00 00       	mov    $0x1,%edi
    3186:	b8 00 00 00 00       	mov    $0x0,%eax
    318b:	e8 d0 dd ff ff       	callq  f60 <__printf_chk@plt>
    3190:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    3195:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    3199:	b8 00 00 00 00       	mov    $0x0,%eax
    319e:	eb d5                	jmp    3175 <driver_post+0x1f>
    31a0:	48 83 ec 08          	sub    $0x8,%rsp
    31a4:	41 51                	push   %r9
    31a6:	49 89 c9             	mov    %rcx,%r9
    31a9:	49 89 d0             	mov    %rdx,%r8
    31ac:	48 89 f9             	mov    %rdi,%rcx
    31af:	48 89 f2             	mov    %rsi,%rdx
    31b2:	be 9a 3c 00 00       	mov    $0x3c9a,%esi
    31b7:	48 8d 3d 7e 08 00 00 	lea    0x87e(%rip),%rdi        # 3a3c <trans_char+0xcc>
    31be:	e8 b9 f5 ff ff       	callq  277c <submitr>
    31c3:	48 83 c4 10          	add    $0x10,%rsp
    31c7:	eb ac                	jmp    3175 <driver_post+0x1f>

00000000000031c9 <check>:
    31c9:	89 f8                	mov    %edi,%eax
    31cb:	c1 e8 1c             	shr    $0x1c,%eax
    31ce:	85 c0                	test   %eax,%eax
    31d0:	74 1d                	je     31ef <check+0x26>
    31d2:	b9 00 00 00 00       	mov    $0x0,%ecx
    31d7:	83 f9 1f             	cmp    $0x1f,%ecx
    31da:	7f 0d                	jg     31e9 <check+0x20>
    31dc:	89 f8                	mov    %edi,%eax
    31de:	d3 e8                	shr    %cl,%eax
    31e0:	3c 0a                	cmp    $0xa,%al
    31e2:	74 11                	je     31f5 <check+0x2c>
    31e4:	83 c1 08             	add    $0x8,%ecx
    31e7:	eb ee                	jmp    31d7 <check+0xe>
    31e9:	b8 01 00 00 00       	mov    $0x1,%eax
    31ee:	c3                   	retq   
    31ef:	b8 00 00 00 00       	mov    $0x0,%eax
    31f4:	c3                   	retq   
    31f4:	c3                   	retq   
    31f5:	b8 00 00 00 00       	mov    $0x0,%eax
    31fa:	c3                   	retq   

00000000000031fb <gencookie>:
    31fb:	53                   	push   %rbx
    31fc:	83 c7 01             	add    $0x1,%edi
    31ff:	e8 0c dc ff ff       	callq  e10 <srandom@plt>
    3204:	e8 17 dd ff ff       	callq  f20 <random@plt>
    3209:	89 c3                	mov    %eax,%ebx
    320b:	89 c7                	mov    %eax,%edi
    320d:	e8 b7 ff ff ff       	callq  31c9 <check>
    3212:	85 c0                	test   %eax,%eax
    3214:	74 ee                	je     3204 <gencookie+0x9>
    3216:	89 d8                	mov    %ebx,%eax
    3218:	5b                   	pop    %rbx
    3219:	c3                   	retq   
    321a:	66 0f 1f 44 00 00    	nopw   0x0(%rax,%rax,1)

0000000000003220 <__libc_csu_init>:
    3220:	41 57                	push   %r15
    3222:	41 56                	push   %r14
    3224:	49 89 d7             	mov    %rdx,%r15
    3227:	41 55                	push   %r13
    3229:	41 54                	push   %r12
    322b:	4c 8d 25 86 1a 20 00 	lea    0x201a86(%rip),%r12        # 204cb8 <__frame_dummy_init_array_entry>
    3232:	55                   	push   %rbp
    3233:	48 8d 2d 86 1a 20 00 	lea    0x201a86(%rip),%rbp        # 204cc0 <__init_array_end>
    323a:	53                   	push   %rbx
    323b:	41 89 fd             	mov    %edi,%r13d
    323e:	49 89 f6             	mov    %rsi,%r14
    3241:	4c 29 e5             	sub    %r12,%rbp
    3244:	48 83 ec 08          	sub    $0x8,%rsp
    3248:	48 c1 fd 03          	sar    $0x3,%rbp
    324c:	e8 77 db ff ff       	callq  dc8 <_init>
    3251:	48 85 ed             	test   %rbp,%rbp
    3254:	74 20                	je     3276 <__libc_csu_init+0x56>
    3256:	31 db                	xor    %ebx,%ebx
    3258:	0f 1f 84 00 00 00 00 	nopl   0x0(%rax,%rax,1)
    325f:	00 
    3260:	4c 89 fa             	mov    %r15,%rdx
    3263:	4c 89 f6             	mov    %r14,%rsi
    3266:	44 89 ef             	mov    %r13d,%edi
    3269:	41 ff 14 dc          	callq  *(%r12,%rbx,8)
    326d:	48 83 c3 01          	add    $0x1,%rbx
    3271:	48 39 dd             	cmp    %rbx,%rbp
    3274:	75 ea                	jne    3260 <__libc_csu_init+0x40>
    3276:	48 83 c4 08          	add    $0x8,%rsp
    327a:	5b                   	pop    %rbx
    327b:	5d                   	pop    %rbp
    327c:	41 5c                	pop    %r12
    327e:	41 5d                	pop    %r13
    3280:	41 5e                	pop    %r14
    3282:	41 5f                	pop    %r15
    3284:	c3                   	retq   
    3285:	90                   	nop
    3286:	66 2e 0f 1f 84 00 00 	nopw   %cs:0x0(%rax,%rax,1)
    328d:	00 00 00 

0000000000003290 <__libc_csu_fini>:
    3290:	f3 c3                	repz retq 

Disassembly of section .fini:

0000000000003294 <_fini>:
    3294:	48 83 ec 08          	sub    $0x8,%rsp
    3298:	48 83 c4 08          	add    $0x8,%rsp
    329c:	c3                   	retq   
