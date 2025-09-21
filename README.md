# guiBasic - GUI for CerberusX

- [x] This guiBasic previously known as MyGui was created by **Christopher Challenger** in 2012.
- [x] It was converted from MonkeyX to CerberusX by **Memzen** in 2019
- [x] Add support to Cerberus X Font by **Mag** in 2022 :tada:
- [x] Add support to Cerberus X Mojo2 by **bosh77** in 2025 :tada:

![](https://github.com/zomagic/guiBasic/blob/main/guiBasic.gif)
![](https://github.com/zomagic/guiBasic/blob/main/screenshot%20of%20examples.jpg)

After unzipping the downloaded file, copy the guiBasic folder into the modules_ext directory for use with mojo, and copy the guiBasic2 folder into the same directory for use with mojo2. Do the same with the sample folders: the Examples folder contains mojo examples, while the Examples2 folder contains mojo2 examples.

At the beginning of your code (mojo example):

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
