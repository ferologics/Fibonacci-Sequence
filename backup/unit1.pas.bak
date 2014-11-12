unit Unit1;

{$mode objfpc}{$H+}

interface

uses
  Classes, SysUtils, FileUtil, Forms, Controls, Graphics, Dialogs, StdCtrls;

type

  { TForm1 }

  TForm1 = class(TForm)
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Edit1: TEdit;
    Label1: TLabel;
    Label2: TLabel;
    Memo1: TMemo;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
  private
    { private declarations }
  public
    { public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.lfm}

{ TForm1 }
var a,b,c,indexClena,i:Integer;
procedure TForm1.Button1Click(Sender: TObject);
begin
     if (i=0) then Form1.Memo1.Clear;
     a:= 0;
     b:= 1;
     c:= 0;
     indexClena:=StrToInt(Form1.Edit1.Text);
     for i:=1 to indexClena do
         begin
           c:= a + b;
           a:= b;
           b:= c;
           //Form1.Memo1.Lines.Add(IntToStr(c));
         end;
     Form1.Memo1.Lines.Add(IntToStr(c));
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
     if (i=0) then Form1.Memo1.Clear;
     a:= 0;
     b:= 1;
     c:= 0;
     i:= 1;
     indexClena:=StrToInt(Form1.Edit1.Text);
     while (i <= indexClena) do
           begin
             c:= a + b;
             a:= b;
             b:= c;
             //Form1.Memo1.Lines.Add(IntToStr(c));
             i:= i+1;
           end;
     Form1.Memo1.Lines.Add(IntToStr(c));
end;

procedure TForm1.Button3Click(Sender: TObject);
begin
     if (i=0) then Form1.Memo1.Clear;
     a:= 0;
     b:= 1;
     c:= 0;
     i:= 1;
     indexClena:=StrToInt(Form1.Edit1.Text);
     repeat
       c:= a + b;
       a:= b;
       b:= c;
       //Form1.Memo1.Lines.Add(IntToStr(c));
       i:= i+1;
     until(i > indexClena);
     Form1.Memo1.Lines.Add(IntToStr(c));
end;

end.

