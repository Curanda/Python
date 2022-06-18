wys = int(input('Write cuboid height : '))
szer = int(input('Write cuboid width : '))
dlugosc = int(input('Write cuboid length : '))

objetosc = wys*szer*dlugosc
pole = (2*(wys*szer))+(2*(dlugosc*szer))+(2*(wys*dlugosc))
print(f"Surface size of this cuboid is : {pole}\nand it's volume is {objetosc}")
