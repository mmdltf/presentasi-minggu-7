
# **Presentasi-minggu-7**

## **Prop-types**
prop-types adalah sebuah depedensi yang digunakan untuk memvalidasi tipe data yang dikirim dari parent ke child. prop-types merupakan sebuah aktivitas preventif untuk mencegah terjadinya error karena perbedaan tipe data ketika meng-input pada proses logic atau secara mudah bisa dibilang sebagai cara kita untuk memastikan tipe data yang masuk pada suatu komponen. Jika data yang di input tidak sesuai maka akan terjadi `error`.
### Penggunaan prop-types
Hal yang pertama harus dilakukan ketika ingin menggunakan prop-types adalah melakukan penginstalan pada terminal dengan command :
`npm install prop-types`
ketika proses penginstalan sudah selesai maka hal yang harus dilakukan setelah itu adalah 
`{import PropTypes from 'prop-types'}` pada komponen yang ingin digunakan. 
## **Router**
Router sebuah *depedencies* pada library react JS yang digunakan untuk routing dimana dalam sebuah SPA (single page application) kita dapat melakukan navigasi ke komponen lain menggunakan URL , tanpa harus melakukan proses *reload* 
### Penggunaan Router
Dalam penggunan react router hal yang dilakukan :
- Pertama lakukan- penginstalan pada terminal `npm install react-router-dom@ (versi yang ingin diinstall)`. 
> setelah **@** merupakan versi yang akan diinstall

- Kemudian pada `index.js` import `{BrowserRouter}` 
jadikan `</App>` sebagai child nya. 

- Lalu pada `App.js` import `{Routes, Route}` kedua tersebut akan digunakan selama proses Routing. 

- Dalam return buat sebuah `<Routes></Routes>` sebagai parent nya dan `<Route/>` sebagai child nya
 
 ### Nested Router
 Nested router merupakan sebuah fitur yang dapat dibilang powerful karena kita dapat menavigasi sebuah routing-an lebih dari satu level misal www.luthfi.com / aboutme/ portofolio/ .... yang dengan merubah `<Route/>` yang menggunakan single-tag menjadi double-tag. Implementasi nya seperti dibawah:
 ![enter image description here](https://i.postimg.cc/zfxQ0Gqq/image.png)

## **React Redux**
React Redux merupakan sebuah depedensi yang digunakan untuk memanage 

redux merupakan sebuah state management dimana kita dapat memanage data secara terpusat pada sebuah {store}. Redux memiliki 3 komponen utama yaitu store, reducer dan action. 
- Store - sebuah fungsi dimana data yang digunakan disimpan. 
- Reducer - sebuah fungsi dimana kita memanipulasi sebuah data pada store 
- Action - sebuah fungsi dimana kita dapat memerintah reducer untuk memanipulasi store data. Untuk menginstall react redux kita dapat menggunakan command ``npm install redux react-redux ``
## **Thunk**
Thunk merupakan sebuah middleware yang memungkinkan action pada redux dapat menjalankan proses asynchronous. action (dispatch) tidak bisa dijalankan pada proses asynchoronous harus secara scynchronous. Karena itu, kita akan menggunakan thunk agar bisa menjalankan proses asynchronous. Thunk sendiri merupakan sebuah tempat/ wadah agar bisa menjalankan proses asynchronous pada action . Redux thunk juga memiliki 2 komponen tambahan yaitu Middleware dan Action Creator. 
Middleware sendiri digunakan memproses data yang dikirimkan oleh Action dan Action Creator digunakan untuk mengirimkan data ke Store. Untuk menginstall react redux thunk kita dapat menggunakan command
`npm install redux react-redux redux-thunk`




