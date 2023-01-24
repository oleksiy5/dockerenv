# dockerenv

 66         public int Mod2(int i, string log)
 67         {
 68            int mod = i % 2;
 69            int sleep = (3000);
 70            
 71            Console.WriteLine(log+";time"+sleep+";result "+mod);
 72 
 73            Thread.Sleep(sleep);
 74 
 75            return mod;
 76         }  

