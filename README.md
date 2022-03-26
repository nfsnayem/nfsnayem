# Data Types ---
a = "Pythan"
b = 4
c = 4.56
d = 20j
print(a, type(a))
print(b, type(b))
print(c, type(c))
print(d, type(d))
# Sequence type----
x = ["apple", "banana", "cherry"]
y = ("king", "khan", "boss")
z = range(6)

print(x, type(x))
print(y, type(y))
print(z, type(z))

# Mapping Type---
q = {"name" : "nayem", "age" : 36}
print(q, type(q))

#  set type----
o = {"apple", "banana", "cherry"}
p = frozenset({"nayem", "king is", "back"})

print(o, type(o))
print(p, type(p))

#Boolean type---

k = True
print(k, type(k))

#binar types----
r = b'hello'
print(r, type(r))

u = bytearray(10)
print(u, type(u))

mn = memoryview(bytes(20))
print(mn, type(mn))
