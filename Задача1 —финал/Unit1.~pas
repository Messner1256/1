unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, Buttons, ImgList, ExtCtrls;

type
  TForm1 = class(TForm)
    Edit1: TEdit;
    Edit2: TEdit;
    Edit3: TEdit;
    Edit4: TEdit;
    Edit5: TEdit;
    Edit6: TEdit;
    Edit11: TEdit;
    Edit12: TEdit;
    Edit13: TEdit;
    Edit14: TEdit;
    Edit15: TEdit;
    Edit16: TEdit;
    Button1: TButton;
    Button2: TButton;
    Panel1: TPanel;
    Panel2: TPanel;
    Panel3: TPanel;
    Panel4: TPanel;
    Panel5: TPanel;
    Panel6: TPanel;
    Label1: TLabel;
    Edit123: TEdit;
    Edit8: TEdit;
    Edit9: TEdit;
    Edit10: TEdit;
    Edit17: TEdit;
    Edit18: TEdit;
    Edit19: TEdit;
    Panel7: TPanel;
    Panel8: TPanel;
    Panel9: TPanel;
    RB1: TRadioButton;
    RB2: TRadioButton;
    RB3: TRadioButton;
    Edit010: TEdit;
    Edit011: TEdit;
    Edit012: TEdit;
    Edit111: TEdit;
    Edit0111: TEdit;
    Edit112: TEdit;
    Panel10: TPanel;
    Panel11: TPanel;
    Panel12: TPanel;
    RB4: TRadioButton;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure RB1Click(Sender: TObject);
    procedure RB2Click(Sender: TObject);
    procedure RB3Click(Sender: TObject);
    procedure RB4Click(Sender: TObject);



   



  private
    { Private declarations }
  public
    max:integer;
       k:integer;
       rej: integer;
    end;

var
  Form1: TForm1;

implementation

{$R *.dfm}





procedure TForm1.Button1Click(Sender: TObject);
begin
If rej=1 then begin
randomize;
Edit1.Text:=IntToStr(1+random(100));
Edit2.Text:=IntToStr(1+random(100));
Edit3.Text:=IntToStr(1+random(100));
Edit11.Text:=Edit1.Text;
Edit12.Text:=Edit2.Text;
Edit13.Text:=Edit3.Text;
end;
If rej=2 then begin
randomize;
Edit1.Text:=IntToStr(1+random(100));
Edit2.Text:=IntToStr(1+random(100));
Edit3.Text:=IntToStr(1+random(100));
Edit4.Text:=IntToStr(1+random(100));
Edit5.Text:=IntToStr(1+random(100));
Edit6.Text:=IntToStr(1+random(100));
Edit11.Text:=Edit1.Text;
Edit12.Text:=Edit2.Text;
Edit13.Text:=Edit3.Text;
Edit14.Text:=Edit4.Text;
Edit15.Text:=Edit5.Text;
Edit16.Text:=Edit6.Text;
end;
If rej=3 then begin
randomize;
Edit1.Text:=IntToStr(1+random(100));
Edit2.Text:=IntToStr(1+random(100));
Edit3.Text:=IntToStr(1+random(100));
Edit4.Text:=IntToStr(1+random(100));
Edit5.Text:=IntToStr(1+random(100));
Edit6.Text:=IntToStr(1+random(100));
Edit8.Text:=IntToStr(1+random(100));
Edit9.Text:=IntToStr(1+random(100));
Edit10.Text:=IntToStr(1+random(100));

Edit11.Text:=Edit1.Text;
Edit12.Text:=Edit2.Text;
Edit13.Text:=Edit3.Text;
Edit14.Text:=Edit4.Text;
Edit15.Text:=Edit5.Text;
Edit16.Text:=Edit6.Text;
Edit17.Text:=Edit8.Text;
Edit18.Text:=Edit9.Text;
Edit19.Text:=Edit10.Text;

end;
If rej=4 then begin
randomize;
Edit1.Text:=IntToStr(1+random(100));
Edit2.Text:=IntToStr(1+random(100));
Edit3.Text:=IntToStr(1+random(100));
Edit4.Text:=IntToStr(1+random(100));
Edit5.Text:=IntToStr(1+random(100));
Edit6.Text:=IntToStr(1+random(100));
Edit8.Text:=IntToStr(1+random(100));
Edit9.Text:=IntToStr(1+random(100));
Edit10.Text:=IntToStr(1+random(100));
Edit010.Text:=IntToStr(1+random(100));
Edit011.Text:=IntToStr(1+random(100));
Edit012.Text:=IntToStr(1+random(100));

