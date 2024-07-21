s- div for wrapping component/items together

- Gunakan semantic element agar lebih mudah dibaca baik oleh search engiine maupun developer

### Display

Display ada yang block dan ada yg inline. Block berarti space akan terblok dan elemen selanjutnya ada dibawahnya sedangkan inline hanya menggunakan space sebesar elemen itu dan bisa lsg dilanjutkan elemen selanjutnya
![1721288185697](image/README/1721288185697.png)

- Gunakan colspan untuk merge columns dan rowspan untuk merge baris. Ingat, buat dulu mau berapa baris dan kolom baru lakukan merge

### Form element

![1721362146040](image/README/1721362146040.png)
![1721362253904](image/README/1721362253904.png)

- label, berikan atribut for agar tau ke input yg mana
- input, berikan name sehingga ketika submit get value dan name akan masuk ke query params
- Radio button, input dgn type radio dengan memberikan name yg sama untuk opsi yg ada
- Dropdown, input dgn type select dengan membuat tag option dengan value dan label dlm children di dalam children select nya.
- Checkbox, input dgn type checkbox
- Textarea, input dn type textarea. Specify berapa cols dan rows untuk luas text area, jika isian lebih besar maka akan ada scrollbar
  [**Lebih lengkap cek docs berikut**](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

## Button dalam Form

secara default button dalam form akan jadi submit button, agar menjadi button biasa bisa specify type nya button atau pakai input tapi typenya button

```html
<button type="button">Button Biasa</button>
<input type="button" value="Input type Button" />
<button type="submit">Submit</button>
```

### Method dan Validasi pada Form

- GET, sesuai dengan attribute name maka data isian akan muncul sebagai query params.
  http://127.0.0.1:5500/submit?username=ssfsdf&email=sugengdatascience%40gmail.com&password=sdsdfs

-POST, tidak akan muncul di query params tapi di network formdata akan masih muncul.

> Gunakan sesuai kebutuhan, untuk cridential atau data yg rahasia lebih baik pakai post. Sebaliknya jika agar user tau di halaman/filter apa dan ketika dishare hasilnya sama maka pakai get

Kita bisa menggunakan fitur bawaan HTML elemen unutk melakukan client side validation pada form kita, caranya tinggal kita tambahkan misal

- required jika harus diisi
- minleght dan maxlength, untuk minimal dan maksimal character
- min dan max, untuk min max number
  dsb bisa di cek di docs berikut:[**disini**](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
