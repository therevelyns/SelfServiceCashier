# Self  Service Cashier
#### Self Service Cashier adalah sistem kasir super di sebuah supermarket yang memungkinkan pelanggan, dimana pun mereka berada, dapat memproses belanjaannya sendiri secara langsung.


# Objectives & Requirements
#### Program yang dibuat mampu:
#### 1. Membuat ID transaksi pelanggan
#### 2. Memasukkan sendiri item yang pelanggan ingin beli (add_item)
#### 3. Melakulan pembaruan data item belanjaan (update_item, update_qty, update_price)
#### 4. Menghapus salah satu item yang sudah diinput sebelumnya (delete_transaction)
#### 5. Mereset data item belanjaan yang sudah lebih dulu diinput sebelumnya (reset_transaction)
#### 6. Melakukan pengecekan data yang sudah diinput (check_order)


# Alur

## Workflow
![image](https://user-images.githubusercontent.com/109421939/218322301-301fd6e2-355d-49d5-ae74-c25bb98ba3be.png)

#### - Memahami latar belakang masalah
#### - Memahami & membuat requirements/objectives/fiturs sesuai dengan latar belakang masalah
#### - Mengajukan solusi, yaitu sebuah obyek class untuk mendeskripsikan transaksi pelanggan
####   (atribut: nama, jumlah, harga) & (method: add_item, update, reset, delete)
#### - pseudocode add_item method
####   input: nama, jumlah, harga
####   output: -
#### - pseudocode update_name, update_qty, update_price
####   input: nama item, qty item, harga item
####   output: -
#### - pseudocode check_order
####   input: nama item, qty item, harga_item
####   output: dictionary dengan data terupdate
#### - pseudocode reset_ & delete_


# Hasil Test Case
#### 1. Penambahan item baru
![image](https://user-images.githubusercontent.com/109421939/218330318-6cf5ad45-82d3-44f0-9caa-b2d38a9c7c35.png)

#### 2. Pembaruan data
![image](https://user-images.githubusercontent.com/109421939/218330184-bc88f665-1632-4b12-b458-5dcf58b028ce.png)

#### 3. Pengecekan data yang sudah diinput
![image](https://user-images.githubusercontent.com/109421939/218330246-59661bfa-c56d-4613-bd83-04b1d2641e61.png)

#### 4. Menghapus data tertentu
![image](https://user-images.githubusercontent.com/109421939/218330572-8ece63c4-03cd-45df-ac55-c93a29d45951.png)

#### 5. Menghapus semua data
![image](https://user-images.githubusercontent.com/109421939/218330737-a43d191d-328f-41ed-a3f5-e703d10d848f.png)

