import math

promienKola = int(input('Write circle radius : '))

pole = math.pi*(promienKola**2)
obwod = 2*math.pi*promienKola

print(f"Surface size of this circle is : {pole:0.6}\nand it's circuit is {obwod:0.5}")
