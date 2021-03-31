# enumClassIn

This is a small Qt dialog program simply put together from pieces found through some Google searches and/or YouTUBE video tutorials on Qt (see the links below). The program will show a ComboBox filled with a list of data from an enum class called RSSElement. The enum class RSSElement resides IN the Dialog class and that makes it a nested enum class inside (to local) a class. When an entry listed in the ComboBox is selected, it will be shown under the "Selected setting" (below the ComboBox). The Save button that makes use of the QSetting class is used to retain the setting.

1. Convert Enum to QString (https://srikanthsombhatla.wordpress.com/2010/08/13/convert-enum-to-qstring)
2. QSettings (https://www.youtube.com/watch?v=TNIkeFfzH-g)
3. QComboBox (https://www.youtube.com/watch?v=5Lb8DZhAAi8)
