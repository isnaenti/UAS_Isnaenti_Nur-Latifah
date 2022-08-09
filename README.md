# UAS_Isnaenti_Nur-Latifah
Source Code pada Greenfoot
public void act()
    {
        // Add your action code here.
        keycontrol();
        koneksi();
    }
    
    public void keycontrol()
    {
        if(Greenfoot.isKeyDown("d"))
        {
            move(5);
        }
        
        if(Greenfoot.isKeyDown("a"))
        {
            move(-5);
        }
        
        if(Greenfoot.isKeyDown("s"))
        {
            setLocation(getX(),getY()+5);
        }
        
        if(Greenfoot.isKeyDown("w"))
        {
            setLocation(getX(),getY()-5);
        }
        
        if(Greenfoot.isKeyDown("gg"))
        {
            
        }
    }
    
    public void koneksi()
    {
        
    }

Penjelasan Source Code:
Code dibawah ini merupakan cara untuk membuat class baru yaitu keycontrol dan juga koneksi.
public void act()
    {
        // Add your action code here.
        keycontrol();
        koneksi();
    }
Code dibawah ini yaitu isi dari class keycontrol yang fungsinya untuk mengatur bee bergerak seperti jika ingin ke kanan dengan mengklik tombol (d) pada keyboard. Jika ingin menggerakkan kearah kiri klik tombol (a), jika ingin kebawah klik tombol (s), dan klik tombol (w) untuk kearah bawah. Dan kemudian jika ingin memberhentikan bee dengan tombol gg pada keyboard.
 public void keycontrol()
    {
        if(Greenfoot.isKeyDown("d"))
        {
            move(5);
        }
        
        if(Greenfoot.isKeyDown("a"))
        {
            move(-5);
        }
        
        if(Greenfoot.isKeyDown("s"))
        {
            setLocation(getX(),getY()+5);
        }
        
        if(Greenfoot.isKeyDown("w"))
        {
            setLocation(getX(),getY()-5);
        }
        
        if(Greenfoot.isKeyDown("gg"))
        {
            
        }
    }
Kemudian tuntuk dapat mengkoneksikan ke dalam database kita memerlukan code untuk dapat megkoneksikannya ke dalam database. Dibawah ini adalah sourcecode dari koneksi. 
public void koneksi()
    {
        
    }
    
Membuat database ke phpmyadmin
Untuk dapat membuat database langkah pertamanya yaitu nyalakan kemudian buka phpmyadmin kemudian pilih localhost. Langkah kedua, setelah masuk ke dalam phpmyadmin kita buat database baru yang saya beri nama uas_isnaenti. Langkah ketiga, buat table pada database pada uas_isnaenti yang saya beri nama table arah, saya beri raw 2. Langkah keempat, isi raw satu dengan nama id Type yang dimasukan INT sebagai Primary Key, raw kedua dengan nama kunci Type yang dimasukan yaitu VARCHAR. 
Diberi nama kunci untuk mengatur arah pada bee yaitu jika diisikan d,a,s, ataupun w akan terjadi pergerakan pada bee. Dan jika mengetikan gg maka bee akan berhenti bergerak.
