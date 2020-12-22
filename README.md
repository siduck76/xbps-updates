# xbps-updates
xbps-updates checker module for polybar <br>
<img src="https://raw.githubusercontent.com/siduck76/xbps-updates/master/dd_001.png">

[module/updates]
type = custom/script<br>
exec = xbps-updates<br>
format = <label><br><br>
format-prefix = 󰳡<br>
format-prefix-foreground = #DE8C92<br>
interval = 3600 <br>
label = %output% <br>
label-padding = 1<br>
format-foreground = #D8DEE9  <br>   

[module/reposync]<br>
type = custom/script<br>
exec = doas xbps-install -S<br>
format =<br>
interval = 3600 <br>
label = <br>
