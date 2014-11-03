Color palettes
=============

Here are some useful color palettes I have collected from various sources or adapted for myself.

This repo also contains a file, [colorcollection.py](colorcollection.py), with all of these schemes in a python class. For example, to use the **Twelve dark** palette as a python scheme:

    from colorcollection.py import *
    colrcoll = ColorCollection()
    dark12 = colrcoll.dark12

### Twelve dark ###

Twelve dark contrasting colors that I've used for line charts, to make sure each data series can be distinguished from the others. If you have more than 12 data series... well, you need to have fewer data series, IMO.

The colors are dark-ish so that they will work against a white or a light grey background. Other light pastel backgrounds should work as well.

    ['#BB2114', '#0C5966', '#BA7814', '#4459AB', '#6B3838', 
     '#B8327B', '#2B947F', '#0D83B5', '#684287', '#8C962C', 
     '#92289E', '#242D7D']

![My 12](twelve_dark.png)

 [Visit a web tool](http://www.colorcombos.com/combomaker.html?design=squares&output_width=70&size_option=element&colors=BB2114,0C5966,BA7814,4459AB,6B3838,B8327B,2B947F,0D83B5,684287,8C962C,92289E,242D7D&background_color=FFFFFF&show_hex_flag=Y) that shows these colors.


### Alan Gilbertson's 24 colors ###

(28 colors if you include grey)

    ['#ff0000', '#b00000', '#870000', '#550000', '#e4e400', 
     '#baba00', '#878700', '#545400', '#00ff00', '#00b000', 
     '#008700', '#005500', '#00ffff', '#00b0b0', '#008787', 
     '#005555', '#b0b0ff', '#8484ff', '#4949ff', '#0000ff', 
     '#ff00ff', '#b000b0', '#870087', '#550055', '#e4e4e4', 
     '#bababa', '#878787', '#545454']

From [this StackExchange post](http://graphicdesign.stackexchange.com/questions/3682/large-color-set-for-coloring-of-many-datasets-on-a-plot)

![A.G. 24](alan_gilbertsons_24_colors_without_grey.png)

### 3. More pastel-y ColorBrewer Paired ###

I modified the ColorBrewer Paired set to be more pastel-like

    ['#a6cee3', '#5c9dc9', '#b2df8a', '#6accb3', '#fb9a99', '#e56969',
     '#fdbf6f', '#ff7f00', '#c397db', '#a868c4', '#e5e5a0', '#c47a52']

![Paired Pastel](cbpairedpastel.png)

### Tableau 10 ###

    ['#1f77b4', '#ff7f0e', '#2ca02c', '#d62728', '#9467bd', '#8c564b', '#e377c2', '#7f7f7f', '#bcbd22', '#17becf']
	
![Tableau 10](tableau10.png)

### Tableau 20 ###

	['#1f77b4', '#aec7e8', '#ff7f0e', '#ffbb78', '#2ca02c', '#98df8a', '#d62728', '#ff9896', '#9467bd', '#c5b0d5', '#8c564b', '#c49c94', '#e377c2', '#f7b6d2', '#7f7f7f', '#c7c7c7', '#bcbd22', '#dbdb8d', '#17becf', '#9edae5']
	
![Tableau 20](tableau20.png)

### Datavisualization.ch 12 colors paired ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#5884b3', '#b6cee5', '#cc6686', '#e5b5c5', '#e87b70', '#f2cec1', '#e5cf6c', '#f9ebaa', '#91be64', '#cee5b5', '#5bbe94', '#b6e4d1']

![Datavisualization.ch 12 paired](dvz12.png)

### Datavisualization.ch blue-white-red diverging ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#3775b3', '#6792c4', '#94b2d3', '#c4d2e2', '#f1f1f1', '#e9cdd2', '#e0a9b0', '#d68390', '#cc5f6f']

![Datavisualization.ch bwr](dvz9bwr.png)

### Datavisualization.ch blue-white ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#343e4e', '#354d67', '#365a81', '#376799', '#3775b3', '#6191c7', '#89add9', '#b3c9eb', '#dce8fd']

![Datavisualization.ch bw](dvz9bw.png)

### Datavisualization.ch red-white ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#4e3539', '#6d4047', '#8c4954', '#ad5461', '#cc5f6f', '#d9828e', '#e4a6ac', '#f1c7cc', '#fcebeb']

![Datavisualization.ch bw](dvz9rw.png)

### Datavisualization.ch neutral diverging ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#47807b', '#739c99', '#9db8b7', '#c7d4d3', '#f1f1f1', '#dfd3cc', '#cdb7a5', '#b99a7e', '#a57c57']

![Datavisualization.ch neutral](dvz9n.png)

### Datavisualization.ch neutral blue-white ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#2c3b3e', '#334d4e', '#395e5e', '#416e6c', '#47807b', '#6b9692', '#8caeac', '#adc5c5', '#d1dedd']

![Datavisualization.ch nbw](dvz9nbw.png)

### Datavisualization.ch neutral red-white ###

From http://datavisualization.ch/inside/how-we-created-color-scales/

	['#4b3735', '#62483c', '#7a5a45', '#906b4f', '#a57c57', '#b79377', '#c7ac95', '#d6c5b5', '#e8ded3']

![Datavisualization.ch bw](dvz9nrw.png)

### Solarized monotone ###

From http://ethanschoonover.com/solarized

	['#002b36', '#073642', '#586e75', '#657b83', '#839496', '#93a1a1', '#eee8d5', '#fdf6e3']
	
![Solarized monotone](solarized_mono.png)

### Solarized accents ###

From http://ethanschoonover.com/solarized

	['#b58900', '#cb4b16', '#dc322f', '#d33682', '#6c71c4', '#268bd2', '#2aa198', '#859900']
	
![Solarized accents](solarized_acc.png)
	

