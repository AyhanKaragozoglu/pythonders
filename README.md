# pythonders
tekrar olanlar tek birisi ele alınır
[ ]
 colors = "red", "blue", "pink", "red", "white", "blue", "purple"
[ ]
 set(colors)
 {'blue', 'pink', 'purple', 'red', 'white'}
[ ]
 ilk_kümem = {1, 1,2, 0, 1}
ilk_kümem
 {0, 1, 2}
liste de elemenler tekrar etse de sayılır.
[ ]
 len([1, 1, 2 ,0, 1])
 5
[ ]
 len({1, 1, 2 ,0, 1})
 3
[3]
0 sn.
letters = "a b c d e f g h ı j k l m n o p r s t u v y z".split()
print(letters)
 ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'ı', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'r', 's', 't', 'u', 'v', 'y', 'z']
[4]
0 sn.
print(set(letters))
 {'j', 'r', 'a', 'p', 'v', 'b', 'e', 'l', 'n', 'u', 'o', 'k', 'g', 'z', 'y', 'ı', 't', 'h', 's', 'm', 'd', 'f', 'c'}
[5]
0 sn.
print(set(letters))
 {'j', 'r', 'a', 'p', 'v', 'b', 'e', 'l', 'n', 'u', 'o', 'k', 'g', 'z', 'y', 'ı', 't', 'h', 's', 'm', 'd', 'f', 'c'}
[7]
0 sn.
given_list = [1, 2, 3, 4, 5, 6]
kümemiz = {given_list}
 
[8]
0 sn.
{  [1, "bir"], "ali", "deli"}
 
[9]
0 sn.
{{1: "bir"}, 2, 3 }
 
[10]
0 sn.
{1, 2, {"ali", "veli", 3, 4 }}
 
[12]
0 sn.
tuple_set = {1, 2, (3, 4)}
tuple_set
 {(3, 4), 1, 2}
Main Operations with Sets
# Bu, kod olarak biçimlendirilmiştir
[17]
0 sn.
a = {'carnation', 'orchid', 'rose', 'violet'}
b = {'rose', 'orchid', 'rose', 'violet', 'carnation'}

b
 {'carnation', 'orchid', 'rose', 'violet'}
[18]
0 sn.
a
 {'carnation', 'orchid', 'rose', 'violet'}
[20]
0 sn.
a.add("lily")
a
 {'carnation', 'lily', 'orchid', 'rose', 'violet'}
[21]
0 sn.
a.remove("rose")
a
 {'carnation', 'lily', 'orchid', 'violet'}
[22]
0 sn.
c = set("philadelphia")
d = set("dolphin")
print(c)
print(d)
 {'e', 'l', 'd', 'a', 'h', 'i', 'p'}
{'l', 'n', 'h', 'i', 'd', 'p', 'o'}
[23]
0 sn.
print(c-d)
print(c.difference(d))
 {'e', 'a'}
{'e', 'a'}
[24]
0 sn.
print(c|d)
print(c.union(d))
 {'e', 'l', 'n', 'a', 'h', 'i', 'd', 'p', 'o'}
{'e', 'l', 'n', 'a', 'h', 'i', 'd', 'p', 'o'}
[25]
0 sn.
print(c&d)
print(c.intersection(d))
 {'l', 'h', 'i', 'd', 'p'}
{'l', 'h', 'i', 'd', 'p'}
set fonksiyonu elmanları tek tek alıp set oluşturuyor
manuel yazdığımızda her bir virgüle bir eleman atıyor, virgül yoksa tek elman yapıyor.
[26]
0 sn.
date = set("10/26/2022")
date2 = {'10/26/2022'}
[27]
0 sn.
date
 {'/', '0', '1', '2', '6'}
[28]
0 sn.
date2
 {'10/26/2022'}
[29]
0 sn.
date1 = set('05/21/2022')
date2 = {'05/21/2022'}
print(date1)
print(date2)
 {'1', '/', '2', '0', '5'}
{'05/21/2022'}
[30]
0 sn.
my_list = [1, 2, 3, 3, 3, 3, 4, 4, 5, 5]
e = set(my_list)
[31]
 e
 {1, 2, 3, 4, 5}
[33]
0 sn.
f = list(e)
f
 [1, 2, 3, 4, 5]
[35]
0 sn.
from types import new_class

new_zealand = set("Wellington")
usa = set("Washington")
print(new_zealand-usa)
print(usa-new_zealand)
 {'e', 'l'}
{'a', 'h', 's'}
[36]
0 sn.
k1 = set([1, 2, 3])
k2 = set([1, 3, 5])
k1.difference_update(k2)
print(k1)
 {2}
[37]
0 sn.
hayvanlar = set(["kedi","köpek", "at", "kuş", "inek", "deve"])
hayvanlar.discard("kedi")
print(hayvanlar)
 {'inek', 'at', 'köpek', 'deve', 'kuş'}
[38]
0 sn.
hayvanlar.remove("köpek")
print(hayvanlar)
 {'inek', 'at', 'deve', 'kuş'}
remove eleman yoksa hata verir.
[39]
0 sn.
hayvanlar.remove("köpek")print(hayvanlar)

 
[ ]
 
şartlara bağlı durumların incelenmesi
[40]
0 sn.
sayılar = [1, 2, 3, 4, 5]print(sayılar[0])

 1
[41]
0 sn.
print(sayılar[0])

 1
[42]
0 sn.
print(sayılar[1])

 2
[43]
0 sn.
print(sayılar[2])

 3
[44]
0 sn.
print(sayılar[3])

 4
[45]
0 sn.
print(sayılar[4])

 5
