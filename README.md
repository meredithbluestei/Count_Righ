# Count_Righ
ToolTip("") EndIf ElseIf $aHit[0] = $i And $aHit[1] = 1 Then ToolTip("") ElseIf $aHit[0] = $i And $aHit[1] = 2 Then ToolTip("") ElseIf $aHit[0] = $i And $aHit[1] = 3 Then ToolTip("") ElseIf $aHit[0] = $i And $aHit[1] = 4 Then ToolTip("") #include &lt;GuiConstantsEx.au3> #include &lt;WindowsConstants.au3> #include "GUIListViewEx.au3" #include &lt;Array.au3> ; Just for display in example Global $iCount_Left = 20, $iCount_Right = 40, $vData, $aRet, $iEditMode = 0 ; Create GUI $hGUI = GUICreate("LVEx Example 4", 640, 430)
