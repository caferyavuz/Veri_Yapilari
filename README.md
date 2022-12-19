# Selection Sort

[22,27,16,2,18,6] -> Insertion Sort

### 1.Soru : Yukarı verilen dizinin sort türüne göre aşamalarını yazınız:
`
Cevap :
1. Adim -> [22,27,16,2,18,6] -> Dizimizin ilk indexini saçip diğer indexleri ile karşılaştırıyoruz. Küçük sayıyı bulduğumuzda yer değiştiriyoruz.

2. Adim -> [2,27,16,22,18,6] -->ikinci indexi seçip önceki adım ile aynı işlemi yapıyoruz, ikinci en küçük sayıyı
bulduk ikinci indeximiz ie yer değiştiriyoruz. Seçilen indexten sonrasında küçük sayı kalmayana kadar bu işlemi devam ettiriyoruz.

Dizimizin son hali : [2,6,16,18,22,27] 
`
### 2.Soru : Big-O gösterimini yazınız:

`Cevap : 0(n^2)`


### 3.Soru : Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
`
Cevap :
Dizimizin son halinde 18 sayısı dizinin ortasında olduğu için **Average case** kapsamına girer.
`

### 4.Soru : [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
`
Cevap :
[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6] 

`
