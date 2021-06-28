# Mongolian-text-recognition
The Mongolian alphabet of this dataset is "ᠴ᠊ᠬ ᠲᠵᠺ ᠷᠯᠢ᠎ᠫ ᠾ ᠱ ᠹ ᠽᠸᠧᠣᠪ ᠥᡁᠡᠰ ᠨ ᠤᠠᠼᠳ ᠦᠩ ᠶ ᠭ᠍ᠮ᠋ ᠦ‍﻿".
The data of this work comes from the China Mongolian News Network(http://www.mgyxw.net), which automatically divides Mongolian pictures into individual words by writing a 
Python script, and saves them as images after binarization. The dataset has a total of 30326 origin Mongolian text pictures, and the vocabulary is 6538.
We use rotation, horizontal wave, distortion, and perspective methods to distort the Mongolian data. After data augmentation, the dataset has 98,085 Mongolian pictures.
Mongolian-Regular3W.rar is the original data.
Mongolian-Irregular0.65W.rar is the data that each vocabulary is enhanced once.
Mongolian-Irregular6.5W.rar is the enhanced data of Mongolian-Regular3W.rar.
