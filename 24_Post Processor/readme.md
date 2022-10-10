# Summary Section 24
## Post Processor
"**Athif Zakiyanto_QE Kelas A**"

-  Post Processor adalah bagian dari test plan yang merupakan sebuah aksi yang berjalan pada saat proses setelah dilakukan, proses ini merupakan sebuah proses request ke sebuah alamat web. Request yang dilakukan post processor pada umumnya untuk mengekstrak value yang didaptkan dari hasil mengakses sebuah alamat web seperti data-data pada JSON atau pada bagian response yang lain.

- JSON Path digunakan untuk mengekstrak isi dari JSON response. Beberapa ekspresi yang umum digunakan :
  * $ = root element
  * . = child operator (object)
  * [] = child operator (array)
  * .. = recursive descent (langsung ke objek)
  * *  = Wild card (all things)
  * [start:end] = array slice operator borrowed

- JMeter Post processor merupakan inti dari performance testing
