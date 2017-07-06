# FlatToggleSwitch
Flat toggle switch control for UWP

```xaml
<Page
    ...
    xmlns:esgee="using:esgeeFlatToggleSwitch">
    <StackPanel>
        <esgee:FlatToggleSwitch Margin="0,5"/>
        <esgee:FlatToggleSwitch IsOn="True"/>

        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" Margin="0,5"/>
        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" TextColor="Yellow" 
                                ButtonColor="Yellow" IsOn="True"/>

        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" OffBgColor="Purple"
                                SwitchWidth="120" ContentAlignment="Stretch" Margin="0,5"/>
        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" OnBgColor="Blue"
                                SwitchWidth="120" ContentAlignment="Center" IsOn="True"/>

        <esgee:FlatToggleSwitch OnContent="✓" OffContent="✘" Margin="0,5"/>
        <esgee:FlatToggleSwitch OnContent="✓" OffContent="✘" IsOn="True"/>
    </StackPanel>
</Page>
```  
            
**On/Off Switch**  
![ON OFF Switch](https://github.com/ersuman/FlatToggleSwitch/blob/master/OnOff1.PNG)

**Enabled/Disabled Switch**  
![](https://github.com/ersuman/FlatToggleSwitch/blob/master/EnabledD.PNG)

```xaml
<esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" OffBgColor="Purple"
                                    SwitchWidth="120" ContentAlignment="Stretch" Margin="0,5"/>
```
![](https://github.com/ersuman/FlatToggleSwitch/blob/master/disabledPurple.PNG)

```xaml
<esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" OnBgColor="Blue"
                                    SwitchWidth="120" ContentAlignment="Center" IsOn="True"/>
```
![](https://github.com/ersuman/FlatToggleSwitch/blob/master/enabled%20blue.PNG)

**Button with special symbol as content (Unicode)**
                              
![](https://github.com/ersuman/FlatToggleSwitch/blob/master/tickCross.PNG)


**Properties**
```
bool: IsOn
Brush: OnBgColor, OffBgColor, BgColor, ButtonColor, TextColor
string: OnContent, OffContent, Content
double: SwitchWidth (default is auto width)
double: Size >> changes switch size and font size
double: ContentFontSize >> Font size of displayed text
ContentAlignment >> Center, Stretch
```

**Event**
```
Toggled
```
