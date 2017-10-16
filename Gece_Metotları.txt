Sistem Kullanımı;

ad alanı MetotlarGece
{
    birinci sınıf program
    {
        statik int f; // Global kapsam
        static int alan (int a, int b)
        {
            
            int d = 0; // Lokal kapsam metodunda geçerli
            a * b döndür; 
        }

        
        
        static void Yaz ()
        {
            Console.WriteLine ("************ ALAN HESAPLA **********");
            
        }
        static int alan (int yarıkap)
        {
            dönüş Convert.ToInt16 (Math.PI * yarıkap * yarıkap) dönüşü;
        }

        static int alan (int k1, int k2, int k3)
        {
            float s = (k1 + k2 + k3) / 2;
            return Convert.ToInt16 (Math.Sqrt (s * (s - k1) * (s - k2) * (s - k3)));
        }

        static void Ana (string [] args)
        {
            Yaz ();

            

            Console.WriteLine ("Bir sekil secmek icin Rakam Giriniz" +
                ": 1. Daire 2. Dortgen 3. Ucgen");
            int secenek = Convert.ToInt16 (Console.ReadLine ());
            int sonuc = 0;

            anahtar (secenek)
            {
                dava 1:
                    Console.WriteLine ("Yaricap degerini Giriniz");
                    int yc = Convert.ToInt16 (Console.ReadLine ());
                    sonucu = alan (yc);
                    kırılma;
                Durum 2:
                    Console.WriteLine ("Ilk kenar:");
                    int a = Convert.ToInt16 (Console.ReadLine ());
                    Console.WriteLine ("Diger Kenar");
                    int b = Convert.ToInt16 (Console.ReadLine ());
                    sonucu = alan (a, b);
                    kırılma;
                dava 3:
                    Console.WriteLine ("Ilk kenar:");
                    int x = Convert.ToInt16 (Console.ReadLine ());
                    Console.WriteLine ("Ikinci Kenar");
                    int y = Convert.ToInt16 (Console.ReadLine ());
                    Console.WriteLine ("Diger Kenar");
                    int z = Convert.ToInt16 (Console.ReadLine ());
                    sonucu = alan (x, y, z);
                    kırılma;
                varsayılan:
                    sonucu = 0;
                    kırılma;


               }
            Console.WriteLine ("Sectiginiz Sekil Icin Hesaplanan Alan:" + sonucu);

        }
    }
}