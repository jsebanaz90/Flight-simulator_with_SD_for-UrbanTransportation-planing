unit Unit2;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, UMotor, UMotorEvolucion, UComponenteMotor, ComCtrls,
  TeEngine, Series, ExtCtrls, TeeProcs, Chart, Gauges, Menus;

type
  TForm2 = class(TForm)
    MotorEvl1: TMotorEvl;
    Button1: TButton;
    TrackBar1: TTrackBar;
    MotorEvl2: TMotorEvl;
    Cuoda: TPageControl;
    TabSheet1: TTabSheet;
    TabSheet2: TTabSheet;
    TabSheet3: TTabSheet;
    Chart2: TChart;
    Chart3: TChart;
    Chart4: TChart;
    Series3: TLineSeries;
    Series4: TLineSeries;
    Label2: TLabel;
    Label3: TLabel;
    StaticText1: TStaticText;
    StaticText2: TStaticText;
    Shape1: TShape;
    Shape2: TShape;
    Series5: TLineSeries;
    Series6: TLineSeries;
    Series7: TLineSeries;
    Series8: TLineSeries;
    Button2: TButton;
    Button3: TButton;
    GroupBox1: TGroupBox;
    Label7: TLabel;
    StaticText3: TStaticText;
    StaticText4: TStaticText;
    Gauge1: TGauge;
    StaticText5: TStaticText;
    StaticText6: TStaticText;
    StaticText7: TStaticText;
    StaticText8: TStaticText;
    Shape3: TShape;
    Shape5: TShape;
    Shape4: TShape;
    Shape6: TShape;
    StaticText9: TStaticText;
    StaticText10: TStaticText;
    StaticText11: TStaticText;
    StaticText12: TStaticText;
    Label1: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    Label6: TLabel;
    GroupBox2: TGroupBox;
    GroupBox3: TGroupBox;
    GroupBox5: TGroupBox;
    Label12: TLabel;
    Shape11: TShape;
    Shape12: TShape;
    Label13: TLabel;
    Label14: TLabel;
    Label15: TLabel;
    TrackBar2: TTrackBar;
    TrackBar3: TTrackBar;
    Label16: TLabel;
    Label17: TLabel;
    Label18: TLabel;
    Label19: TLabel;
    Label20: TLabel;
    Label21: TLabel;
    TrackBar4: TTrackBar;
    TrackBar5: TTrackBar;
    Label22: TLabel;
    Label23: TLabel;
    Label24: TLabel;
    Label25: TLabel;
    Label26: TLabel;
    Label28: TLabel;
    Label29: TLabel;
    TrackBar6: TTrackBar;
    Label31: TLabel;
    TrackBar8: TTrackBar;
    TrackBar10: TTrackBar;
    Label33: TLabel;
    Label35: TLabel;
    Label36: TLabel;
    Label38: TLabel;
    Label40: TLabel;
    Image1: TImage;
    Image2: TImage;
    MainMenu1: TMainMenu;
    Acercade1: TMenuItem;
    Interfazsoftware1: TMenuItem;
    Modelodinmicosistmico1: TMenuItem;
    Diagramadeinfluencias1: TMenuItem;
    Diagramadeflujosniveles1: TMenuItem;
    Sector11: TMenuItem;
    Sector21: TMenuItem;
    Sector31: TMenuItem;
    Salir1: TMenuItem;
    Image3: TImage;
    Image4: TImage;
    Image5: TImage;
    Image6: TImage;
    Image7: TImage;
    Image8: TImage;
    Image9: TImage;
    Image10: TImage;
    Image11: TImage;
    Image12: TImage;
    StaticText19: TStaticText;
    StaticText20: TStaticText;
    StaticText21: TStaticText;
    StaticText22: TStaticText;
    Image16: TImage;
    StaticText23: TStaticText;
    StaticText24: TStaticText;
    Image15: TImage;
    Image17: TImage;
    TabSheet6: TTabSheet;
    TabSheet7: TTabSheet;
    Chart5: TChart;
    Series9: TLineSeries;
    Series10: TLineSeries;
    Image14: TImage;
    StaticText13: TStaticText;
    Shape9: TShape;
    Shape10: TShape;
    StaticText17: TStaticText;
    Label8: TLabel;
    Label9: TLabel;
    StaticText27: TStaticText;
    Image19: TImage;
    StaticText28: TStaticText;
    Chart1: TChart;
    Series1: TLineSeries;
    Series2: TLineSeries;
    Shape7: TShape;
    Shape8: TShape;
    StaticText16: TStaticText;
    Label10: TLabel;
    Label11: TLabel;
    StaticText14: TStaticText;
    Image13: TImage;
    StaticText25: TStaticText;
    Image18: TImage;
    StaticText26: TStaticText;
    StaticText15: TStaticText;
    StaticText18: TStaticText;
    procedure Button1Click(Sender: TObject);
    procedure TrackBar1Change(Sender: TObject);
    procedure MotorEvl1Preparar(Sender: TObject; var HuboError: Boolean);
    procedure MotorEvl1PasoSimulacion(Sender: TObject);
    procedure MotorEvl2PasoSimulacion(Sender: TObject);
    procedure MotorEvl2Preparar(Sender: TObject; var HuboError: Boolean);
    procedure MotorEvil1Iteracion(Sender: TObject);
    procedure MotorEvil2Iteracion(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure TrackBar3Change(Sender: TObject);
    procedure TrackBar2Change(Sender: TObject);
    procedure TrackBar4Change(Sender: TObject);
    procedure TrackBar5Change(Sender: TObject);
    procedure TrackBar6Change(Sender: TObject);
    procedure TrackBar8Change(Sender: TObject);
    procedure TrackBar10Change(Sender: TObject);
    procedure Image1Click(Sender: TObject);
    procedure Salir1Click(Sender: TObject);
    procedure Image2Click(Sender: TObject);
    procedure Image3Click(Sender: TObject);
    procedure Image4Click(Sender: TObject);
    procedure Image5Click(Sender: TObject);
    procedure Image6Click(Sender: TObject);
    procedure Image7Click(Sender: TObject);
    procedure Image8Click(Sender: TObject);
    procedure Image9Click(Sender: TObject);
    procedure Image10Click(Sender: TObject);
    procedure Image11Click(Sender: TObject);
    procedure Image12Click(Sender: TObject);
    procedure Image13Click(Sender: TObject);
    procedure Image14Click(Sender: TObject);
    procedure Image16Click(Sender: TObject);
    procedure Image15Click(Sender: TObject);
    procedure Image17Click(Sender: TObject);
    procedure Image18Click(Sender: TObject);
    procedure Image19Click(Sender: TObject);
    procedure Interfazsoftware1Click(Sender: TObject);
    procedure Modelodinmicosistmico1Click(Sender: TObject);
    procedure Diagramadeinfluencias1Click(Sender: TObject);
    procedure Sector11Click(Sender: TObject);
    procedure Sector21Click(Sender: TObject);
    procedure Sector31Click(Sender: TObject);

  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form2: TForm2;

implementation

uses Unit3;

{$R *.dfm}

procedure TForm2.Button1Click(Sender: TObject);
begin
  MotorEvl1.Iniciar;
  MotorEvl2.Iniciar;
end;

procedure TForm2.TrackBar1Change(Sender: TObject);
begin
Label7.Caption:=IntToStr(TrackBar1.Position);
end;

procedure TForm2.MotorEvl1Preparar(Sender: TObject; var HuboError: Boolean);
begin
   Chart1.Series[0].Clear;
   Chart2.Series[0].Clear;
   Chart3.Series[0].Clear;
   Chart4.Series[0].Clear;
   Chart5.Series[0].Clear;
   MotorEvl1.CondicionesIniciales.Paso:=0.1;
   MotorEvl1.CondicionesIniciales.PasoGrabacion:=0.1;
   MotorEvl1.CondicionesIniciales.TiempoFinal:=TrackBar1.Position;
   MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('TarifaCongestion')].ValorInicial[0]:=  TrackBar4.Position;
   MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('FraccionReinvers')].ValorInicial[0]:=  TrackBar5.Position/10;
   MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Costo_Pasaje')].ValorInicial[0]:=  TrackBar6.Position;
   MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('FraccNuevosBuses')].ValorInicial[0]:=  TrackBar8.Position/10;
   MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Dinero_estado')].ValorInicial[0]:=  TrackBar10.Position;
