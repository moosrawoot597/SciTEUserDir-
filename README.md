# SciTEUserDir-
If EnvGet("SCITE_USERHOME") &lt;> "" And FileExists(EnvGet("SCITE_USERHOME")) Then         $SciTEUserDir = EnvGet("SCITE_USERHOME")     ElseIf EnvGet("SCITE_HOME") &lt;> "" And FileExists(EnvGet("SCITE_HOME")) Then         $SciTEUserDir = EnvGet("SCITE_HOME")     Else         $SciTEUserDir = @UserProfileDir ; original sciTE default location     EndIf
