# praktikum-12 PYTHON STRING
> NAMA : ABDUL AZIZ

>NIM : 312210022



APA ITU PYTHON STRING ?
 * String adalah jenis yang paling populer di Python.
 
* Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.

* Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

* Membuat string semudah memberi nilai pada sebuah variabel.

  # latihan 1
  
  ![Screenshot (221)](https://user-images.githubusercontent.com/116137169/209841582-c804a112-1516-472b-8f0a-c3f32a1c7619.png)
   
   > disini saya merubah kalimat "txt" menjadi "kata" agar mudah di ingat
   
   * menghitung jumlah karakter dengan menggunakan fungsi panjang atau disebut length(len)
   
   
   print(len(kata))
   
   > contoh pengetikan : 
   
                kata =len("hello world")
                print(kata)
        
      #hasil run akan ditampilkan dibawah
   
  * ambil karakter terakhir
  cara mengambil karakter yaitu dengan menggunakan [] kurung siku dan mendeklarasikan nomer di dalam kurung siku huruf yang paling kanan di definisian sebagai -1 dan tiap satu huruf ke kiri menjadi -2 dan seterusnya.
         
   > contoh pengetikan :
                  
                 kata =("Hello world")
                 print(kata[-1])
                 
  * mengambil karakter index ke -2 saampai ke 4(llo)
   menggunakan index urutan angka tersebut menggunakan : titik 2 ,titik 2 disini diartikan sebagai "sampai"
   > contoh pengetikan :
             
               kata=( "Hello world")
               print(kata[3:6])
               
             kenapa saya memasukan angka 3? karena spasi disini dihitung menjadi karater index
   
  * menghilangkan spasi pada hello world
  menggunakan fungsi replace atau mengganti untuk menghilangkan spasi
  > contoh pengetikan :
  
              kata=("Hello world")
              print(kata.replace(" ", ""))
              
              dijelaskan bahwa awalnya " " terdapat spasi menjadi "" tidak ada spasi
              
  * Ubah text menjadi huruf besar
  menggunakan fungsi upper
  > contoh peengetikan :
               
               kata=("hello world")
               print(kata.upper())
  
  * ubah teks menjadi huruf kecil
  menggunakan fungsi lower
  > contoh pengetikan :
              
              kata=(HELLO WORLD)
              print(kata.lower())
  
* ganti karakter H dengan karakter J
sama halnya dengan menghilangkan spasi seperti diatas karena pada dasarnya mengganti karakter atau merubah

jadi menggunakan fungsi replace
> contoh pengetikan :
              
              kata=("Hello world")
              print(kata.replace("H", "J"))
              
              
   ![Screenshot (222)](https://user-images.githubusercontent.com/116137169/209848563-c4be46ad-258e-4fd6-afb6-d5a5fef05cff.png)
   
   # LATIHAN 1.2
   ![Screenshot (223)](https://user-images.githubusercontent.com/116137169/209848901-8ed4f689-c669-4dad-ab0b-08617edfa2ba.png)
   
   Mmasukan kurung kurawal {} untuk menempatkan variabel umur
   > contoh pengetikan :
   
            umur = 24
            txt = 'Hello, nama saya jhon, dan umur saya adalah {0} tahun'

            print(txt.format(umur))
            
            
            ![Screenshot (220)](https://user-images.githubusercontent.com/116137169/209849573-82770cf9-9ac8-4a30-993a-17bce217e017.png)

   

