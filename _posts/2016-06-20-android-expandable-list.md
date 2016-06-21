---
layout: post
title: "Android Expandable ListView "
quote: "list with parrent"
image:
      url: /blogs/assets/images/get-start-ionic/cover.png
      
      
video: false
comments: true
theme_color: 302F2D
---
# apa itu?
expandable list view , bisa dibilang sebagai <b>group listview</b> , atau <b>listview</b> yang di group-group kan ,
atau listview yang setiap item nya memiliki anak lagi didalamnya

<strong>contoh:<br/></strong>
list kelas di sekolah :
<ul>
    <li>
        <h6>kelas 3</h6>
        <ul>
            <li>kelas 3 - A</li>
            <li>kelas 3 - B</li>
            <li>kelas 3 - C</li>
        </ul>
    </li>
        <li>
            <h6>kelas 2</h6>
            <ul>
                <li>kelas 2 - A</li>
                <li>kelas 2 - B</li>
                <li>kelas 2 - C</li>
            </ul>
        </li>
            <li>
                <h6>kelas 1</h6>
                <ul>
                    <li>kelas 1 - A</li>
                    <li>kelas 2 - B</li>
                    <li>kelas 3 - C</li>
                </ul>
            </li>
</ul>

seperti itu , jadi awal nya ada 3 item di list tersebut yaitu list kelas 1 , kelas 2 , kelas 3 , lalu saat di klik akan muncul lagi 
child-child dari kelas tersebut ,misal <b>kelas 3 : [kelas 3-A,kelas 3-B , kelas-C]</b>


# konsep listview pada android
pada android untuk dapat menghasilkan sebuat listview , kita memerlukan :
<ol>
    <li>
        <b>object listview</b>
        <p>
            object listview yang akan menampung listviewnya
        </p>
    </li>
    <li>
            <b>class model</b>
            <p>
                class model , di gunakan untuk menampung data yang di perlukan list view
                , misal kita ingin menampilkan judul ,dan tahun pada listview
                maka kita perlu menampung nama dan judul tersebut di kelas model ini
            </p>
        </li>
    <li>
           <b>layout xml untuk kontent</b>
                   <p>
                     tempat kita mendefinikan bentuk tampilan dari listview kita nanti
                   </p>
               </li>
        
    <li>
        <b>class adapter</b>
        <p>
           class adapter digunakan untuk menghubungkan antara layout content item yang kita buat
           dan data dari kelas model agar dapat diproses di list view
        </p>
    </li>
</ol>




