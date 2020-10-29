# crispy-giggle
Hello everyone
d={'r':556,'nm':'fycs','branch':'cs'}
print(d)
print(d['r'])
d2=d.copy()
print(d2)
key=(1,2,33)
d3=d.fromkeys(key,5)
print(d3)
x=d.get('r')
print(x)
print(d.items())
d.update({'q':34533})
print(d)
x2=d.setdefault('r')
print(x2)
d.pop('r')
print(d)

