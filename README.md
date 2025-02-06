![image](https://github.com/user-attachments/assets/e342723e-baf5-4d60-85c0-f82672c696c3)![image](https://github.com/user-attachments/assets/846ffb96-0f71-4423-be1b-69e694de32bf)Bu bitirme projesinde, klasik ve popüler bir oyun olan Tetris'i yeniden tasarladım. Proje kapsamında İbrahim Cem BAYKAL hocamızın geliştirdiği ICBYTES kütüphanesini kullanarak oyunun temel mekaniklerini oluşturdum. 
Amacım, programlama ve thread konusundaki bilgi ve becerilerimi geliştirmek hem de özgün bir deneyim sunan bir Tetris oyunu oluşturmaktı. Oyunda, geleneksel Japon müziği ve metal müziğin birleştiği 
"Shamisen 三味線 x electric guitar x drum Relaxing Background Music for Working or Study - 和風" adlı müziği kullanarak oynanış atmosferini daha etkileyici hale getirdim.

Projeyi Çalıştırmak için olması gereken dizin yapısı:
>GraduationProject
  >include
  >lib
  >Tetris
    >Tetris
    >Tetris.sln

Proje yukarı anlatılan dizin yapısı haline getirildikten sonra Tetris.sln çalıştırılarak Visual Studio programı üzerinden Debug 64x te çalıştırılabilir.

İlk çalışma işleminden sonra x64/Debug dizibi oluşur ve Debug un içinde Tetris.exe uygulama programı oluşur.
>GraduationProject
  >include
  >lib
  >Tetris
  >x64
    >Debug
      >Tetris.exe 

Tetris.exe uygulamasından programı çalıştırmak için ; 
  1- GraduationProject\Tetris\Tetris in içindeki Assets ve Sound klasörlerinin kopyalanmalı 
    >GraduationProject
      >include
      >lib
      >Tetris
        >Assets *
        >Sound *
  2- GraduationProject\Tetris\x64\Debug klasörünü içine yapıştırılmalı
    >GraduationProject
  >include
  >lib
  >Tetris
  >x64
    >Debug
      >Assets
      >Sound
      >Tetris.exe 
