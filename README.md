# aspx-for-value.
$Res_Gui_2 = GUICreate($lang[22], 390, 470, -1, -1, -1) ; DLL Info $FileVersion_Title = GUICtrlCreateLabel($lang[23] &amp; " :", 110, 8, 171, 28) ; DLL Informations GUICtrlSetFont(-1, 14, 800, 0, "MS Sans Serif") GUICtrlCreateLabel($lang[24], 15, 60, 125, 20) ; Dll Filename GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_File_Name = GUICtrlCreateInput($lang[25], 175, 60, 140, 21) ; MyDll GUICtrlCreateLabel(".Dll", 318, 63, 30, 20) GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") GUICtrlCreateLabel($lang[26], 16, 92, 130, 20) ; File Version GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_Ver1 = GUICtrlCreateInput("01", 175, 92, 35, 21, BitOR($ES_AUTOHSCROLL, $ES_NUMBER)) $UpD1 = GUICtrlCreateUpdown(-1) GUICtrlSetLimit(-1, 99, 01) $Dll_Ver2 = GUICtrlCreateInput("00", 220, 92, 35, 21, BitOR($ES_AUTOHSCROLL, $ES_NUMBER)) $UpD2 = GUICtrlCreateUpdown(-1) GUICtrlSetLimit(-1, 99) $Dll_Ver3 = GUICtrlCreateInput("0000", 265, 92, 49, 21, BitOR($ES_AUTOHSCROLL, $ES_NUMBER)) $UpD3 = GUICtrlCreateUpdown(-1) GUICtrlSetLimit(-1, 9999) $Dll_Ver4 = GUICtrlCreateInput("0000", 325, 92, 49, 21, BitOR($ES_AUTOHSCROLL, $ES_NUMBER)) $UpD4 = GUICtrlCreateUpdown(-1) GUICtrlSetLimit(-1, 9999) GUICtrlCreateLabel($lang[27], 16, 127, 150, 20) ; Product Version GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_PVer1 = GUICtrlCreateLabel("01,00,0000,0000", 175, 130, 90, 20) $Dll_PVer2 = GUICtrlCreateInput("", 265, 127, 110, 21) GUICtrlCreateLabel($lang[28], 16, 165, 150, 20) ; Product Name GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_Prod_Name = GUICtrlCreateInput($lang[29], 175, 165, 200, 21) ; Name_Of_Your_Product GUICtrlCreateLabel($lang[30], 16, 200, 150, 20) ; Compagny Name GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_Compagny = GUICtrlCreateInput($lang[31], 175, 200, 200, 21) ; Type_Your_Company GUICtrlCreateLabel($lang[32], 16, 235, 150, 20) ; Legal Copyright GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_Copyright = GUICtrlCreateInput($lang[33], 175, 235, 200, 21) ; Copyright_(C)_2007-2008 GUICtrlCreateLabel($lang[34], 16, 270, 150, 20) ; File Description GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_File_Desc = GUICtrlCreateInput($lang[35], 175, 270, 200, 21) ; Type_Your_Description GUICtrlCreateLabel($lang[36], 16, 305, 150, 20) ; Language GUICtrlSetFont(-1, 10, 800, 0, "MS Sans Serif") $Dll_Lang = GUICtrlCreateCombo("", 175, 305, 90, 25, BitOR($CBS_DROPDOWNLIST, $CBS_AUTOHSCROLL)) GUICtrlSetData(-1, $lang[37], $lang[38]) ; English|French ; English ; See http://msdn.microsoft.com/en-us/library/aa381058%28VS.85%29.aspx for value.