end;

procedure TForm2.MotorEvl1PasoSimulacion(Sender: TObject);
begin
  Chart1.SeriesList[0].AddXY(MotorEvl1.TiempoSimulacion,MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('kilom_Recorridos')].Valor[0]);
  Chart2.SeriesList[0].AddXY(MotorEvl1.TiempoSimulacion,MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Porc_Carro')].Valor[0]);
  Chart3.SeriesList[0].AddXY(MotorEvl1.TiempoSimulacion,MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Porc_TP')].Valor[0]);
  Chart4.SeriesList[0].AddXY(MotorEvl1.TiempoSimulacion,MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Porc_TI')].Valor[0]);
  Chart5.SeriesList[0].AddXY(MotorEvl1.TiempoSimulacion,MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('RCI')].Valor[0]);
  Gauge1.Progress:= Round((100* MotorEvl1.TiempoSimulacion)/ MotorEvl1.CondicionesIniciales.TiempoFinal);
end;

procedure TForm2.MotorEvl2PasoSimulacion(Sender: TObject);
begin
   Chart1.SeriesList[1].AddXY(MotorEvl2.TiempoSimulacion,MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('KMR')].Valor[0]);
   Chart2.SeriesList[1].AddXY(MotorEvl2.TiempoSimulacion,MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Porc_Carro')].Valor[0]);
   Chart3.SeriesList[1].AddXY(MotorEvl2.TiempoSimulacion,MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Porc_TP')].Valor[0]);
   Chart4.SeriesList[1].AddXY(MotorEvl2.TiempoSimulacion,MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Porc_TI')].Valor[0]);
   Chart5.SeriesList[1].AddXY(MotorEvl2.TiempoSimulacion,MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('RCI')].Valor[0]);
end;

procedure TForm2.MotorEvl2Preparar(Sender: TObject;  var HuboError: Boolean);
begin
   Chart1.Series[1].Clear;
   Chart2.Series[1].Clear;
   Chart3.Series[1].Clear;
   Chart4.Series[1].Clear;
   Chart5.Series[1].Clear;
   MotorEvl2.CondicionesIniciales.Paso:=0.1;
   MotorEvl2.CondicionesIniciales.PasoGrabacion:=0.1;
   MotorEvl2.CondicionesIniciales.TiempoFinal:=TrackBar1.Position;
   MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('TasaMantinimient')].ValorInicial[0]:=  TrackBar3.Position/10;
   MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Presupuesto_vias')].ValorInicial[0]:=  TrackBar2.Position;
end;

procedure TForm2.MotorEvil1Iteracion(Sender: TObject);
begin
      Label2.Caption:=FormatFloat('0.00', MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Porc_Carro')].Valor[0]);
      Label4.Caption:=FormatFloat('0.00', MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Porc_TP')].Valor[0]);
      Label6.Caption:=FormatFloat('0.00', MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('Porc_TI')].Valor[0]);
      Label9.Caption:=FormatFloat('0.00', MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('RCI')].Valor[0]);
      Label11.Caption:=FormatFloat('0.0', MotorEvl1.ListaElementos[MotorEvl1.ListaElementos.IndiceDe('kilom_Recorridos')].Valor[0]);
end;

procedure TForm2.MotorEvil2Iteracion(Sender: TObject);
begin
      Label3.Caption:=FormatFloat('0.00', MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Porc_Carro')].Valor[0]);
      Label1.Caption:=FormatFloat('0.00', MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Porc_TP')].Valor[0]);
      Label5.Caption:=FormatFloat('0.00', MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('Porc_TI')].Valor[0]);
      Label8.Caption:=FormatFloat('0.00', MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('RCI')].Valor[0]);
      Label10.Caption:=FormatFloat('0.0', MotorEvl2.ListaElementos[MotorEvl2.ListaElementos.IndiceDe('KMR')].Valor[0]);
end;

procedure TForm2.Button2Click(Sender: TObject);
begin
MotorEvl1.Pausa;
MotorEvl2.Pausa;
end;

procedure TForm2.Button3Click(Sender: TObject);
begin
MotorEvl1.Detener;
MotorEvl2.Detener;
end;

procedure TForm2.TrackBar3Change(Sender: TObject);
begin
Label17.Caption:=FormatFloat('0.0', TrackBar3.Position/10);
end;

procedure TForm2.TrackBar2Change(Sender: TObject);
begin
Label18.Caption:=FormatFloat('0.0', TrackBar2.Position);
end;

procedure TForm2.TrackBar4Change(Sender: TObject);
begin
Label22.Caption:=FormatFloat('0.0', TrackBar4.Position);
end;

procedure TForm2.TrackBar5Change(Sender: TObject);
begin
Label24.Caption:=FormatFloat('0.0', TrackBar5.Position/10);
end;

procedure TForm2.TrackBar6Change(Sender: TObject);
begin
Label31.Caption:=FormatFloat('0.0', TrackBar6.Position);
end;

procedure TForm2.TrackBar8Change(Sender: TObject);
begin
Label38.Caption:=FormatFloat('0.0', TrackBar8.Position/10);
end;

procedure TForm2.TrackBar10Change(Sender: TObject);
begin
Label35.Caption:=FormatFloat('0.0', TrackBar10.Position);
end;



procedure TForm2.Image1Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 440;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 440;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Politicas_EscenarioUsual.bmp');
  Form3.Caption:= 'Política usual de construcción';
  Form3.ShowModal
end;

procedure TForm2.Salir1Click(Sender: TObject);
begin
Close;
end;

procedure TForm2.Image2Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 520;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 520;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Politicas_EscenarioPushPull.bmp');
  Form3.Caption:= 'Políticas "Push-Pull"';
  Form3.ShowModal
end;

procedure TForm2.Image3Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 100;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 100;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_construccion.bmp');
  Form3.Caption:= 'Dinero para construcción vial';
  Form3.ShowModal
end;

procedure TForm2.Image4Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 120;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 120;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_mantenimiento.bmp');
  Form3.Caption:= 'Tasa de mantenimiento vial"';
  Form3.ShowModal
end;

procedure TForm2.Image5Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 120;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 120;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_cc.bmp');
  Form3.Caption:= 'Dinero de cobro por congestión';
  Form3.ShowModal
end;

procedure TForm2.Image6Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 250;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 250;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_CC_A_TP.bmp');
  Form3.Caption:= 'Dinero recaudado mediante cobro por congestión para reinvertir en transporte público';
  Form3.ShowModal
end;

procedure TForm2.Image7Click(Sender: TObject);
begin
Form3.Width:= 600;
  Form3.Height:= 100;
  Form3.Image1.Width:= 600;
  Form3.Image1.Height:= 100;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_Pasaje.bmp');
  Form3.Caption:= 'Costo que la población debe pagar por usar el transporte público';
  Form3.ShowModal
end;

procedure TForm2.Image8Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 120;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 120;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_nuevosBuses.bmp');
  Form3.Caption:= 'Dinero recaudado del cobro por congestión para reinvertir en nuevos buses';
  Form3.ShowModal
end;

procedure TForm2.Image9Click(Sender: TObject);
begin
Form3.Width:= 620;
  Form3.Height:= 120;
  Form3.Image1.Width:= 620;
  Form3.Image1.Height:= 120;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\P_Estado.bmp');
  Form3.Caption:= 'Dinero estatal para apoyar la calidad del transporte público';
  Form3.ShowModal
end;

procedure TForm2.Image10Click(Sender: TObject);
begin
Form3.Width:= 690;
  Form3.Height:= 450;
  Form3.Image1.Width:= 690;
  Form3.Image1.Height:= 450;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Escenarios_Evaluados.bmp');
  Form3.Caption:= 'Descripción de escenarios evaluados';
  Form3.ShowModal
end;

procedure TForm2.Image11Click(Sender: TObject);
begin
Form3.Width:= 690;
  Form3.Height:= 450;
  Form3.Image1.Width:= 690;
  Form3.Image1.Height:= 450;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Escenarios_Evaluados.bmp');
  Form3.Caption:= 'Descripción de escenarios evaluados';
  Form3.ShowModal
end;

procedure TForm2.Image12Click(Sender: TObject);
begin
Form3.Width:= 690;
  Form3.Height:= 450;
  Form3.Image1.Width:= 690;
  Form3.Image1.Height:= 450;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Escenarios_Evaluados.bmp');
  Form3.Caption:= 'Descripción de escenarios evaluados';
  Form3.ShowModal
end;

procedure TForm2.Image13Click(Sender: TObject);
begin
Form3.Width:= 690;
  Form3.Height:= 450;
  Form3.Image1.Width:= 690;
  Form3.Image1.Height:= 450;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Escenarios_Evaluados.bmp');
  Form3.Caption:= 'Descripción de escenarios evaluados';
  Form3.ShowModal
end;

procedure TForm2.Image14Click(Sender: TObject);
begin
Form3.Width:= 690;
  Form3.Height:= 450;
  Form3.Image1.Width:= 690;
  Form3.Image1.Height:= 450;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Escenarios_Evaluados.bmp');
  Form3.Caption:= 'Descripción de escenarios evaluados';
  Form3.ShowModal
end;

procedure TForm2.Image16Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 140;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Cuota_TI.bmp');
  Form3.Caption:= 'Descripción cuota de mercado de transporte informal';
  Form3.ShowModal
end;

procedure TForm2.Image15Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 140;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Cuota_C.bmp');
  Form3.Caption:= 'Descripción cuota de mercado de vehículo privado';
  Form3.ShowModal
end;

procedure TForm2.Image17Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 140;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Cuota_TP.bmp');
  Form3.Caption:= 'Descripción cuota de mercado de transporte público';
  Form3.ShowModal
end;

procedure TForm2.Image18Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 140;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\KTR.bmp');
  Form3.Caption:= 'Descripción kilómetros recorridos';
  Form3.ShowModal
end;

procedure TForm2.Image19Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 140;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\CV.bmp');
  Form3.Caption:= 'Descripción índice de congestión vial';
  Form3.ShowModal
end;

procedure TForm2.Interfazsoftware1Click(Sender: TObject);
begin
Form3.Width:= 640;
  Form3.Height:= 140;
  Form3.Image1.Width:= 640;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Info_InterfazSoftware.bmp');
  Form3.Caption:= 'Descripción interfaz software';
  Form3.ShowModal
end;

procedure TForm2.Modelodinmicosistmico1Click(Sender: TObject);
begin
Form3.Width:= 650;
  Form3.Height:= 140;
  Form3.Image1.Width:= 650;
  Form3.Image1.Height:= 140;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\Info_Modelo.bmp');
  Form3.Caption:= 'Descripción modelo dinámico-sistémico';
  Form3.ShowModal
end;

procedure TForm2.Diagramadeinfluencias1Click(Sender: TObject);
begin
Form3.Width:= 1180;
  Form3.Height:= 550;
  Form3.Image1.Width:= 1180;
  Form3.Image1.Height:= 550;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\D_influencias.bmp');
  Form3.Caption:= 'Descripción diagrama de influencias del modelo';
  Form3.ShowModal
end;

procedure TForm2.Sector11Click(Sender: TObject);
begin
Form3.Width:= 1100;
  Form3.Height:= 520;
  Form3.Image1.Width:= 1100;
  Form3.Image1.Height:= 520;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\DFN_Sector1.bmp');
  Form3.Caption:= 'Sector que contiene las políticas Push-Pull';
  Form3.ShowModal
end;

procedure TForm2.Sector21Click(Sender: TObject);
begin
Form3.Width:= 1100;
  Form3.Height:= 360;
  Form3.Image1.Width:= 1100;
  Form3.Image1.Height:= 360;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\DFN_Sector2.bmp');
  Form3.Caption:= 'Sector que contiene la infraestructura vial y el comportamiento vehícular';
  Form3.ShowModal
end;

procedure TForm2.Sector31Click(Sender: TObject);
begin
Form3.Width:= 1100;
  Form3.Height:= 400;
  Form3.Image1.Width:= 1100;
  Form3.Image1.Height:= 400;
  Form3.Image1.Visible:=true;
  Form3.reDefiniciones.Visible:=false;
  Form3.Image1.Picture.LoadFromFile('.\imagenes\DFN_Sector3.bmp');
  Form3.Caption:= 'Sector que contiene la demanda de transporte';
  Form3.ShowModal
end;

end.
