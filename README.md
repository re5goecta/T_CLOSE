# T_CLOSE
-1)&lt;BR>GUISetBkColor(0xFFFF00)&lt;BR>$List1 = GUICtrlCreateList("", 56, 384, 401, 86)&lt;BR>GUICtrlSetData(-1, "1.exe|2.exe|3.exe|4.exe|5.exe")&lt;BR>GUISetState(@SW_SHOW)&lt;BR>#EndRegion ### END Koda GUI section ###&lt;/P> &lt;P>While 1&lt;BR>&amp;nbsp;$nMsg = GUIGetMsg()&lt;BR>&amp;nbsp;Switch $nMsg&lt;BR>&amp;nbsp;&amp;nbsp;Case $GUI_EVENT_CLOSE&lt;BR>&amp;nbsp;&amp;nbsp;&amp;nbsp;Exit&lt;/P> &lt;P>&amp;nbsp;EndSwitch&lt;BR>WEnd&lt;/P>
