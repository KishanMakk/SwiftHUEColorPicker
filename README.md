<h4>SwiftHUEColorPicker</h4>

Simple iOS HUE color picker.</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img1.png)
</br><b>Manual installation:</b>
<pre>
Copy SwiftHUEColorPicker.swift to your project.
</pre>

<b>Cocoapods:</b>
<pre>
pod 'SwiftHUEColorPicker'
</pre>
</br>Supports two modes: horizontal and vertical.</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img2.png)
</br>Also you can change saturation, brightness and alpha values.
</br>And control has customization. You can customize the label:</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img3.png)
</br>Or appearance:</br>
</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img4.png)
</br>
</br>
<b>How to use:</b>
</br></br>You can create from storyboard or XIB. Or create manually:
<pre>
let picker = SwiftHUEColorPicker()
</pre>

For handling changing of values you should implement protocol SwiftHUEColorPickerDelegate.
<pre>
picker.delegate = self

func valuePicked(color: UIColor, type: SwiftHUEColorPicker.PickerType) {
}
</pre>

Direction:
<pre>
picker.direction = SwiftHUEColorPicker.PickerDirection.Vertical // Vertical and horizontal
</pre>

Type:
<pre>
picker.type = SwiftHUEColorPicker.PickerType.Color // Color, Saturation, Brightness, Alpha
</pre>

