# FlatToggleSwitch
Flat toggle switch control for UWP

```xaml
<Page
    ...
    xmlns:esgee="using:esgeeFlatToggleSwitch">
    <StackPanel>
        <!-- Switch with default content (ON/OFF) -->
        <esgee:FlatToggleSwitch Margin="0,5"/>
        <esgee:FlatToggleSwitch IsOn="True"/>

        <!--Switch with custom content (Enabled/Disabled) -->
        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" Margin="0,5"/>
        <!--Toggle Switch with Custom color for text and button -->
        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" TextColor="Yellow" 
                                ButtonColor="Yellow" IsOn="True"/>

        <!-- you can also adjust switch width, content alignment -->
        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" OffBgColor="Purple"
                                SwitchWidth="120" ContentAlignment="Stretch" Margin="0,5"/>
        <esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" OnBgColor="Blue"
                                SwitchWidth="120" ContentAlignment="Center" IsOn="True"/>

        <!--Toggle Switch also supports special symbol as content (Unicode) -->
        <esgee:FlatToggleSwitch OnContent="✓" OffContent="✘" Margin="0,5"/>
        <esgee:FlatToggleSwitch OnContent="✓" OffContent="✘" IsOn="True"/>
    </StackPanel>
</Page>
```  
            
**Switch with default content (ON/OFF)**  
![ON OFF Switch](https://github.com/ersuman/FlatToggleSwitch/blob/master/OnOff1.PNG)

**Switch with custom content (Enabled/Disabled)**  
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


**Toggle Switch with Custom color for text and button**

![](https://github.com/ersuman/FlatToggleSwitch/blob/master/enabled%20green%20yellow.PNG)

```xaml
<esgee:FlatToggleSwitch OnContent="Enabled" OffContent="Disabled" IsOn="True"
                        TextColor="Yellow" ButtonColor="Yellow" SwitchWidth="120"  />
```

**Toggle Switch with special symbol as content (Unicode)**
                              
![](https://github.com/ersuman/FlatToggleSwitch/blob/master/tickCross.PNG)


**Properties**

bool: `IsOn`

Brush: `OnBgColor`, `OffBgColor`, `BgColor`, `ButtonColor`, `TextColor`

string: `OnContent`, `OffContent`, `Content`

double: `SwitchWidth` (default is auto width)

double: `Size` >> changes switch size and font size

double: `ContentFontSize` >> Font size of displayed text

`ContentAlignment` >> *Center* (allign text at center), *Stretch* (allign text near the button)


**Event**

`Toggled`


*Don't forget to give Star if you liked it.*