Edit11.Text:=Edit1.Text;
Edit12.Text:=Edit2.Text;
Edit13.Text:=Edit3.Text;
Edit14.Text:=Edit4.Text;
Edit15.Text:=Edit5.Text;
Edit16.Text:=Edit6.Text;
Edit17.Text:=Edit8.Text;
Edit18.Text:=Edit9.Text;
Edit19.Text:=Edit10.Text;
Edit111.Text:=Edit010.Text;
Edit0111.Text:=Edit011.Text;
Edit112.Text:=Edit012.Text;
end;

max:=StrToInt(edit1.Text);
k:=0;
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
If rej=1 then begin
While (max<>StrToInt(Edit12.Text)) or  (max<>StrToInt(Edit13.Text)) do begin

If max > StrToInt(Edit1.Text) then
Edit11.Text:= IntToStr(max)
else
max:=StrToInt(Edit1.Text);

 If max > StrToInt(Edit2.Text) then
 Edit12.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit2.Text);

If max > StrToInt(Edit3.Text) then
Edit13.Text:= IntToStr(max)
else
max:=StrToInt(Edit3.Text);

 If max > StrToInt(Edit1.Text) then
 Edit11.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit1.Text);

k:=k+1;
Edit123.Text:=IntToStr(k);
end;
If max = StrToInt(Edit1.text) then
Panel1.color:=clgreen
else Panel1.Color:=clred;

If max = StrToInt(Edit2.text) then
Panel2.color:=clgreen
else Panel2.Color:=clred;

If max = StrToInt(Edit3.text) then
Panel3.color:=clgreen
else Panel3.Color:=clred;
end;
If rej=2 then begin

While (max<>StrToInt(Edit12.Text)) or  (max<>StrToInt(Edit13.Text)) or  (max<>StrToInt(Edit14.Text)) or (max<>StrToInt(Edit15.Text)) or  (max<>StrToInt(Edit16.Text)) do begin

If max > StrToInt(Edit1.Text) then
Edit11.Text:= IntToStr(max)
else
max:=StrToInt(Edit1.Text);

 If max > StrToInt(Edit2.Text) then
 Edit12.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit2.Text);

If max > StrToInt(Edit3.Text) then
Edit13.Text:= IntToStr(max)
else
max:=StrToInt(Edit3.Text);

 If max > StrToInt(Edit4.Text) then
 Edit14.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit4.Text);

If max > StrToInt(Edit5.Text) then
Edit15.Text:= IntToStr(max)
else
max:=StrToInt(Edit5.Text);

 If max > StrToInt(Edit6.Text) then
 Edit16.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit6.Text);

 If max > StrToInt(Edit1.Text) then
Edit11.Text:= IntToStr(max)
else
max:=StrToInt(Edit1.Text);

k:=k+1;
Edit123.Text:=IntToStr(k);

 end;

If max = StrToInt(Edit1.text) then
Panel1.color:=clgreen
else Panel1.Color:=clred;

If max = StrToInt(Edit2.text) then
Panel2.color:=clgreen
else Panel2.Color:=clred;

If max = StrToInt(Edit3.text) then
Panel3.color:=clgreen
else Panel3.Color:=clred;

If max = StrToInt(Edit4.text) then
Panel4.color:=clgreen
else Panel4.Color:=clred;

If max = StrToInt(Edit5.text) then
Panel5.color:=clgreen
else Panel5.Color:=clred;

If max = StrToInt(Edit6.text) then
Panel6.color:=clgreen
else Panel6.Color:=clred;
end;

 If rej=3 then begin

While (max<>StrToInt(Edit12.Text)) or  (max<>StrToInt(Edit13.Text)) or  (max<>StrToInt(Edit14.Text)) or (max<>StrToInt(Edit15.Text)) or  (max<>StrToInt(Edit16.Text)) or  (max<>StrToInt(Edit17.Text)) or  (max<>StrToInt(Edit18.Text)) or  (max<>StrToInt(Edit19.Text)) do begin

If max > StrToInt(Edit1.Text) then
Edit11.Text:= IntToStr(max)
else
max:=StrToInt(Edit1.Text);

 If max > StrToInt(Edit2.Text) then
 Edit12.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit2.Text);

If max > StrToInt(Edit3.Text) then
Edit13.Text:= IntToStr(max)
else
max:=StrToInt(Edit3.Text);

 If max > StrToInt(Edit4.Text) then
 Edit14.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit4.Text);

