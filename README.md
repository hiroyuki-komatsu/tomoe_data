# tomoe_data: Japanese Handwriting Stroke Data.

[Tomoe](https://sourceforge.net/projects/tomoe/) is a handwriting recognition tool, I ([Hiroyuki Komatsu](https://github.com/hiroyuki-komatsu/)) originally created and later handed over to other project contributors.

This repository (https://github.com/hiroyuki-komatsu/tomoe_data/) contains the stroke data that was part of my own contribution to the project.

## License

This tomoe_data is available under a dual liceses. You may choose the license that best fits your needs:

* Apache License 2.0
* CC BY 4.0

### How to cite

```
tomoe_data by Hiroyuki Komatsu, available at https://github.com/hiroyuki-komatsu/tomoe_data/
```

## Format

```
<Character in UTF-8>
:<Number of strokes>
<Number of coordicates of stroke1> (<X1> <Y1>) (<X2> <Y2>) ... (<Xn> <Yn>)
<Number of coordicates of stroke2> (<X1> <Y1>) (<X2> <Y2>) ... (<Xn> <Yn>)

```

```
あ
:3
2 (54 58) (249 68) 
3 (147 10) (145 201) (182 252) 
9 (224 103) (149 230) (82 240) (53 204) (86 149) (182 139) (240 172) (248 224) (228 250) 

い
:2
4 (56 63) (43 213) (67 259) (94 243) 
3 (213 66) (231 171) (208 217) 

う
:2
2 (102 35) (187 45) 
5 (73 121) (167 105) (206 139) (198 211) (135 275) 

```

X and Y range from 0 to 320.
