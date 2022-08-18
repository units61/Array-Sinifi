# Array-Sinifi
## Array Sınıfı ile İlgili İçerikler

## SORT 
```
int[] sayıDizisi = {23,12,4,86,3,11,17};

Console.WriteLine("******** Sırasız Dizisi ********");
foreach (var sayi in sayıDizisi)
{
    Console.WriteLine(sayi);
}

Console.WriteLine("******** Sıralı Dizisi ********");
Array.Sort(sayıDizisi);
foreach (var sayi in sayıDizisi)
{
    Console.WriteLine(sayi);
}
```

## Clear
```
Console.WriteLine("******** Array Clear ********");
// sayiDizisi elemanlarını kullanarak 2. indexten itibaren 2 tane elemanı 0'lar
Array.Clear(sayıDizisi,2,2);
foreach (var sayi in sayıDizisi)
{
    Console.WriteLine(sayi);
}
```
## Reverse
```
Console.WriteLine("******** Array Reverse ********");
Array.Reverse(sayıDizisi);
foreach (var sayi in sayıDizisi)
{
    Console.WriteLine(sayi);
}
```
## IndexOf
```
Console.WriteLine("******** Array IndexOf ********");
Console.WriteLine(Array.IndexOf(sayıDizisi,23));
```
## Resize
```
Console.WriteLine("******** Array Resize ********");
Array.Resize<int>(ref sayıDizisi, 9);
sayıDizisi[8] = 99;
foreach (var sayi in sayıDizisi)
{
    Console.WriteLine(sayi);
}
```