# UE Market Oyunu

Yapmış olduğum market oyununun UI Kodu ve kullandığım resim dosyalarına erişe bilirsiniz.

```python
Begin Object Class=/Script/UMG.CanvasPanel Name="CanvasPanel_19" ExportPath="/Script/UMG.CanvasPanel'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19'"
   Begin Object Class=/Script/UMG.CanvasPanelSlot Name="CanvasPanelSlot_1" ExportPath="/Script/UMG.CanvasPanelSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19.CanvasPanelSlot_1'"
   End Object
   Begin Object Class=/Script/UMG.CanvasPanelSlot Name="CanvasPanelSlot_0" ExportPath="/Script/UMG.CanvasPanelSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19.CanvasPanelSlot_0'"
   End Object
   Begin Object Class=/Script/UMG.CanvasPanelSlot Name="CanvasPanelSlot_8" ExportPath="/Script/UMG.CanvasPanelSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19.CanvasPanelSlot_8'"
   End Object
   Begin Object Name="CanvasPanelSlot_1" ExportPath="/Script/UMG.CanvasPanelSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19.CanvasPanelSlot_1'"
      LayoutData=(Offsets=(Right=1920.000000,Bottom=1080.000000),Anchors=(Minimum=(X=0.500000,Y=0.500000),Maximum=(X=0.500000,Y=0.500000)),Alignment=(X=0.500000,Y=0.500000))
      Parent="/Script/UMG.CanvasPanel'CanvasPanel_19'"
      Content="/Script/UMG.Image'Background_Image'"
   End Object
   Begin Object Name="CanvasPanelSlot_0" ExportPath="/Script/UMG.CanvasPanelSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19.CanvasPanelSlot_0'"
      LayoutData=(Anchors=(Minimum=(X=0.500000,Y=0.000000),Maximum=(X=0.500000,Y=0.000000)),Alignment=(X=0.500000,Y=-2.500000))
      bAutoSize=True
      Parent="/Script/UMG.CanvasPanel'CanvasPanel_19'"
      Content="/Script/UMG.SizeBox'SizeBox_0'"
   End Object
   Begin Object Name="CanvasPanelSlot_8" ExportPath="/Script/UMG.CanvasPanelSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.CanvasPanel_19.CanvasPanelSlot_8'"
      LayoutData=(Offsets=(Right=0.000000,Bottom=0.000000),Anchors=(Maximum=(X=1.000000,Y=1.000000)))
      Parent="/Script/UMG.CanvasPanel'CanvasPanel_19'"
      Content="/Script/UMG.WidgetSwitcher'WidgetSwitcher'"
   End Object
   Slots(0)="/Script/UMG.CanvasPanelSlot'CanvasPanelSlot_1'"
   Slots(1)="/Script/UMG.CanvasPanelSlot'CanvasPanelSlot_0'"
   Slots(2)="/Script/UMG.CanvasPanelSlot'CanvasPanelSlot_8'"
   bExpandedInDesigner=True
End Object
Begin Object Class=/Script/UMGEditor.WidgetSlotPair Name="WidgetSlotPair_0" ExportPath="/Script/UMGEditor.WidgetSlotPair'/Engine/Transient.WidgetSlotPair_0'"
   WidgetName="CanvasPanel_19"
End Object
Begin Object Class=/Script/UMG.Image Name="Background_Image" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Background_Image'"
   Brush=(ImageType=FullColor,ImageSize=(X=684.000000,Y=365.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/TabletUI.TabletUI'")
   DisplayLabel="Background_Image"
End Object
Begin Object Class=/Script/UMG.SizeBox Name="SizeBox_0" ExportPath="/Script/UMG.SizeBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SizeBox_0'"
   Begin Object Class=/Script/UMG.SizeBoxSlot Name="SizeBoxSlot_0" ExportPath="/Script/UMG.SizeBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SizeBox_0.SizeBoxSlot_0'"
   End Object
   Begin Object Name="SizeBoxSlot_0" ExportPath="/Script/UMG.SizeBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SizeBox_0.SizeBoxSlot_0'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Parent="/Script/UMG.SizeBox'SizeBox_0'"
      Content="/Script/UMG.HorizontalBox'HorizontalBox_43'"
   End Object
   Slots(0)="/Script/UMG.SizeBoxSlot'SizeBoxSlot_0'"
End Object
Begin Object Class=/Script/UMG.HorizontalBox Name="HorizontalBox_43" ExportPath="/Script/UMG.HorizontalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43'"
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_4" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43.HorizontalBoxSlot_4'"
   End Object
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_1" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43.HorizontalBoxSlot_1'"
   End Object
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_5" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43.HorizontalBoxSlot_5'"
   End Object
   Begin Object Name="HorizontalBoxSlot_4" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43.HorizontalBoxSlot_4'"
      Parent="/Script/UMG.HorizontalBox'HorizontalBox_43'"
      Content="/Script/UMG.TextBlock'DukkanName'"
   End Object
   Begin Object Name="HorizontalBoxSlot_1" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43.HorizontalBoxSlot_1'"
      Padding=(Left=4.000000,Top=2.000000,Right=4.000000,Bottom=2.000000)
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Parent="/Script/UMG.HorizontalBox'HorizontalBox_43'"
      Content="/Script/UMG.Spacer'Spacer_54'"
   End Object
   Begin Object Name="HorizontalBoxSlot_5" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.HorizontalBox_43.HorizontalBoxSlot_5'"
      Parent="/Script/UMG.HorizontalBox'HorizontalBox_43'"
      Content="/Script/UMG.TextBlock'Money_Text'"
   End Object
   Slots(0)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_4'"
   Slots(1)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_1'"
   Slots(2)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_5'"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="DukkanName" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.DukkanName'"
   Text=NSLOCTEXT("UMG", "TextBlockDefaultValue", "Text Block")
   DisplayLabel="DukkanName"
End Object
Begin Object Class=/Script/UMG.Spacer Name="Spacer_54" ExportPath="/Script/UMG.Spacer'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Spacer_54'"
   Size=(X=500.000000,Y=1.000000)
End Object
Begin Object Class=/Script/UMG.TextBlock Name="Money_Text" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Money_Text'"
   Text=NSLOCTEXT("UMG", "TextBlockDefaultValue", "Text Block")
   DisplayLabel="Money_Text"
End Object
Begin Object Class=/Script/UMG.WidgetSwitcher Name="WidgetSwitcher" ExportPath="/Script/UMG.WidgetSwitcher'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher'"
   Begin Object Class=/Script/UMG.WidgetSwitcherSlot Name="WidgetSwitcherSlot_0" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher.WidgetSwitcherSlot_0'"
   End Object
   Begin Object Class=/Script/UMG.WidgetSwitcherSlot Name="WidgetSwitcherSlot_1" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher.WidgetSwitcherSlot_1'"
   End Object
   Begin Object Name="WidgetSwitcherSlot_0" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher.WidgetSwitcherSlot_0'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Parent="/Script/UMG.WidgetSwitcher'WidgetSwitcher'"
      Content="/Script/UMG.GridPanel'GridPanel_162'"
   End Object
   Begin Object Name="WidgetSwitcherSlot_1" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher.WidgetSwitcherSlot_1'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Parent="/Script/UMG.WidgetSwitcher'WidgetSwitcher'"
      Content="/Script/UMG.HorizontalBox'SiparişVer_HBox'"
   End Object
   Slots(0)="/Script/UMG.WidgetSwitcherSlot'WidgetSwitcherSlot_0'"
   Slots(1)="/Script/UMG.WidgetSwitcherSlot'WidgetSwitcherSlot_1'"
   bExpandedInDesigner=True
   DisplayLabel="WidgetSwitcher"
End Object
Begin Object Class=/Script/UMG.GridPanel Name="GridPanel_162" ExportPath="/Script/UMG.GridPanel'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162'"
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_6" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_6'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_3" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_3'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_4" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_4'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_7" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_7'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_2" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_2'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_1" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_1'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_0" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_0'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_5" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_5'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_8" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_8'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_10" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_10'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_11" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_11'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_12" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_12'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_13" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_13'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_14" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_14'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_15" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_15'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_16" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_16'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_9" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_9'"
   End Object
   Begin Object Class=/Script/UMG.GridSlot Name="GridSlot_17" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_17'"
   End Object
   Begin Object Name="GridSlot_6" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_6'"
      Row=4
      Column=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'Ayarlar_Btn'"
   End Object
   Begin Object Name="GridSlot_3" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_3'"
      Row=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'Banka_Btn'"
   End Object
   Begin Object Name="GridSlot_4" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_4'"
      Row=2
      Column=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'Casino_Btn'"
   End Object
   Begin Object Name="GridSlot_7" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_7'"
      Row=4
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'Kaydet_Btn'"
   End Object
   Begin Object Name="GridSlot_2" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_2'"
      Column=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'MarketGeliştir_Btn'"
   End Object
   Begin Object Name="GridSlot_1" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_1'"
      Column=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'ReklamVer_Btn'"
   End Object
   Begin Object Name="GridSlot_0" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_0'"
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'SiparişVer_Btn'"
   End Object
   Begin Object Name="GridSlot_5" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_5'"
      Row=2
      Column=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'Yorumlar_Btn'"
   End Object
   Begin Object Name="GridSlot_8" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_8'"
      Row=4
      Column=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.Button'Çik_Btn'"
   End Object
   Begin Object Name="GridSlot_10" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_10'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_707'"
   End Object
   Begin Object Name="GridSlot_11" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_11'"
      Padding=(Left=15.000000)
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=1
      Column=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_938'"
   End Object
   Begin Object Name="GridSlot_12" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_12'"
      Padding=(Left=15.000000,Right=15.000000)
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=1
      Column=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_1096'"
   End Object
   Begin Object Name="GridSlot_13" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_13'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=3
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_1256'"
   End Object
   Begin Object Name="GridSlot_14" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_14'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=3
      Column=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock'"
   End Object
   Begin Object Name="GridSlot_15" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_15'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=3
      Column=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_1'"
   End Object
   Begin Object Name="GridSlot_16" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_16'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=5
      Column=1
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_2'"
   End Object
   Begin Object Name="GridSlot_9" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_9'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=5
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_360'"
   End Object
   Begin Object Name="GridSlot_17" ExportPath="/Script/UMG.GridSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.GridPanel_162.GridSlot_17'"
      HorizontalAlignment=HAlign_Center
      VerticalAlignment=VAlign_Center
      Row=5
      Column=2
      Parent="/Script/UMG.GridPanel'GridPanel_162'"
      Content="/Script/UMG.TextBlock'TextBlock_4'"
   End Object
   Slots(0)="/Script/UMG.GridSlot'GridSlot_0'"
   Slots(1)="/Script/UMG.GridSlot'GridSlot_1'"
   Slots(2)="/Script/UMG.GridSlot'GridSlot_2'"
   Slots(3)="/Script/UMG.GridSlot'GridSlot_3'"
   Slots(4)="/Script/UMG.GridSlot'GridSlot_4'"
   Slots(5)="/Script/UMG.GridSlot'GridSlot_5'"
   Slots(6)="/Script/UMG.GridSlot'GridSlot_6'"
   Slots(7)="/Script/UMG.GridSlot'GridSlot_10'"
   Slots(8)="/Script/UMG.GridSlot'GridSlot_11'"
   Slots(9)="/Script/UMG.GridSlot'GridSlot_12'"
   Slots(10)="/Script/UMG.GridSlot'GridSlot_13'"
   Slots(11)="/Script/UMG.GridSlot'GridSlot_14'"
   Slots(12)="/Script/UMG.GridSlot'GridSlot_15'"
   Slots(13)="/Script/UMG.GridSlot'GridSlot_16'"
   Slots(14)="/Script/UMG.GridSlot'GridSlot_7'"
   Slots(15)="/Script/UMG.GridSlot'GridSlot_8'"
   Slots(16)="/Script/UMG.GridSlot'GridSlot_9'"
   Slots(17)="/Script/UMG.GridSlot'GridSlot_17'"
End Object
Begin Object Class=/Script/UMG.Button Name="SiparişVer_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'SiparişVer_Btn'"
      Content="/Script/UMG.Image'Image_0'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="SiparişVer_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_0" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_0'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/istockphoto-1206806317-612x612-removebg-preview.istockphoto-1206806317-612x612-removebg-preview'")
End Object
Begin Object Class=/Script/UMG.Button Name="ReklamVer_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.ReklamVer_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.ReklamVer_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.ReklamVer_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'ReklamVer_Btn'"
      Content="/Script/UMG.Image'Image_2'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="ReklamVer_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_2" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_2'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/DALL·E_2025-01-21_12_09_30_-_A_creative_concept_image_representing_the_idea_of_advertising__featuring_the_word__ADS__in_bold__modern_typography__The_word_is_placed_centrally_on_a_.DALL·E_2025-01-21_12_09_30_-_A_creative_concept_image_representing_the_idea_of_advertising__featuring_the_word__ADS__in_bold__modern_typography__The_word_is_placed_centrally_on_a_'")
End Object
Begin Object Class=/Script/UMG.Button Name="MarketGeliştir_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.MarketGeliştir_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.MarketGeliştir_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.MarketGeliştir_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'MarketGeliştir_Btn'"
      Content="/Script/UMG.Image'Image_1'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="MarketGeliştir_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_1" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_1'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/canva-pastelcore-market-sticker-MAE7AtJ6E5U.canva-pastelcore-market-sticker-MAE7AtJ6E5U'")
End Object
Begin Object Class=/Script/UMG.Button Name="Banka_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Banka_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_1" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Banka_Btn.ButtonSlot_1'"
   End Object
   Begin Object Name="ButtonSlot_1" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Banka_Btn.ButtonSlot_1'"
      Parent="/Script/UMG.Button'Banka_Btn'"
      Content="/Script/UMG.Image'Image_4'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_1'"
   DisplayLabel="Banka_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_4" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_4'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/pngtree-bank-clip-art-cartoon-style-orange-building-office-building-light-blue-png-image_2679180-removebg-preview.pngtree-bank-clip-art-cartoon-style-orange-building-office-building-light-blue-png-image_2679180-removebg-preview'")
End Object
Begin Object Class=/Script/UMG.Button Name="Casino_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Casino_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Casino_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Casino_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Casino_Btn'"
      Content="/Script/UMG.Image'Image_5'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="Casino_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_5" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_5'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/wheel-fortune-casino-background-2d-vector-illustration_1029469-207676.wheel-fortune-casino-background-2d-vector-illustration_1029469-207676'")
End Object
Begin Object Class=/Script/UMG.Button Name="Yorumlar_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Yorumlar_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_1" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Yorumlar_Btn.ButtonSlot_1'"
   End Object
   Begin Object Name="ButtonSlot_1" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Yorumlar_Btn.ButtonSlot_1'"
      Parent="/Script/UMG.Button'Yorumlar_Btn'"
      Content="/Script/UMG.Image'Image_10'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_1'"
   DisplayLabel="Yorumlar_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_10" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_10'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/resim_2025-01-21_170548177-removebg-preview.resim_2025-01-21_170548177-removebg-preview'")
End Object
Begin Object Class=/Script/UMG.Button Name="Ayarlar_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Ayarlar_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Ayarlar_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Ayarlar_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Ayarlar_Btn'"
      Content="/Script/UMG.Image'Image_7'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="Ayarlar_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_7" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_7'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/png-transparent-gear-mechanics-settings-icon-transmission-gear-wheel-wheel-mechanism-cog-rotation-thumbnail-removebg-preview.png-transparent-gear-mechanics-settings-icon-transmission-gear-wheel-wheel-mechanism-cog-rotation-thumbnail-removebg-preview'")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_707" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_707'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "D88AEAFC46AD7FE91F2233BDF1FD8A91", "Sipariş Ver")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_938" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_938'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "53FD689F417AA72D3076C9BAD7B11E38", "Market Geliştirme")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1096" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1096'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "DF5235C8455337205DEA66B03E68874C", "Reklam Ver")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1256" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1256'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "69AD0BC540F37D0000D761A66FB5010B", "Banka")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "35623DD44273FDA08021E7ABEBD01CA9", "Casino")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "6F7D2F754BD7C7262403D3B6B4649F88", "Yorumlar")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_2" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_2'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "7607A344460CE7FDAABF31B4E7CE17BF", "Ayarlar")
End Object
Begin Object Class=/Script/UMG.Button Name="Kaydet_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Kaydet_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Kaydet_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Kaydet_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Kaydet_Btn'"
      Content="/Script/UMG.Image'Image_6'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="Kaydet_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_6" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_6'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/istockphoto-1281220377-612x612-removebg-preview.istockphoto-1281220377-612x612-removebg-preview'")
End Object
Begin Object Class=/Script/UMG.Button Name="Çik_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Çik_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Çik_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Çik_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Çik_Btn'"
      Content="/Script/UMG.Image'Image_3'"
   End Object
   BackgroundColor=(R=1.000000,G=1.000000,B=1.000000,A=0.000000)
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="Çik_Btn"
End Object
Begin Object Class=/Script/UMG.Image Name="Image_3" ExportPath="/Script/UMG.Image'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Image_3'"
   Brush=(ImageType=FullColor,ImageSize=(X=128.000000,Y=128.000000),ResourceObject="/Script/Engine.Texture2D'/Game/Tex/images-removebg-preview.images-removebg-preview'")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_360" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_360'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "BA4C345548D080C71C8202848CE6124C", "Kaydet")
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_4" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_4'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "490CC392404F2862E28C77A02A3179A3", "Çık")
End Object
Begin Object Class=/Script/UMG.HorizontalBox Name="SiparişVer_HBox" ExportPath="/Script/UMG.HorizontalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox'"
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_0" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox.HorizontalBoxSlot_0'"
   End Object
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_2" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox.HorizontalBoxSlot_2'"
   End Object
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_3" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox.HorizontalBoxSlot_3'"
   End Object
   Begin Object Name="HorizontalBoxSlot_0" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox.HorizontalBoxSlot_0'"
      Parent="/Script/UMG.HorizontalBox'SiparişVer_HBox'"
      Content="/Script/UMG.VerticalBox'VerticalBox_82'"
   End Object
   Begin Object Name="HorizontalBoxSlot_2" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox.HorizontalBoxSlot_2'"
      Parent="/Script/UMG.HorizontalBox'SiparişVer_HBox'"
      Content="/Script/UMG.Spacer'Spacer_962'"
   End Object
   Begin Object Name="HorizontalBoxSlot_3" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.SiparişVer_HBox.HorizontalBoxSlot_3'"
      Parent="/Script/UMG.HorizontalBox'SiparişVer_HBox'"
      Content="/Script/UMG.WidgetSwitcher'WidgetSwitcher_0'"
   End Object
   Slots(0)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_0'"
   Slots(1)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_2'"
   Slots(2)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_3'"
   DisplayLabel="SiparişVer_HBox"
End Object
Begin Object Class=/Script/UMG.VerticalBox Name="VerticalBox_82" ExportPath="/Script/UMG.VerticalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82'"
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_1" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_1'"
   End Object
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_5" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_5'"
   End Object
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_0" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_0'"
   End Object
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_4" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_4'"
   End Object
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_2" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_2'"
   End Object
   Begin Object Name="VerticalBoxSlot_1" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_1'"
      Parent="/Script/UMG.VerticalBox'VerticalBox_82'"
      Content="/Script/UMG.Button'Dekorasyon_Btn'"
   End Object
   Begin Object Name="VerticalBoxSlot_5" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_5'"
      HorizontalAlignment=HAlign_Left
      Parent="/Script/UMG.VerticalBox'VerticalBox_82'"
      Content="/Script/UMG.Button'Geri_Sipariş_Btn'"
   End Object
   Begin Object Name="VerticalBoxSlot_0" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_0'"
      Parent="/Script/UMG.VerticalBox'VerticalBox_82'"
      Content="/Script/UMG.Button'Gida_Btn'"
   End Object
   Begin Object Name="VerticalBoxSlot_4" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_4'"
      Parent="/Script/UMG.VerticalBox'VerticalBox_82'"
      Content="/Script/UMG.Spacer'Spacer'"
   End Object
   Begin Object Name="VerticalBoxSlot_2" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.VerticalBox_82.VerticalBoxSlot_2'"
      Parent="/Script/UMG.VerticalBox'VerticalBox_82'"
      Content="/Script/UMG.Spacer'Spacer_453'"
   End Object
   Slots(0)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_0'"
   Slots(1)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_2'"
   Slots(2)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_1'"
   Slots(3)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_4'"
   Slots(4)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_5'"
End Object
Begin Object Class=/Script/UMG.Button Name="Gida_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Gida_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Gida_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Gida_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Gida_Btn'"
      Content="/Script/UMG.TextBlock'TextBlock_1550'"
   End Object
   WidgetStyle=(Normal=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000))),Hovered=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000)),OutlineSettings=(Color=(SpecifiedColor=(R=0.000000,G=0.000000,B=0.000000,A=1.000000)),RoundingType=HalfHeightRadius)),Pressed=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000))),Disabled=(TintColor=(SpecifiedColor=(R=0.000000,G=0.000000,B=0.000000,A=1.000000))))
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="Gida_Btn"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1550" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1550'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "6D26A0034559135879E8D2BC403C15FB", "Gıda")
End Object
Begin Object Class=/Script/UMG.Spacer Name="Spacer_453" ExportPath="/Script/UMG.Spacer'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Spacer_453'"
   Size=(X=1.000000,Y=5.000000)
End Object
Begin Object Class=/Script/UMG.Button Name="Dekorasyon_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Dekorasyon_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Dekorasyon_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Dekorasyon_Btn.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Dekorasyon_Btn'"
      Content="/Script/UMG.TextBlock'TextBlock_1616'"
   End Object
   WidgetStyle=(Normal=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000))),Hovered=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000)),OutlineSettings=(Color=(SpecifiedColor=(R=0.000000,G=0.000000,B=0.000000,A=1.000000)),RoundingType=HalfHeightRadius)),Pressed=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000))),Disabled=(TintColor=(SpecifiedColor=(R=0.000000,G=0.000000,B=0.000000,A=1.000000))))
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   DisplayLabel="Dekorasyon_Btn"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1616" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1616'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "62A5EC92456D78C6C8127F9B18EA28E4", "Dekorasyon")
End Object
Begin Object Class=/Script/UMG.Spacer Name="Spacer" ExportPath="/Script/UMG.Spacer'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Spacer'"
   Size=(X=1.000000,Y=5.000000)
End Object
Begin Object Class=/Script/UMG.Button Name="Geri_Sipariş_Btn" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Geri_Sipariş_Btn'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Geri_Sipariş_Btn.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Geri_Sipariş_Btn.ButtonSlot_0'"
      Padding=(Left=0.000000,Top=0.000000,Right=0.000000,Bottom=0.000000)
      Parent="/Script/UMG.Button'Geri_Sipariş_Btn'"
      Content="/Script/UMG.TextBlock'TextBlock_1705'"
   End Object
   WidgetStyle=(Normal=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000))),Hovered=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000)),OutlineSettings=(Color=(SpecifiedColor=(R=0.000000,G=0.000000,B=0.000000,A=1.000000)),RoundingType=HalfHeightRadius)),Pressed=(TintColor=(SpecifiedColor=(R=0.215861,G=0.215861,B=0.215861,A=1.000000))),Disabled=(TintColor=(SpecifiedColor=(R=0.000000,G=0.000000,B=0.000000,A=1.000000))))
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   bExpandedInDesigner=True
   DisplayLabel="Geri_Sipariş_Btn"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1705" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1705'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "DEA1FE8D4290E854D08A5C84EEA979EA", "Geri")
End Object
Begin Object Class=/Script/UMG.Spacer Name="Spacer_962" ExportPath="/Script/UMG.Spacer'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Spacer_962'"
   Size=(X=10.000000,Y=1.000000)
End Object
Begin Object Class=/Script/UMG.WidgetSwitcher Name="WidgetSwitcher_0" ExportPath="/Script/UMG.WidgetSwitcher'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher_0'"
   Begin Object Class=/Script/UMG.WidgetSwitcherSlot Name="WidgetSwitcherSlot_4" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher_0.WidgetSwitcherSlot_4'"
   End Object
   Begin Object Class=/Script/UMG.WidgetSwitcherSlot Name="WidgetSwitcherSlot_3" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher_0.WidgetSwitcherSlot_3'"
   End Object
   Begin Object Name="WidgetSwitcherSlot_4" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher_0.WidgetSwitcherSlot_4'"
      Parent="/Script/UMG.WidgetSwitcher'WidgetSwitcher_0'"
      Content="/Script/UMG.VerticalBox'Dekor_VBox'"
   End Object
   Begin Object Name="WidgetSwitcherSlot_3" ExportPath="/Script/UMG.WidgetSwitcherSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.WidgetSwitcher_0.WidgetSwitcherSlot_3'"
      Parent="/Script/UMG.WidgetSwitcher'WidgetSwitcher_0'"
      Content="/Script/UMG.VerticalBox'Gida_VBox'"
   End Object
   Slots(0)="/Script/UMG.WidgetSwitcherSlot'WidgetSwitcherSlot_3'"
   Slots(1)="/Script/UMG.WidgetSwitcherSlot'WidgetSwitcherSlot_4'"
End Object
Begin Object Class=/Script/UMG.VerticalBox Name="Gida_VBox" ExportPath="/Script/UMG.VerticalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Gida_VBox'"
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_0" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Gida_VBox.VerticalBoxSlot_0'"
   End Object
   Begin Object Name="VerticalBoxSlot_0" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Gida_VBox.VerticalBoxSlot_0'"
      Parent="/Script/UMG.VerticalBox'Gida_VBox'"
      Content="/Script/UMG.HorizontalBox'G_Ürünleri_HBox'"
   End Object
   Slots(0)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_0'"
   bExpandedInDesigner=True
   DisplayLabel="Gida_VBox"
End Object
Begin Object Class=/Script/UMG.HorizontalBox Name="G_Ürünleri_HBox" ExportPath="/Script/UMG.HorizontalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.G_Ürünleri_HBox'"
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_0" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.G_Ürünleri_HBox.HorizontalBoxSlot_0'"
   End Object
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_2" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.G_Ürünleri_HBox.HorizontalBoxSlot_2'"
   End Object
   Begin Object Name="HorizontalBoxSlot_0" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.G_Ürünleri_HBox.HorizontalBoxSlot_0'"
      Parent="/Script/UMG.HorizontalBox'G_Ürünleri_HBox'"
      Content="/Script/UMG.Button'Test'"
   End Object
   Begin Object Name="HorizontalBoxSlot_2" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.G_Ürünleri_HBox.HorizontalBoxSlot_2'"
      Parent="/Script/UMG.HorizontalBox'G_Ürünleri_HBox'"
      Content="/Script/UMG.TextBlock'TextBlock_1835'"
   End Object
   Slots(0)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_2'"
   Slots(1)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_0'"
   bExpandedInDesigner=True
   DisplayLabel="G_Ürünleri_HBox"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_1835" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_1835'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "83EFF14E4D7EAABE99D4F9A1C5AC6A74", "Ürünler...")
End Object
Begin Object Class=/Script/UMG.Button Name="Test" ExportPath="/Script/UMG.Button'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Test'"
   Begin Object Class=/Script/UMG.ButtonSlot Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Test.ButtonSlot_0'"
   End Object
   Begin Object Name="ButtonSlot_0" ExportPath="/Script/UMG.ButtonSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Test.ButtonSlot_0'"
      Parent="/Script/UMG.Button'Test'"
      Content="/Script/UMG.TextBlock'TextBlock_276'"
   End Object
   Slots(0)="/Script/UMG.ButtonSlot'ButtonSlot_0'"
   bExpandedInDesigner=True
   DisplayLabel="Test"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_276" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_276'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "69A4B8514F25270CC4699D91A9834CD1", "Test Spawn")
End Object
Begin Object Class=/Script/UMG.VerticalBox Name="Dekor_VBox" ExportPath="/Script/UMG.VerticalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Dekor_VBox'"
   Begin Object Class=/Script/UMG.VerticalBoxSlot Name="VerticalBoxSlot_0" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Dekor_VBox.VerticalBoxSlot_0'"
   End Object
   Begin Object Name="VerticalBoxSlot_0" ExportPath="/Script/UMG.VerticalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.Dekor_VBox.VerticalBoxSlot_0'"
      Parent="/Script/UMG.VerticalBox'Dekor_VBox'"
      Content="/Script/UMG.HorizontalBox'D_Ürünleri_HBox'"
   End Object
   Slots(0)="/Script/UMG.VerticalBoxSlot'VerticalBoxSlot_0'"
   bExpandedInDesigner=True
   DisplayLabel="Dekor_VBox"
End Object
Begin Object Class=/Script/UMG.HorizontalBox Name="D_Ürünleri_HBox" ExportPath="/Script/UMG.HorizontalBox'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.D_Ürünleri_HBox'"
   Begin Object Class=/Script/UMG.HorizontalBoxSlot Name="HorizontalBoxSlot_2" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.D_Ürünleri_HBox.HorizontalBoxSlot_2'"
   End Object
   Begin Object Name="HorizontalBoxSlot_2" ExportPath="/Script/UMG.HorizontalBoxSlot'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.D_Ürünleri_HBox.HorizontalBoxSlot_2'"
      Parent="/Script/UMG.HorizontalBox'D_Ürünleri_HBox'"
      Content="/Script/UMG.TextBlock'TextBlock_3'"
   End Object
   Slots(0)="/Script/UMG.HorizontalBoxSlot'HorizontalBoxSlot_2'"
   bExpandedInDesigner=True
   DisplayLabel="D_Ürünleri_HBox"
End Object
Begin Object Class=/Script/UMG.TextBlock Name="TextBlock_3" ExportPath="/Script/UMG.TextBlock'/Game/Widget/W_TabletUI.W_TabletUI:WidgetTree.TextBlock_3'"
   Text=NSLOCTEXT("[38B2D6258797B9B993B31D750A43D517]", "5B4BF62B473E9B6F153A73ABECD90996", "Ürünler...")
End Object

