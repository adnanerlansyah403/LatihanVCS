# Cara menghubungkan git dengan github atau remote
1. pertama buat repository local di git dengan perintah : <br>
```sh
git init
```
2. sebelumnya,buat lah terlebih dahulu folder untuk di jadikan folder repositorynya.<br> jika sudah membuat folder repositorynya. lanjut membuat file untuk nanti di kirimkan ke githubnya dengan remote. dengan perintah : <br>
```sh
git add (fileName)
```
3. setelah file di add,kita commit terlebih dahulu file/foldernya, dengan perintah : <br>
```sh
git commit -m "new file"
```
4. jika sudah membuat filenya,maka kita tinggal hubungkan/remote git yang ada di pc kita dengan github. dengan perintah : <br>
```sh
git remote add origin <alamat repository/link repositorynya>
```
5. Melakukan push untuk memasukkan file yang sudah kita buat tadi ke dalam link repository yang sudah kita remote tadi. dengan perintah : <br>
```sh
git push -u origin main
``` 
<br>
--SELESAI--











