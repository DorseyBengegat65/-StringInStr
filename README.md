# -StringInStr
     ; That failed - so we try four characters.     For $i = 1 To $aDoubleChar[0]         For $j = 1 To $aDoubleChar[0]             $sDelim = $aDoubleChar[$i] &amp; $aDoubleChar[$j]             If Not StringInStr($sTest, $sDelim, 1) Then Return $sDelim         Next
