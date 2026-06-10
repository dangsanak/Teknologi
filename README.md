Untuk menulis artikel panjang dengan banyak paragraf, subjudul (subheading), atau bahkan daftar (list), Anda bisa menggunakan perpaduan Tanda Kutip Miring / Backtick (`) dan Tag HTML dasar.

Pada kode sebelumnya, konten artikel ditulis dalam satu baris panjang menggunakan tanda kutip biasa ("). Agar Anda leluasa menulis artikel panjang dengan format yang rapi, berikut adalah langkah-langkah penyesuaiannya:

1. Gunakan Tanda Backtick (`) untuk Teks Multi-baris
Alih-alih menggunakan tanda kutip ganda ("), gunakan tanda backtick (biasanya terletak di sebelah kiri tombol angka 1 pada keyboard Anda). Tanda ini memungkinkan Anda menekan Enter untuk membuat baris baru di dalam kode JavaScript tanpa menyebabkan error.

2. Gunakan Tag HTML untuk Struktur Tulisan
Di dalam backtick tersebut, Anda bisa menyisipkan tag HTML untuk merapikan teks:

<h3>Judul Bagian</h3> : Untuk membuat subheading / subjudul.

<p>Isi teks...</p> : Untuk membuat satu paragraf.

<ul><li>Poin 1</li></ul> : Untuk membuat daftar (bullet points).

<b>teks tebal</b> : Untuk menebalkan teks.


{
    title: "Kucing: Peliharaan Lucu Penawar Stres",
    slug: "kucing-peliharaan-lucu",
    tags: ["Kucing", "Hewan Peliharaan", "Kesehatan Mental"],
    image: "kucingku.jpg",
    description: "Mengenal lebih dekat tingkah laku kucing dan manfaat memeliharanya.",
    
    // PERHATIKAN: Gunakan tanda backtick ( ` ) di awal dan akhir konten
    content: `
        <p>Kucing adalah salah satu hewan peliharaan paling populer di dunia. Tingkah mereka yang menggemaskan, dari mengejar bola benang hingga tidur di tempat-tempat sempit, selalu berhasil membuat pemiliknya tersenyum.</p>

        <h3>1. Manfaat Kesehatan Mental</h3>
        <p>Lebih dari sekadar lucu, penelitian menunjukkan bahwa dengkuran kucing (<i>purring</i>) berada pada frekuensi 20-140 Hertz yang dapat menurunkan tekanan darah dan meredakan stres bagi manusia di sekitarnya.</p>

        <h3>2. Mengajarkan Tanggung Jawab</h3>
        <p>Memelihara kucing mengajarkan kita tentang tanggung jawab yang konsisten. Beberapa hal yang harus diperhatikan antara lain:</p>
        <ul>
            <li>Memberikan makanan bergizi tepat waktu.</li>
            <li>Membersihkan kotak pasir (<i>litter box</i>) setiap hari.</li>
            <li>Mengajaknya bermain agar tidak stres.</li>
        </ul>

        <h3>Kesimpulan</h3>
        <p>Memelihara kucing mungkin membutuhkan dedikasi, namun imbalannya adalah kasih sayang tanpa syarat dari makhluk kecil berbulu ini. Mereka bukan sekadar hewan, melainkan bagian dari keluarga.</p>
    `
}
