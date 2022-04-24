# guiBasic - GUI for CerberusX

- [x] This guiBasic previously known as MyGui was created by **Christopher Challenger** in 2012.
- [x] It was converted from MonkeyX to CerberusX by **Memzen** in 2019
- [x] Add support to Cerberus X Font by **ZoMagic** in 2022 :tada:

![](https://github.com/zomagic/guiBasic/blob/main/guiBasic.gif)
![](https://github.com/zomagic/guiBasic/blob/main/gscreenshot of examples.jpg)

Unzip the downloaded file and copy the *guiBasic* folder into your CerberusX *modules_ext* folder

At the beginning of your code:

`Import guiBasic`

In your OnUpdate() method:

`Gui.Update()`

In Your OnRender() method:

`Gui.Draw()`
 
```
Import mojo
Import guiBasic
Function Main();New Game;End Function
Class Game Extends App
	Method OnCreate()
		SetUpdateRate(60)
	End Method
	Method OnUpdate()
		Gui.Update()
	End Method
	Method OnRender()
		Cls(200,200,200)
		Gui.Draw()
	End Method
End Class
```
