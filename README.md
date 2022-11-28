# Cool UI probably made by Enxquity

Create a UI: Lib.UI(Name)

Create a tab: UI:Tab(Name, Icon)

Create a container: Tab:Container(Name)

Create a button: Container:Button(Name, Callback) [no return]

Create a toggle: Container:Toggle(Name, StartingState, Callback) [returns state]

Create a dropdown: Container:Dropdown(Name, List [contains strings], Callback) [returns selected string from table]

Create a label: Container:Label(Text) [no return]

Create a keybind: Container:Keybind(Name, Starting_Key, Blacklisted_Keys [contains strings], Callback) [returns key string form (example: "A")]

Create a textbox: Container:TextBox(Name, Callback) [returns text in textbox]

Create a slider: Container:Slider(Name, Min, Max, Start, Callback, Use_Decimals) [returns selected number]

Create a notification: Lib:Notification(Title, Info, Icon, Duration) [limit of 5 notifications being shown (can be edited in source)]
![image](https://user-images.githubusercontent.com/114941534/204367838-2954fc26-5dd1-43f5-b0a4-1b88d198ed64.png)
