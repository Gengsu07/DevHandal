## CSS (Cascading Style Sheet)

![1721614824002](image/readme/1721614824002.png)
![1721615018419](image/readme/1721615018419.png)
![1721617794708](image/readme/1721617794708.png)

##### Inline

di setiap element

```CSS
<button
        style="
          background-color: blue;
          color: white;
          padding: 5px;
          padding-left: 15px;
          padding-right: 15px;
        "
      >
        Klik
      </button>
```

##### Style Element

di Head,

```CSS
 <style>
      button {
        background-color: blue;
        color: white;
        padding: 5px;
        padding-left: 15px;
        padding-right: 15px;
      }
    </style>
```

> **Inline dan Style element tidak direkomendasikan karena akan memenuhi file html.
> Best Pratice Gunakan perinsip separation concern, buat file css sendiri kemudian masukkan linknya ke html**

---

### Sistem Warna

- RGB
- Hex
- Named color
  referensi cari warna:
  [https://htmlcolorcodes.com]()
  [https://cssgradient.io]()

### Text Properti

- text-align : alignmen dari text/paragraf
- font-weight : ketebalan text dri 100-900. 400-600 normal
- text-decoration : untuk memberikan variasi pada text atau menghilangkan default style misal pd anchor
- line-height : Spasi antar baris
- letter-spacing : memberikan jarak antar huruf

---

### Ukuran pada CSS

![1721642380931](image/readme/1721642380931.png)
