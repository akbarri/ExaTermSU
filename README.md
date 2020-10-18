# ExaTermSU
ExaGear Terminal Emulator SuperUser

Original Idea by GFOXSH

https://4pda.ru/forum/index.php?showtopic=992239&st=900#entry97859358

Trouble 1 - "SysV IPC"

cmd:='fakeroot-tcp ' + Edit1.Text + ' &> of.log' + AnsiChar(#10)

Trouble 3 - "environment"

write(ifile, 'export PATH', AnsiChar(#10));

write(ifile, 'export TERM', AnsiChar(#10));
