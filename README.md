# Zadej
v delhi 7

program Project2;

{$APPTYPE CONSOLE}

uses
  SysUtils;

var
  a,b,c:real;
  N,I:Integer;

begin
  Writeln('Zadej přirozené číslo:   );
  ReadLn(N);
  for I:=1 to N do
    begin
      WriteLn('Zadej trojici čísel:');
      ReadLn(a,b,c);
      if a=b then
        if a=c then
          WriteLn('Shoda 3')
        else
          WriteLn('Shoda 2')
      else
        if a=c then
          WriteLn('Shoda 2')
        else
          if b=c then
            WriteLn('Shoda 2')
          else;
            WriteLn('Shoda 0')
    end
End