If max > StrToInt(Edit5.Text) then
Edit15.Text:= IntToStr(max)
else
max:=StrToInt(Edit5.Text);

 If max > StrToInt(Edit6.Text) then
 Edit16.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit6.Text);

If max > StrToInt(Edit8.Text) then
Edit17.Text:= IntToStr(max)
else
max:=StrToInt(Edit8.Text);

 If max > StrToInt(Edit9.Text) then
 Edit18.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit9.Text);

If max > StrToInt(Edit10.Text) then
Edit19.Text:= IntToStr(max)
else
max:=StrToInt(Edit10.Text);

 If max > StrToInt(Edit1.Text) then
 Edit11.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit1.Text);

k:=k+1;
Edit123.Text:=IntToStr(k);

 end;

If max = StrToInt(Edit1.text) then
Panel1.color:=clgreen
else Panel1.Color:=clred;

If max = StrToInt(Edit2.text) then
Panel2.color:=clgreen
else Panel2.Color:=clred;

If max = StrToInt(Edit3.text) then
Panel3.color:=clgreen
else Panel3.Color:=clred;

If max = StrToInt(Edit4.text) then
Panel4.color:=clgreen
else Panel4.Color:=clred;

If max = StrToInt(Edit5.text) then
Panel5.color:=clgreen
else Panel5.Color:=clred;

If max = StrToInt(Edit6.text) then
Panel6.color:=clgreen
else Panel6.Color:=clred;

If max = StrToInt(Edit8.text) then
Panel7.color:=clgreen
else Panel7.Color:=clred;

If max = StrToInt(Edit9.text) then
Panel8.color:=clgreen
else Panel8.Color:=clred;

If max = StrToInt(Edit10.text) then
Panel9.color:=clgreen
else Panel9.Color:=clred;
end;
 If rej=4 then begin

While (max<>StrToInt(Edit12.Text)) or  (max<>StrToInt(Edit13.Text)) or  (max<>StrToInt(Edit14.Text)) or (max<>StrToInt(Edit15.Text)) or  (max<>StrToInt(Edit16.Text)) or  (max<>StrToInt(Edit17.Text)) or  (max<>StrToInt(Edit18.Text)) or  (max<>StrToInt(Edit19.Text)) or  (max<>StrToInt(Edit111.Text)) or  (max<>StrToInt(Edit0111.Text)) or  (max<>StrToInt(Edit112.Text)) do begin

If max > StrToInt(Edit1.Text) then
Edit11.Text:= IntToStr(max)
else
max:=StrToInt(Edit1.Text);

 If max > StrToInt(Edit2.Text) then
 Edit12.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit2.Text);

If max > StrToInt(Edit3.Text) then
Edit13.Text:= IntToStr(max)
else
max:=StrToInt(Edit3.Text);

 If max > StrToInt(Edit4.Text) then
 Edit14.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit4.Text);

If max > StrToInt(Edit5.Text) then
Edit15.Text:= IntToStr(max)
else
max:=StrToInt(Edit5.Text);

 If max > StrToInt(Edit6.Text) then
 Edit16.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit6.Text);

If max > StrToInt(Edit8.Text) then
Edit17.Text:= IntToStr(max)
else
max:=StrToInt(Edit8.Text);

 If max > StrToInt(Edit9.Text) then
 Edit18.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit9.Text);

If max > StrToInt(Edit10.Text) then
Edit19.Text:= IntToStr(max)
else
max:=StrToInt(Edit10.Text);

 If max > StrToInt(Edit010.Text) then
 Edit111.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit010.Text);

If max > StrToInt(Edit011.Text) then
Edit0111.Text:= IntToStr(max)
else
max:=StrToInt(Edit011.Text);

 If max > StrToInt(Edit012.Text) then
 Edit112.Text:= IntToStr(max)
 else
 max:=StrToInt(Edit012.Text);

If max > StrToInt(Edit1.Text) then
Edit11.Text:= IntToStr(max)
else
max:=StrToInt(Edit1.Text);

k:=k+1;
Edit123.Text:=IntToStr(k);

 end;

If max = StrToInt(Edit1.text) then
Panel1.color:=clgreen
else Panel1.Color:=clred;

If max = StrToInt(Edit2.text) then
Panel2.color:=clgreen
else Panel2.Color:=clred;

If max = StrToInt(Edit3.text) then
Panel3.color:=clgreen
else Panel3.Color:=clred;

If max = StrToInt(Edit4.text) then
Panel4.color:=clgreen
else Panel4.Color:=clred;

