# permutasyon
 Örnek Permütasyon probleminin python diliyle çözülmesi

Permütasyon ,n pozitif tamsayı, r doğal sayı ve r ≤n olmak üzere, n elemanlı bir kümenin r elemanlı sıralı r’lilerine o kümenin r’li permütasyonu olarak tanımlayabiliriz.n tane farklı nesnemiz var. bu n tane nesneden r tanesini aynı anda seçiyor ve sıralıyoruz, yani sıralı r’li oluşturuyoruz, işte bu sıralamaya n’in r’li permütasyonu denir. Permütasyonda diziliş önemlidir.

P(n,r) = n!/(n−r)! n adet nesneden r tanesini seçip sıralamanın formülüdür. Konuyu bir örnekle pekiştirelim.

Problem :Oğuz={1,2,3,4,5,6} kümesinin dörtlü permütasyonlarının kaçında 5 veya 6 bulunur ?

Çözüm : Öncelikle kümenin toplam eleman sayısının 4'lü permütasyonu bulunur. P(6,4) 654*3 = 360

Akabinde 6 elemana sahip Oğuz kümesinin dört elemanlı alt kümelerinden 5 ve 6 rakamının bulunmaması durumu ayrıştırılır. P(6,4)-P(4,4) = 4321 = 24 P(6,4)-P(4,4) 4321 = 24 Sonuç 360-24=336