If max = StrToInt(Edit5.text) then
Panel5.color:=clgreen
else Panel5.Color:=clred;

If max = StrToInt(Edit6.text) then
Panel6.color:=clgreen
else Panel6.Color:=clred;

If max = StrToInt(Edit8.text) then
Panel7.color:=clgreen
else Panel7.Color:=clred;

If max = StrToInt(Edit9.text) then
Panel8.color:=clgreen
else Panel8.Color:=clred;

If max = StrToInt(Edit10.text) then
Panel9.color:=clgreen
else Panel9.Color:=clred;

If max = StrToInt(Edit010.text) then
Panel10.color:=clgreen
else Panel10.Color:=clred;

If max = StrToInt(Edit011.text) then
Panel11.color:=clgreen
else Panel11.Color:=clred;

If max = StrToInt(Edit012.text) then
Panel12.color:=clgreen
else Panel12.Color:=clred;


end;
end;



procedure TForm1.RB1Click(Sender: TObject);
begin
RB1.Checked:=true;
RB2.Checked:=false;
RB3.Checked:=false;
RB4.Checked:=false;
Rej:=1;
edit1.enabled:=true;edit11.enabled:=true;edit2.enabled:=true;edit12.enabled:=true;edit3.enabled:=true;edit13.enabled:=true;edit4.enabled:=false;edit14.enabled:=false;edit5.enabled:=false;edit15.enabled:=false;edit6.enabled:=false;edit16.enabled:=false;edit8.enabled:=false;edit17.enabled:=false;edit9.enabled:=false;edit10.enabled:=false;edit18.enabled:=false;edit19.enabled:=false;edit010.enabled:=false;edit111.enabled:=false;edit011.enabled:=false;edit0111.enabled:=false;edit012.enabled:=false;edit112.enabled:=false;
end;

procedure TForm1.RB2Click(Sender: TObject);
begin
RB1.Checked:=false;
RB2.Checked:=true;
RB3.Checked:=false;
RB4.Checked:=false;


Rej:=2;
edit1.enabled:=true;edit11.enabled:=true;edit2.enabled:=true;edit12.enabled:=true;edit3.enabled:=true;edit13.enabled:=true;edit4.enabled:=true;edit14.enabled:=true;edit5.enabled:=true;edit15.enabled:=true;edit6.enabled:=true;edit16.enabled:=true;edit8.enabled:=false;edit17.enabled:=false;edit9.enabled:=false;edit10.enabled:=false;edit18.enabled:=false;edit19.enabled:=false;edit010.enabled:=false;edit111.enabled:=false;edit011.enabled:=false;edit0111.enabled:=false;edit012.enabled:=false;edit112.enabled:=false;
end;
procedure TForm1.RB3Click(Sender: TObject);
begin
RB1.Checked:=false;
RB2.Checked:=false;
RB3.Checked:=true;
RB4.Checked:=false;


Rej:=3;
edit1.enabled:=true;edit11.enabled:=true;edit2.enabled:=true;edit12.enabled:=true;edit3.enabled:=true;edit13.enabled:=true;edit4.enabled:=true;edit14.enabled:=true;edit5.enabled:=true;edit15.enabled:=true;edit6.enabled:=true;edit16.enabled:=true;edit8.enabled:=true;edit17.enabled:=true;edit9.enabled:=true;edit10.enabled:=true;edit18.enabled:=true;edit19.enabled:=true;edit010.enabled:=false;edit111.enabled:=false;edit011.enabled:=false;edit0111.enabled:=false;edit012.enabled:=false;edit112.enabled:=false;
end;




procedure TForm1.RB4Click(Sender: TObject);
begin
RB1.Checked:=false;
RB2.Checked:=false;
RB3.Checked:=false;
RB4.Checked:=true;
Rej:=4;
edit1.enabled:=true;edit11.enabled:=true;edit2.enabled:=true;edit12.enabled:=true;edit3.enabled:=true;edit13.enabled:=true;edit4.enabled:=true;edit14.enabled:=true;edit5.enabled:=true;edit15.enabled:=true;edit6.enabled:=true;edit16.enabled:=true;edit8.enabled:=true;edit17.enabled:=true;edit9.enabled:=true;edit10.enabled:=true;edit18.enabled:=true;edit19.enabled:=true;edit010.enabled:=true;edit111.enabled:=true;edit011.enabled:=true;edit0111.enabled:=true;edit012.enabled:=false;edit112.enabled:=true;

end;

end.


